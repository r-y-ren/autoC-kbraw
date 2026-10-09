# Kaggle ListPages API 页导出：Evaluation

- 来源: https://www.kaggle.com/api/i/competitions.PageService/ListPages (competitionId=168019)
- 抓取日期: 2026-10-05
- mimeType: text/markdown | order: 3

---

Each day your team is able to submit up to 5 agents to the competition. Each submission will play Episodes (games) against other agents on the ladder that have a similar skill rating. Over time skill ratings will go up with wins or down with losses and evened out with ties. To reduce the number of agents playing and increase the number of episodes each team participates in, we only track the latest 2 submissions and use those for final submissions.

Every agent submitted will continue to play episodes until the end of the competition, with newer agents playing a much more frequent number of episodes. On the leaderboard only your best scoring agent will be shown, but you can track the progress of all of your submissions on your Submissions page.

Each Submission has an estimated Skill Rating which is modeled by a Gaussian N(μ,σ2) where μ is the estimated skill and σ represents the uncertainty of that estimate which will decrease over time.

When you upload a Submission, we first play a Validation Episode where that Submission plays against copies of itself to make sure it works properly. If the Episode fails, the Submission is marked as Error and you can download the agent logs to help figure out why. Otherwise, we initialize the Submission with μ0=600 and it joins the pool of All Submissions for ongoing evaluation.

We repeatedly run Episodes from the pool of All Submissions, and try to pick Submissions with similar ratings for fair matches. Newly submitted agents will be given an increased rate in the number of episodes run to give you faster feedback.

**Ranking System** 

After an Episode finishes, we'll update the Rating estimate for all Submissions in that Episode. If one Submission won, we'll increase its μ and decrease its opponent's μ -- if the result was a draw, then we'll move the two μ values closer towards their mean. The updates will have magnitude relative to the deviation from the expected result based on the previous μ values, and also relative to each Submission's uncertainty σ. We also reduce the σ terms relative to the amount of information gained by the result. The score by which your agent wins or loses an Episode does not affect the skill rating updates.

**Final Evaluation**

At the submission deadline, additional submissions will be locked. Games will continue to run for approximately two weeks to continue to reduce uncertainty, especially for new agents. A final Bradley-Terry tournament will be run on those episodes to produce the final leaderboard.