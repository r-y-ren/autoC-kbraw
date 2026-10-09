# Kaggle CLI 侧验证记录

- 命令: `kaggle competitions list -s "ptcg"`（本机已配置凭据，官方 CLI）
- 抓取日期: 2026-10-05
- 目的: 核对 ListPages API Timeline 页模板变量未解析的 deadline 字段（平台权威字段）

```text
ref                                                                                          deadline             category         reward  teamCount  userHasEntered  userRank  
-------------------------------------------------------------------------------------------  -------------------  ----------  -----------  ---------  --------------  --------  
https://www.kaggle.com/competitions/pokemon-tcg-ai-battle-challenge-strategy                 2026-09-13 23:59:00  Featured    240,000 Usd        939           False         0  
https://www.kaggle.com/competitions/the-pokemon-company-ptcg-ai-battle-challenge-playground  2027-01-08 23:59:59  Playground         Swag        172           False         0  
https://www.kaggle.com/competitions/pokemon-tcg-ai-battle                                    2026-08-31 23:59:00  Featured      Knowledge       6807           False         0  
```

要点：本赛 deadline **2027-01-08 23:59:59**（UTC，Kaggle 平台字段）；category=Playground；reward=Swag（无金额）；teamCount=172（与列表页快照一致，双源）；userHasEntered=False（本框架尚未报名）。
