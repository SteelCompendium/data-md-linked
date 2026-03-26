---
action_type: Main action
class: tactician
cost: 9 Focus
cost_amount: 9
cost_resource: Focus
distance: Melee 1
feature_type: ability
file_basename: To Me Squad
file_dpath: Abilities/Tactician/6th-Level Features
flavor: You lead your allies in a charge.
item_id: to-me-squad-9-focus
item_index: '06'
item_name: To Me Squad! (9 Focus)
keywords:
  - '[Charge](scc:mcdm.heroes.v1:common-ability.main-action:charge)'
  - Melee
  - Strike
  - Weapon
level: 6
scc:
  - mcdm.heroes.v1:feature.ability.tactician.6th-level-feature:to-me-squad-9-focus
scdc:
  - 1.1.1:11.2.4.3:06
source: mcdm.heroes.v1
subclass: Vanguard
target: One creature
type: feature/ability/tactician/6th-level-feature
---

###### To Me Squad! (9 Focus)

*You lead your allies in a charge.*

| **[Charge](REL_PATH_PREFIXRules/Abilities/Common/Main%20Actions/ChargeREL_PATH_SUFFIX), Melee, Strike, Weapon** |     **Main action** |
| --------------------------------------------------------------------------------------------------------------- | ------------------: |
| **📏 Melee 1**                                                                                                  | **🎯 One creature** |

**Power Roll + Might:**

- **≤11:** 6 + M damage; one ally within 10 squares can use the [Charge](REL_PATH_PREFIXRules/Abilities/Common/Main%20Actions/ChargeREL_PATH_SUFFIX) main action as a free triggered action, and can use a melee strike signature ability instead of a [free strike](REL_PATH_PREFIXRules/Abilities/Common/Main%20Actions/Free%20StrikeREL_PATH_SUFFIX) for the [charge](REL_PATH_PREFIXRules/Abilities/Common/Main%20Actions/ChargeREL_PATH_SUFFIX)
- **12-16:** 9 + M damage; one ally within 10 squares can use the [Charge](REL_PATH_PREFIXRules/Abilities/Common/Main%20Actions/ChargeREL_PATH_SUFFIX) main action as a free triggered action, and can use a melee strike signature ability that gains an edge instead of a [free strike](REL_PATH_PREFIXRules/Abilities/Common/Main%20Actions/Free%20StrikeREL_PATH_SUFFIX) for the [charge](REL_PATH_PREFIXRules/Abilities/Common/Main%20Actions/ChargeREL_PATH_SUFFIX)
- **17+:** 13 + M damage; two allies within 10 squares can use the [Charge](REL_PATH_PREFIXRules/Abilities/Common/Main%20Actions/ChargeREL_PATH_SUFFIX) main action as a free triggered action, and can each use a melee strike signature ability that gains an edge instead of a [free strike](REL_PATH_PREFIXRules/Abilities/Common/Main%20Actions/Free%20StrikeREL_PATH_SUFFIX) for the [charge](REL_PATH_PREFIXRules/Abilities/Common/Main%20Actions/ChargeREL_PATH_SUFFIX)

**Effect:** If the target is hit with two or more strikes as part of this ability and they have R < STRONG, they are [dazed](REL_PATH_PREFIXRules/Conditions/DazedREL_PATH_SUFFIX) (save ends). If the target is reduced to 0 Stamina before one or both allies has made their strike, the ally or allies can pick a different target.
