---
action_type: feature
class: tactician
feature_type: trait
file_basename: 6th Level Vanguard Abilities
file_dpath: Tactician/6th-Level Features/6th-Level Doctrine Ability
item_id: 6th-level-vanguard-abilities
item_index: '01'
item_name: 6th-Level Vanguard Abilities
level: 6
scc:
  - mcdm.heroes.v1:subfeature.trait.tactician.6th-level-feature:6th-level-vanguard-abilities
scdc:
  - 1.1.1:12.1.4.5:01
source: mcdm.heroes.v1
type: subfeature/trait/tactician/6th-level-feature
---

##### 6th-Level Vanguard Abilities

Choose one of the following abilities.

<!-- -->
> ###### Instant Retaliation (9 Focus)
>
> *You parry with almost supernatural speed.*
>
> | **Melee, Weapon** | **Free triggered** |
> | ----------------- | -----------------: |
> | **📏 Melee 1**    |    **🎯 One ally** |
>
> **Trigger:** A creature deals damage to the target.
>
> **Effect:** The target takes half the damage. You then make a power roll against the triggering creature.
>
> **Power Roll + Might:**
>
> - **≤11:** A < WEAK, [dazed](REL_PATH_PREFIXRules/Conditions/DazedREL_PATH_SUFFIX) (save ends)
> - **12-16:** A < AVERAGE, [dazed](REL_PATH_PREFIXRules/Conditions/DazedREL_PATH_SUFFIX) (save ends)
> - **17+:** A < STRONG, [dazed](REL_PATH_PREFIXRules/Conditions/DazedREL_PATH_SUFFIX) (save ends)

<!-- -->
> ###### To Me Squad! (9 Focus)
>
> *You lead your allies in a charge.*
>
> | **[Charge](REL_PATH_PREFIXRules/Abilities/Common/Main%20Actions/ChargeREL_PATH_SUFFIX), Melee, Strike, Weapon** |     **Main action** |
> | --------------------------------------------------------------------------------------------------------------- | ------------------: |
> | **📏 Melee 1**                                                                                                  | **🎯 One creature** |
>
> **Power Roll + Might:**
>
> - **≤11:** 6 + M damage; one ally within 10 squares can use the [Charge](REL_PATH_PREFIXRules/Abilities/Common/Main%20Actions/ChargeREL_PATH_SUFFIX) main action as a free triggered action, and can use a melee strike signature ability instead of a [free strike](REL_PATH_PREFIXRules/Abilities/Common/Main%20Actions/Free%20StrikeREL_PATH_SUFFIX) for the [charge](REL_PATH_PREFIXRules/Abilities/Common/Main%20Actions/ChargeREL_PATH_SUFFIX)
> - **12-16:** 9 + M damage; one ally within 10 squares can use the [Charge](REL_PATH_PREFIXRules/Abilities/Common/Main%20Actions/ChargeREL_PATH_SUFFIX) main action as a free triggered action, and can use a melee strike signature ability that gains an edge instead of a [free strike](REL_PATH_PREFIXRules/Abilities/Common/Main%20Actions/Free%20StrikeREL_PATH_SUFFIX) for the [charge](REL_PATH_PREFIXRules/Abilities/Common/Main%20Actions/ChargeREL_PATH_SUFFIX)
> - **17+:** 13 + M damage; two allies within 10 squares can use the [Charge](REL_PATH_PREFIXRules/Abilities/Common/Main%20Actions/ChargeREL_PATH_SUFFIX) main action as a free triggered action, and can each use a melee strike signature ability that gains an edge instead of a [free strike](REL_PATH_PREFIXRules/Abilities/Common/Main%20Actions/Free%20StrikeREL_PATH_SUFFIX) for the [charge](REL_PATH_PREFIXRules/Abilities/Common/Main%20Actions/ChargeREL_PATH_SUFFIX)
>
> **Effect:** If the target is hit with two or more strikes as part of this ability and they have R < STRONG, they are [dazed](REL_PATH_PREFIXRules/Conditions/DazedREL_PATH_SUFFIX) (save ends). If the target is reduced to 0 Stamina before one or both allies has made their strike, the ally or allies can pick a different target.
