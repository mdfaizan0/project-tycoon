# Project-Tycoon: Board and Economy Master Sheet (Legal v2)

This document defines the physical layout of the 44-space board and the underlying economic values for the game.

## 1. Economic Constants
| Param | Value | Description |
| :--- | :--- | :--- |
| **Starting Cash** | $1,400 | Initial capital for each player. |
| **Salary (BEGIN)** | $250 | Collected when passing or landing on BEGIN. |
| **Prison Fine** | $75 | Paid to leave Prison early. |
| **Income Tax** | $300 | Fixed deduction on landing. |
| **Wealth Tax** | $150 | Fixed deduction on landing. |
| **Mortgage Rate** | 60% | Cash received from bank when mortgaging. |
| **Interest Rate** | 15% | Paid (on mortgage value) when un-mortgaging or trading. |

---

## 2. The Master Board (44 Spaces)

### Side 1: Early Stage (Bottom)
| Index | Name | Type | Color / Details |
| :--- | :--- | :--- | :--- |
| 0 | 🚀 **BEGIN** | Corner | Salary Start Point |
| 1 | 🔘 **Slate Terrace** | Property | Slate |
| 2 | 🔘 **Stone Harbor** | Property | Slate |
| 3 | ❓ **City Vault** | Card | Draw Card |
| 4 | 🔘 **Basalt Blvd** | Property | Slate |
| 5 | 🚂 **Rail #1** | Railway | Rail #1 |
| 6 | 💸 **Income Tax** | Tax | Pay $300 |
| 7 | 🟢 **Pine Crest** | Property | Teal |
| 8 | ❓ **Chance** | Card | Draw Card |
| 9 | 🟢 **Moss Garden** | Property | Teal |
| 10 | 🟢 **Fern Valley** | Property | Teal |

### Side 2: Growth (Left)
| Index | Name | Type | Color / Details |
| :--- | :--- | :--- | :--- |
| 11 | ⛓️ **PRISON** | Corner | Delay / Penalty Zone |
| 12 | 🟡 **Topaz Court** | Property | Amber |
| 13 | 🟡 **Saffron Square** | Property | Amber |
| 14 | ❓ **City Vault** | Card | Draw Card |
| 15 | 🚂 **Rail #2** | Railway | Rail #2 |
| 16 | ⚡ **Electric** | Utility | Utility #1 |
| 17 | 🚂 **Rail #3** | Railway | Rail #3 |
| 18 | 🟡 **Ochre Alley** | Property | Amber |
| 19 | 🔴 **Ruby Ridge** | Property | Crimson |
| 20 | 🔴 **Garnet Gate** | Property | Crimson |
| 21 | 🔴 **Scarlet Sands** | Property | Crimson |

### Side 3: Prime (Top)
| Index | Name | Type | Color / Details |
| :--- | :--- | :--- | :--- |
| 22 | 🏙️ **URBAN PLAZA** | Corner | Neutral Zone |
| 23 | 🟢 **Jade Junction** | Property | Emerald |
| 24 | 🟢 **Olive Park** | Property | Emerald |
| 25 | ❓ **Fortune** | Card | Draw Card |
| 26 | 🟢 **Mint Meadows** | Property | Emerald |
| 27 | 🚂 **Rail #4** | Railway | Rail #4 |
| 28 | 💧 **Water** | Utility | Utility #2 |
| 29 | 🔵 **Azure Heights** | Property | Cobalt |
| 30 | ⚡ **Fiber** | Utility | Utility #3 |
| 31 | 🔵 **Indigo Isle** | Property | Cobalt |
| 32 | 🔵 **Navy Marina** | Property | Cobalt |

### Side 4: Elite (Right)
| Index | Name | Type | Color / Details |
| :--- | :--- | :--- | :--- |
| 33 | 🚓 **TRIP TO PRISON** | Corner | Send to Prison |
| 34 | 🟣 **Lavendar Loft** | Property | Amethyst |
| 35 | 🟣 **Orchid Estate** | Property | Amethyst |
| 36 | ❓ **City Vault** | Card | Draw Card |
| 37 | 🟣 **Violet Villa** | Property | Amethyst |
| 38 | 🚂 **Rail #5** | Railway | Rail #5 |
| 39 | ❓ **Fortune** | Card | Draw Card |
| 40 | 🟡 **Crown Plaza** | Property | Gold |
| 41 | 🟡 **Zenith Tower** | Property | Gold |
| 42 | 🟡 **Titan Terrace** | Property | Gold |
| 43 | 💸 **Wealth Tax** | Tax | Pay $150 |

