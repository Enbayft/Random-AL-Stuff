<body>
  <h1 align="center">
    Heavy Cruiser Guns: AP vs HE
  </h1>
</body>

## Abstract
Heavy cruisers have two main choices: armor piercing and high explosive guns. Both offer situational advantages. In majority of cases, high explosive guns work best, however, there are situations in which armor piercing guns offer better advantages. This paper will look at these two types overall and then break them down. It will also discuss, briefly, specific guns tied to specific ships.

Heavy cruiser guns (203mm) are burst-like guns in Azur Lane (AL). They are split into two categories: Armor Piercing (AP) and High Explosive (HE). When either are equipped on a heavy cruiser (CA), especially on ones which have MGM+1 (main gun mount + 1), they form the core of a DPS unit. However, which is best is highly debated. 

This paper will be talking about what makes a good CA gun and when an AP or HE-type gun is appropriate in what context. It will also discuss unique exceptions. Do note that this paper will avoid discussing on an individual CA and their performance. It is strictly focused on the guns themselves unless it is heavily tied to a ship.

# Introduction to AP and HE (skip if well-versed)
AP guns focus on pure raw damage and focused on medium armor mods (modifiers). They are typically characterized by their slow speed but high alpha damage. Thus, even if they have only a slight better mod in heavy armor, the raw damage tends to allow them to push higher in the DPS points. They also are faster than HE guns with capability of piercing. Piercing in AL means the round will not dissipate on one enemy, but will travel until hitting another or evaporating. Enemies that receive the pierced round will be dealt full damage.

Ex. Two ships are lined up in a line. A round hits the first and hits the second. The round does 50 damage. Both ships are dealt 50 damage.

HE guns are typically faster with a stronger focus on light and a weaker raw damage than AP guns. They typically make up for this with a faster reload and a great affinity against light armor and mediocre in medium and heavy.

## AP v. HE
One of the greatest debates in AL is on what a CA should equip. There are many reasons why one might prefer AP and where one might prefer HE. Outside of where ship girls have a skill that enhances a shell type, there isn’t one single “best” round type. While yes one of these will perform the best in the majority, there definitely exists situations in which the other will work.

When observing what AP offers, one may be tempted to side with it. However, the context in which these offerings are employed can result in an opposite unexpected result. The high alpha damage and focus on medium armor is a tempting offer, but the majority of the enemies are light. The pierce sounds great, but, in likelihood, one will not achieve a high enough pierce to offset the light DPS disparity.
When observing HE, one might be tempted to rely on it solely for every content. The fast reload and better mods v. light offer a tempting choice. However, there exists situations in which its lacking in raw alpha damage leaves it not optimal.

Let’s use the 203mm Triple MLE from prototype research (PR) as our staple HE gun. We will refer to it as the MLE from now on until further notice. Conversely, we will use the 203mm Triple SKC from PR, referred to as the SKC until further notice. 

The raw stats for both guns are as follows:

| Name | Firepower | Damage | Coefficient | Volley Time (s) | Reload (s) | Light Armor Mod | Medium Armor Mod | Heavy Armor Mod|
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| MLE | 45 | 3x52 | 130% | 0.40 | 5.39 | 135% | 95% | 70% |
| SKC | 45 | 2x3x50 | 105% | 0.50 | 7.32 | 75% | 110% | 75% |

Then we calculate their damage/DPS to get:

| Name | Light Damage | Medium Damage | Heavy Damage | Light DPS | Medium DPS | Heavy DPS |
| --- | --- | --- | --- | --- | --- | --- |
| MLE | 396 | 279 | 205 | 65 | 45 | 33 |
| SKC | 342 | 502 | 342 | 42 | 61 | 42 |

In practice, both guns are fairly accurate. Thus we will not apply any modifiers.

Now we can observe distinctively what the roles of AP and HE are. HE guns focus on DPS. Notice that while they lack tremendously in terms of heavy damage compare to AP but translates to only 9 DPS points difference. Likewise AP guns focus on raw damage, noting despite having terrible light mods of 75%, they (SKC) are 54 damage points off of MLE.

