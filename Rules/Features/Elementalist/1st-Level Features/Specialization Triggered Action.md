---
action_type: feature
class: elementalist
feature_type: trait
file_basename: Specialization Triggered Action
file_dpath: Elementalist/1st-Level Features
item_id: specialization-triggered-action
item_index: '07'
item_name: Specialization Triggered Action
level: 1
scc:
  - mcdm.heroes.v1:feature.trait.elementalist.1st-level-feature:specialization-triggered-action
scdc:
  - 1.1.1:11.1.9.1:07
source: mcdm.heroes.v1
type: feature/trait/elementalist/1st-level-feature
---

#### Specialization Triggered Action

Your [elemental specialization](REL_PATH_PREFIXRules/Elementalist/1st-Level%20Features/Elemental%20SpecializationREL_PATH_SUFFIX) grants you a triggered action, as shown on the [Specialization Triggered Actions](REL_PATH_PREFIXRules/Elementalist/1st-Level%20Features/Specialization%20Triggered%20ActionREL_PATH_SUFFIX) table.

###### Elemental Specialization Triggered Actions Table

| Specialization | Triggered Action                                                                                                                             |
| -------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| Earth          | [Skin Like Castle Walls](REL_PATH_PREFIXRules/Abilities/Elementalist/1st-Level%20Features/Skin%20Like%20Castle%20WallsREL_PATH_SUFFIX)       |
| Fire           | [Explosive Assistance](REL_PATH_PREFIXRules/Abilities/Elementalist/1st-Level%20Features/Explosive%20AssistanceREL_PATH_SUFFIX)               |
| Green          | [Breath of Dawn Remembered](REL_PATH_PREFIXRules/Abilities/Elementalist/1st-Level%20Features/Breath%20of%20Dawn%20RememberedREL_PATH_SUFFIX) |
| Void           | [Subtle Relocation](REL_PATH_PREFIXRules/Abilities/Elementalist/1st-Level%20Features/Subtle%20RelocationREL_PATH_SUFFIX)                     |

<!-- -->
> ###### Breath of Dawn Remembered
>
> *The power you channel grants the ability to get back in the fight.*
>
> | **Green, Magic, Ranged** |           **Triggered** |
> | ------------------------ | ----------------------: |
> | **📏 Ranged 10**         | **🎯 Self or one ally** |
>
> **Trigger:** The target starts their turn or takes damage.
>
> **Effect:** The target can spend a Recovery.
>
> **Spend 1+ Essence:** The target can spend an additional Recovery for each essence spent.

<!-- -->
> ###### Explosive Assistance
>
> *You add a little magic to an ally's aggression at just the right time.*
>
> | **Fire, Magic, Ranged** |           **Triggered** |
> | ----------------------- | ----------------------: |
> | **📏 Ranged 10**        | **🎯 Self or one ally** |
>
> **Trigger:** The target force moves a creature or object.
>
> **Effect:** The forced movement distance gains a bonus equal to your Reason score.
>
> **Spend 1 Essence:** The forced movement distance gains a bonus equal to twice your Reason score instead.

<!-- -->
> ###### Skin Like Castle Walls
>
> *You cover yourself or an ally in protective stone.*
>
> | **Earth, Magic, Ranged** |           **Triggered** |
> | ------------------------ | ----------------------: |
> | **📏 Ranged 10**         | **🎯 Self or one ally** |
>
> **Trigger:** The target takes damage.
>
> **Effect:** The target takes half the damage.
>
> **Spend 1 Essence:** If the damage has any potency effects associated with it, the potency is reduced by 1 for the target.

<!-- -->
> ###### Subtle Relocation
>
> *You call on the void to swallow and spit out an ally.*
>
> | **Magic, Ranged, Void** |           **Triggered** |
> | ----------------------- | ----------------------: |
> | **📏 Ranged 10**        | **🎯 Self or one ally** |
>
> **Trigger:** The target starts their turn, moves, or is force moved.
>
> **Effect:** You [teleport](REL_PATH_PREFIXRules/Movement/TeleportREL_PATH_SUFFIX) the target up to a number of squares equal to your Reason score. If the target moves to trigger this ability, you can [teleport](REL_PATH_PREFIXRules/Movement/TeleportREL_PATH_SUFFIX) them at any point during the move.
>
> **Spend 1 Essence:** You [teleport](REL_PATH_PREFIXRules/Movement/TeleportREL_PATH_SUFFIX) the target up to a number of squares equal to twice your Reason score instead.