### 2.5 Board Layout Visualization (Grid View)

Below is a spatial map of all 44 spaces normalized to 10 tiles between corners.

| Corner | Side 3 | Side 3 | Side 3 | Side 3 | Side 3 | Side 3 | Side 3 | Side 3 | Side 3 | Side 3 | Corner |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 🏙️<br>**URBAN<br>PLAZA** | 🟢<br>Jade | 🟢<br>Olive | ❓<br>Fort | 🟢<br>Mint | 🚂<br>Rail #4 | 💧<br>Water | 🔵<br>Azure | ⚡<br>Fiber | 🔵<br>Indi | 🔵<br>Navy | 🚓<br>**TRIP TO<br>PRISON** |
| 🔴<br>Scarl | | | | | | | | | | | 🟣<br>Laven |
| 🚂<br>Rail #2 | | | | | | | | | | | 🟣<br>Orchi |
| 🔴<br>Garne | | | | | | | | | | | ❓<br>Vault |
| 🔴<br>Ruby | | | | | | **TYCOON** | | | | | 🟣<br>Viole |
| 🚂<br>Rail #3 | | | | | | | | | | | 🚂<br>Rail #5 |
| ⚡<br>Electric | | | | | | | | | | | ❓<br>Fortune |
| 🟡<br>Ochre | | | | | | | | | | | 🟡<br>Crown |
| ❓<br>Vault | | | | | | | | | | | 🟡<br>Zenit |
| 🟡<br>Saffr | | | | | | | | | | | 💸<br>Wealth |
| 🟡<br>Topaz | | | | | | | | | | | 🟡<br>Titan |
| ⛓️<br>**PRISON** | 🟢<br>Fern | 🟢<br>Moss | ❓<br>Fortune | 🟢<br>Pine | 🚂<br>Rail #1 | 💸<br>Inc. T | 🔘<br>Basalt | ❓<br>Vault | 🔘<br>Stone | 🔘<br>Slate | 🚀<br>**BEGIN** |

**Legend:**
- 🔴 Crimson | 🟡 Amber | 🟢 Emerald | 🔵 Cobalt | 🟣 Amethyst | 🟡 Gold | 🔘 Slate | 🟢 Teal
- ❓ Chance | 🚂 Railway | ⚡ Utility | 💸 Tax
- 🕹️ **Note**: 
    - Grid labels are shortened for mobile visibility. Refer to Side Tables for full names.
    - The property names are just placeholders for now, we will change them later.
    - The board structure is **final**.

---

## 3. Tiered Economics (Pricing & Rent)

### 3.1 Construction Cost Logic
Building costs are determined by the **Property Tier (Categorization)**. Higher-tier properties require more capital to develop, reflecting their prime locations and higher revenue potential.

| Tier | Categorization | House/Hotel Cost |
| :--- | :--- | :--- |
| **Slate** | Early Stage | **$50** per building |
| **Teal** | Growth | **$75** per building |
| **Amber** | Mid-market | **$100** per building |
| **Crimson** | High-Traffic | **$125** per building |
| **Emerald** | Prime | **$150** per building |
| **Cobalt** | Upper Class | **$175** per building |
| **Amethyst**| High Value | **$200** per building |
| **Gold** | Elite | **$250** per building |

---

### 3.2 Master Rent Table
This table defines the specific economic progression for every property on the board. **Titan Terrace** is capped at **$3,000**.