This is where the crucial discussion lays ahead of us. We can tell that HE and AP are specialized. But which is better and when should we use one over the other? We will use a few criteria: fleet composition, enemy makeup on a map, and level advantages. 

We will employ two different types of CAs, not because of their skills, but because of their equipment. In Azur Lane, we have Torp-CA which uses torpedoes as their secondaries. We also have Gun-CAs which have DD (destroyer) guns as their secondaries. Both classes offer interesting views on what to equip in addition to fleet composition, enemy make, and level advantage. We will use Takao (Torp-CA) and Minneapolis (Gun-CA). 

### A disclaimer before we move forward:

> We will disregard either CAs' skills. This is due to not only the random nature of their skills, but also how it doesn't provide any crucial data. The only purpose said skills provide is faster clear times _for both cases_. Or they induce too much randomness or variables that it doesn't provide any meaningful analysis.

> We will also disregard barrage damage. While this leans in favor of the SKC as MLEs allow for faster barrage procs, we are focused only on gun performance. Thus, while I urge you to consider barrage proc rate as a factor, it will not be factored in considering each gun performance as a direct criterion.

# Main Analysis

## Preview

While utilizing the raw base stats of the MLE and SKC are solid, we require more practical approaches in analyzing damage. Which is where Takao and Minneapolis come in. We will use their stats and their own coefficients (differing multiplier to the gun's own coefficient) to get the adjusted numbers. Following that, we will also use their secondary damage/DPS. We will also ignore critical damage.

This paper will not spend time in providing the various formulas and numbers. Such values can be grabbed from Azur Lane's EN wiki. Combat page for formulas. Each ships' individual pages for their values. And the various equipment pages for torpedo/secondary gun/auxiliary information.

## Takao and Minneapolis

We will equip both CAs accordingly:
1. Takao
MLE or SKC + 533mm Quintuple Torpedoes + 40mm STAAG + Type 94 Oxygen Torpedo + Defensive Aux (no offensive bonuses)

2. Minneapolis
MLE or SKC + 138.6mm Single MLE + 40mm STAAG + 2 Defensive Auxes (no offensive bonuses)

Their damage values:

| Name | Light Damage | Medium Damage | Heavy Damage | Firing Cycle (s) |
| --- | --- | --- | --- | --- |
| Takao MLE | 1420 | 999 | 736 | 5.22 |
| Takao SKC | 1283 | 1883 | 1283 | 6.93 |
| Takao 533mm | 5350 | 6688 | 8695 | 22.45 |
| Minneapolis MLE | 2997 | 2109 | 1554 | 5.64 |
| Minneapolis SKC | 2710 | 3974 | 2710 | 7.46 |
| Minneapolis 138.6mm | 303 | 151 | 151 | 1.81 |

Firing cycle here denotes the total time it takes to fire. That is, it involves a CA's absolute cooldown, the gun's volley time, the reload modifier, and the gun's reload time.

## Initial HP Pool Clear Time Analysis for Solo CAs

We will assume a collective enemy health pool of 100,000. This pool will be split into light/medium/heavy armor proportionally with multiple cases. We assume that the CAs will focus on the light enemies first and then move to medium and finally to heavy. We will ignore any fleet composition for this initial analysis. Pierce or burn will also be ignored.

### Takao Clear Time
#### Warning: Massive Tables. Skip if wanting to look at the post analysis
| Light | Medium | Heavy | SKC (s) | MLE (s) |
|-------|--------|-------|-----|-----|
| 1     | 0      | 0     | 225 | 188 |
| 0.9   | 0.1    | 0     | 210 | 189 |
| 0.8   | 0.1    | 0.1   | 194 | 174 |
| 0.8   | 0.2    | 0     | 203 | 184 |
| 0.7   | 0.3    | 0     | 203 | 182 |
| 0.6   | 0.2    | 0.2   | 181 | 168 |
| 0.6   | 0.4    | 0     | 203 | 181 |
| 0.5   | 0      | 0.5   | 197 | 180 |
| 0.5   | 0.5    | 0     | 197 | 180 |
| 0.4   | 0.3    | 0.3   | 180 | 160 |
| 0.4   | 0.2    | 0.4   | 181 | 168 |
| 0.4   | 0.4    | 0.2   | 181 | 159 |
| 0.4   | 0.6    | 0     | 188 | 181 |
| 0.3   | 0.4    | 0.3   | 181 | 160 |
| 0.3   | 0.3    | 0.4   | 181 | 162 |
| 0.3   | 0.7    | 0     | 181 | 182 |
| 0.2   | 0.4    | 0.4   | 181 | 168 |
| 0.2   | 0.6    | 0.2   | 166 | 168 |
| 0.2   | 0.2    | 0.6   | 166 | 177 |
| 0.2   | 0.8    | 0     | 180 | 190 |
| 0.1   | 0.8    | 0.1   | 163 | 180 |
| 0.1   | 0.1    | 0.8   | 163 | 167 |
| 0.1   | 0.9    | 0     | 174 | 196 |
| 0     | 0.5    | 0.5   | 168 | 180 |
| 0     | 1      | 0     | 167 | 203 |
| 0     | 0      | 1     | 167 | 180 |

### Minneapolis Clear Time
#### Table warning
| Light | Medium | Heavy | SKC (s) | MLE (s) |
|-------|--------|-------|-----|-----|
| 1     | 0      | 0     | 187 | 147 |
| 0.9   | 0.1    | 0     | 180 | 144 |
| 0.8   | 0.1    | 0.1   | 187 | 158 |
| 0.8   | 0.2    | 0     | 180 | 153 |
| 0.7   | 0.3    | 0     | 172 | 159 |
| 0.6   | 0.2    | 0.2   | 186 | 178 |
| 0.6   | 0.4    | 0     | 172 | 170 |
| 0.5   | 0      | 0.5   | 201 | 204 |
| 0.5   | 0.5    | 0     | 165 | 176 |
| 0.4   | 0.3    | 0.3   | 187 | 200 |
| 0.4   | 0.2    | 0.4   | 194 | 205 |
| 0.4   | 0.4    | 0.2   | 179 | 195 |
| 0.4   | 0.6    | 0     | 173 | 187 |
| 0.3   | 0.4    | 0.3   | 180 | 205 |
| 0.3   | 0.3    | 0.4   | 187 | 211 |
| 0.3   | 0.7    | 0     | 165 | 193 |
| 0.2   | 0.4    | 0.4   | 187 | 222 |
| 0.2   | 0.6    | 0.2   | 180 | 212 |
| 0.2   | 0.2    | 0.6   | 202 | 233 |
| 0.2   | 0.8    | 0     | 165 | 203 |
| 0.1   | 0.8    | 0.1   | 164 | 212 |
| 0.1   | 0.1    | 0.8   | 209 | 251 |
| 0.1   | 0.9    | 0     | 157 | 206 |
| 0     | 0.5    | 0.5   | 186 | 244 |
| 0     | 1      | 0     | 157 | 215 |
| 0     | 0      | 1     | 223 | 277 |

### Analysis Based On Table Data

The Light/Medium/Heavy columns indicate how much of the HP pool is taken by said armor class. The SKC and MLE columns represent total clear time, measured in seconds.

In terms of what is better or not:

For Torp-CAs like Takao, they prefer HE guns heavily. It is only when there is a significant disparity in medium HP compared to other armor types that the SKC is the better option. That is, things begin to shift to the SKC's favor when there's 20% light, 60% medium, and 20% heavy. Any increase in medium or heavy and a decrease in light HP means the SKC is better.

For Gun-CAs like Minneapolis, they prefer SKCs more. To note, at 60% light, 40% medium, and 0% heavy, MLEs are superior. Any increase in light % and a decrease in medium % means MLEs are better. When medium armor takes a significant proportion, heavy armor at a lesser degree, and light at a minority, SKCs win.

### Further Comments

Before we move onto concerning ourselves with fleet compositions, we'll discuss our results in slighty more detail. Note that these are solo CAs. Gun-CAs don't change much in term of what is offered. But Torp-CAs here do heavily rely on their torpedoes for any enemies that aren't light. Thus particular caution should be paid attention to as the less amounts of torpedo hits there are, the more they will struggle against say medium enemies, thus favoring the SKC more than the MLE.
