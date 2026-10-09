# Kaggle ListPages API 页导出：How to Play Pokémon TCG

- 来源: https://www.kaggle.com/api/i/competitions.PageService/ListPages (competitionId=168019)
- 抓取日期: 2026-10-05
- mimeType: text/markdown | order: 11

---

Download the most recent rulebook for the Pokémon Trading Card Game.

View the Competition [Data Page](https://www.kaggle.com/competitions/the-pokemon-company-ptcg-ai-battle-challenge-playground/data) for more information on cards and decks available for this tournament.

Get information on the Pokémon TCG, the Play! Pokémon program and more on The Pokémon Company's [Rules & Resources page](https://www.pokemon.com/static-assets/content-assets/cms2/pdf/trading-card-game/rulebook/meg_rulebook_en.pdf).

### Simulator API Documentation
Battles are run on the Pokémon TCG battle simulator built for `kaggle-environments`.

Each turn, your agent receives an observation — including game logs, the current board state, and a list of legal options — and returns the indices of the options it selects. The engine only ever presents legal moves.

API documentation: https://matsuoinstitute.github.io/cabt/

Note, any differences between official Pokémon TCG rules and simulator behavior will be documented in the competition forums.