| ID | Property Name | Price | Mtg | House | Base | 2x | 1H | 2H | 3H | 4H | Hotel |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 1 | 🔘 Slate Terrace | $60 | $36 | $50 | $6 | $12 | $30 | $90 | $270 | $400 | $550 |
| 2 | 🔘 Stone Harbor | $60 | $36 | $50 | $6 | $12 | $30 | $90 | $270 | $400 | $550 |
| 4 | 🔘 Basalt Blvd | $80 | $48 | $50 | $8 | $16 | $40 | $100 | $300 | $450 | $600 |
| 7 | 🟢 Pine Crest | $100 | $60 | $50 | $10 | $20 | $50 | $150 | $450 | $625 | $750 |
| 9 | 🟢 Moss Garden | $100 | $60 | $50 | $10 | $20 | $50 | $150 | $450 | $625 | $750 |
| 10 | 🟢 Fern Valley | $120 | $72 | $50 | $12 | $24 | $60 | $180 | $500 | $700 | $900 |
| 12 | 🟡 Topaz Court | $140 | $84 | $100 | $14 | $28 | $70 | $200 | $550 | $750 | $950 |
| 13 | 🟡 Saffron Square | $140 | $84 | $100 | $14 | $28 | $70 | $200 | $550 | $750 | $950 |
| 18 | 🟡 Ochre Alley | $160 | $96 | $100 | $16 | $32 | $80 | $220 | $600 | $800 | $1,050 |
| 19 | 🔴 Ruby Ridge | $180 | $108 | $100 | $18 | $36 | $90 | $250 | $700 | $925 | $1,100 |
| 20 | 🔴 Garnet Gate | $180 | $108 | $100 | $18 | $36 | $90 | $250 | $700 | $925 | $1,100 |
| 21 | 🔴 Scarlet Sands | $200 | $120 | $100 | $20 | $40 | $100 | $300 | $750 | $975 | $1,200 |
| 23 | 🟢 Jade Junction | $220 | $132 | $150 | $22 | $44 | $110 | $330 | $800 | $1,050 | $1,300 |
| 24 | 🟢 Olive Park | $220 | $132 | $150 | $22 | $44 | $110 | $330 | $800 | $1,050 | $1,300 |
| 26 | 🟢 Mint Meadows | $240 | $144 | $150 | $24 | $48 | $120 | $360 | $850 | $1,100 | $1,400 |
| 29 | 🔵 Azure Heights | $260 | $156 | $150 | $26 | $52 | $130 | $390 | $900 | $1,150 | $1,500 |
| 31 | 🔵 Indigo Isle | $260 | $156 | $150 | $26 | $52 | $130 | $390 | $900 | $1,150 | $1,500 |
| 32 | 🔵 Navy Marina | $280 | $168 | $150 | $28 | $56 | $150 | $450 | $1,000 | $1,200 | $1,600 |
| 34 | 🟣 Lavendar Loft | $300 | $180 | $200 | $30 | $60 | $175 | $500 | $1,100 | $1,300 | $1,800 |
| 35 | 🟣 Orchid Estate | $300 | $180 | $200 | $30 | $60 | $175 | $500 | $1,100 | $1,300 | $1,800 |
| 37 | 🟣 Violet Villa | $320 | $192 | $200 | $35 | $70 | $200 | $600 | $1,300 | $1,500 | $2,000 |
| 40 | 🟡 Crown Plaza | $350 | $210 | $200 | $40 | $80 | $250 | $750 | $1,500 | $1,800 | $2,400 |
| 41 | 🟡 Zenith Tower | $350 | $210 | $200 | $40 | $80 | $250 | $750 | $1,500 | $1,800 | $2,400 |
| 42 | 🟡 Titan Terrace | $400 | $240 | $200 | $50 | $100 | $350 | $1,000 | $1,800 | $2,200 | $3,000 |

> Note: 
> - **Price** is purchase cost. 
> - **Mtg** is mortgage value (60%). 
> - **House** is construction cost. 
> - **Base Rent** is for unimproved property. 
> - **2x** for full set.


### 3.3 Special Asset Economics
This section defines the values and mechanics for non-property assets.

#### Railways
| Asset Name | Price | Mtg | Rental Logic |
| :--- | :---: | :---: | :--- |
| 🚂 **Railways (5)** | $200 | $120 | 1: $25 \| 2: $50 \| 3: $100 \| 4: $200 \| 5: **$400** |

#### Utilities
| Asset Name | Price | Mtg | Multiplier Logic (Dice Roll) |
| :--- | :---: | :---: | :--- |
| ⚡💧 **Utilities (3)** | $150 | $90 | 1: **4x** \| 2: **10x** \| 3: **20x** |

#### Tax Spaces
| Tax Type | Amount | Logic |
| :--- | :---: | :--- |
| 💸 **Income Tax** | $300 | Fixed deduction upon landing. |
| 💸 **Wealth Tax** | $150 | Fixed deduction upon landing. |

---

## 4. Final Configuration Notes
- **Corner Names**: Reverted to **BEGIN**, **PRISON**, **URBAN PLAZA**, and **TRIP TO PRISON** per user preference.
- **Tax Names**: Reverted to **Income Tax** and **Wealth Tax**.
- **Economy**: Maintaining the overhauled values ($1,400 start, $250 salary, 60% mortgage, 15% interest) for healthy game pacing.
- **Vibe**: Keeping the premium color groups (Slate to Gold) for a modern, high-end feel.
