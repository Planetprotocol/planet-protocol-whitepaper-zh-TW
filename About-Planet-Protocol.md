# Planet Protocol

**連結全球 DeFi 資金與實體農業資產**

---

我們相信,新興市場每年 1,700 億美元的農業融資缺口——其為總額超過 4,500 億美元的小農信貸缺口的一部分——是去中心化金融與實體經濟交會處最具潛力而尚未被開發的機會之一。東南亞數以百萬計的農業生產者無法取得可負擔且及時的資金,原因並非他們不具備銀行往來資格,而是傳統金融基礎設施從一開始就不是為服務他們而設計的。

Planet Protocol 是建構於以太坊之上的去中心化實體資產(RWA)融資平台。它透過智慧合約治理的批次融資、碎片化參與代幣,以及透明的託管生命週期,將全球 DeFi 資金直接與農業生產者連結,藉此移除中間層、降低成本,並釋放以實體生產性資產為後盾的收益。

Planet 上的每一個批次都代表一筆真實的農業融資操作:可查核的生產者、明確定義的里程碑,以及在鏈上強制執行的確定性資金流。參與者購買 ERC-1155 碎片化代幣以資助特定批次,並在批次順利完成後透過銷毀領取機制取得分配。

Planet Protocol 不是借貸協議、不是收益聚合器,也不是投機工具。它是一類全新鏈上實體資產的基礎設施,而這類資產植基於糧食生產、供應鏈物流與新興市場成長的真實經濟。

---

## 核心原則

**預設透明** — 所有資金流、狀態轉換與里程碑事件皆記錄於鏈上,所有參與者均可檢視。

**真實資產,真實收益** — 收益來自實際的農業融資操作,而非代幣增發或反身性的激勵循環。

**確定性執行** — 智慧合約強制執行批次生命週期,不設人工覆寫。資金僅在預先定義的條件成立時移動。

**無需許可的參與** — 任何持有 Web3 錢包的人皆可參與批次融資,不受地域或機構身分限制。

**風險隔離** — 每個批次都是獨立的經濟單元。單一批次的表現不會影響其他批次。

---

## 運作方式概述

1. **批次建立** — 農業融資方提交融資申請。Planet Labs 查核其底層營運狀況,並透過 BatchFactory 合約部署新批次。

2. **初級銷售** — DeFi 參與者購買 ERC-1155 碎片化 RWA 代幣,代表其在該批次中的持份。所有資金進入專屬的 EscrowVault。

3. **里程碑執行** — 隨著現實世界的里程碑(種植、生長、收成)被查核並於鏈上確認,資金分階段撥付予融資方。

4. **收益分配** — 批次完成後,回款存入 ClaimVault。代幣持有人銷毀其 RWA 代幣以領取相應比例的分配。

---

## 快速連結

| 章節 | 說明 |
|---|---|
| [運作方式](Protocol/How-It-Works.md) | 完整批次生命週期 |
| [智慧合約](Protocol/Smart-Contracts.md) | 五合約架構 |
| [EscrowVault 託管金庫](Protocol/EscrowVault.md) | 七狀態託管機 |
| [銷毀領取機制](Protocol/Burn-to-Claim.md) | ClaimVault 贖回機制 |
| [查核架構](Protocol/Verification.md) | 五層查核架構 |
| [單位經濟](Economics/Unit-Economics.md) | 批次層級財務模型 |
| [商業模式](Economics/Business-Model.md) | 平台費用結構 |
| [融資方擔保機制](Economics/Originator-Security.md) | $PNT 質押門檻 |
| [積分計畫](Economics/Points-Program.md) | Planet 積分與空投權重 |
| [市場機會](Market/Market-Opportunity.md) | 東南亞農業融資 |
| [為什麼選擇 Planet](Market/Why-Planet.md) | 競爭定位 |
| [發展藍圖](Roadmap.md) | 開發里程碑 |
| [團隊](Team.md) | 核心成員 |
| [風險揭露](Risks.md) | 風險說明 |
| [法律與合規](Legal-and-Compliance.md) | 法規架構 |
| [免責聲明](Disclaimers.md) | 法律免責聲明 |

---

**網站:** [planetprotocol.net](https://planetprotocol.net)
**聯絡:** [support@planetprotocol.net](mailto:support@planetprotocol.net)
**開發者:** Planet Labs
**法人實體:** Planet Digital Labs Limited(香港)
