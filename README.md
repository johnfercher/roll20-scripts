# roll20-scripts

## Initiative
source: https://wiki.roll20.net/Useful_Macros

```
/em @{selected|token_name} rolls a [[1d20+@{selected|initiative_bonus}&{tracker}]] for initiative!
```

## Skill Check
source: https://app.roll20.net/forum/post/5591526/5e-ogl-universal-skill-check-macro-updated-for-v2-dot-0

created by: Craig https://app.roll20.net/users/2096187/craig

edited by: Kyle G. https://app.roll20.net/users/1419660/kyle-g

```
@{selected|wtype}&{template:simple} @{selected|rtype}?{Stat
|Strength,+[[@{selected|strength_mod}]][STR] ]]}} {{rname=^{strength-u}}} {{mod=[[ [[@{selected|strength_mod}]][STR] ]]}} {{r1=[[@{selected|d20}+[[@{selected|strength_mod}]][STR] ]]
|Dexterity,+[[@{selected|dexterity_mod}]][DEX] ]]}} {{rname=^{dexterity-u}}} {{mod=[[ [[@{selected|dexterity_mod}]][DEX] ]]}} {{r1=[[@{selected|d20}+[[@{selected|dexterity_mod}]][DEX] ]]
|Constitution,+[[@{selected|constitution_mod}]][CON] ]]}} {{rname=^{constitution-u}}} {{mod=[[ [[@{selected|constitution_mod}]][CON] ]]}} {{r1=[[@{selected|d20}+[[@{selected|constitution_mod}]][CON] ]]
|Intelligence,+[[@{selected|intelligence_mod}]][INT] ]]}} {{rname=^{intelligence-u}}} {{mod=[[ [[@{selected|intelligence_mod}]][INT] ]]}} {{r1=[[@{selected|d20}+[[@{selected|intelligence_mod}]][INT] ]]
|Wisdom,+[[@{selected|wisdom_mod}]][WIS] ]]}} {{rname=^{wisdom-u}}} {{mod=[[ [[@{selected|wisdom_mod}]][WIS] ]]}} {{r1=[[@{selected|d20}+[[@{selected|wisdom_mod}]][WIS] ]]
|Charisma,+[[@{selected|charisma_mod}]][CHA] ]]}} {{rname=^{charisma-u}}} {{mod=[[ [[@{selected|charisma_mod}]][CHA] ]]}} {{r1=[[@{selected|d20}+[[@{selected|charisma_mod}]][CHA] ]]
}}} {{global=@{selected|global_skill_mod}}} @{selected|charname_output}
```

## Ability Check
source: https://app.roll20.net/forum/post/5591522/5e-ogl-universal-ability-check-macro-updated-for-v2-dot-0

created by: Craig https://app.roll20.net/users/2096187/craig

edited by: Kyle G. https://app.roll20.net/users/1419660/kyle-g

```
@{selected|wtype}&{template:simple} @{selected|rtype}?{Stat
|Strength,+[[@{selected|strength_mod}]][STR] ]]&#125;&#125; {{rname=^{strength-u&#125;&#125;&#125; {{mod=[[ [[@{selected|strength_mod}]][STR] ]]&#125;&#125; {{r1=[[@{selected|d20}+[[@{selected|strength_mod}]][STR] ]]
|Dexterity,+[[@{selected|dexterity_mod}]][DEX] ]]&#125;&#125; {{rname=^{dexterity-u&#125;&#125;&#125; {{mod=[[ [[@{selected|dexterity_mod}]][DEX] ]]&#125;&#125; {{r1=[[@{selected|d20}+[[@{selected|dexterity_mod}]][DEX] ]]
|Constitution,+[[@{selected|constitution_mod}]][CON] ]]&#125;&#125; {{rname=^{constitution-u&#125;&#125;&#125; {{mod=[[ [[@{selected|constitution_mod}]][CON] ]]&#125;&#125; {{r1=[[@{selected|d20}+[[@{selected|constitution_mod}]][CON] ]]
|Intelligence,+[[@{selected|intelligence_mod}]][INT] ]]&#125;&#125; {{rname=^{intelligence-u&#125;&#125;&#125; {{mod=[[ [[@{selected|intelligence_mod}]][INT] ]]&#125;&#125; {{r1=[[@{selected|d20}+[[@{selected|intelligence_mod}]][INT] ]]
|Wisdom,+[[@{selected|wisdom_mod}]][WIS] ]]&#125;&#125; {{rname=^{wisdom-u&#125;&#125;&#125; {{mod=[[ [[@{selected|wisdom_mod}]][WIS] ]]&#125;&#125; {{r1=[[@{selected|d20}+[[@{selected|wisdom_mod}]][WIS] ]]
|Charisma,+[[@{selected|charisma_mod}]][CHA] ]]&#125;&#125; {{rname=^{charisma-u&#125;&#125;&#125; {{mod=[[ [[@{selected|charisma_mod}]][CHA] ]]&#125;&#125; {{r1=[[@{selected|d20}+[[@{selected|charisma_mod}]][CHA] ]]
}}} {{global=@{selected|global_skill_mod}}} @{selected|charname_output}
```

## Saving Throw
source: https://app.roll20.net/forum/post/5591512/5e-ogl-universal-saving-throw-macro-updated-for-v2-dot-0

created by: Craig https://app.roll20.net/users/2096187/craig

edited by: Kyle G. https://app.roll20.net/users/1419660/kyle-g

```
@{selected|wtype}&{template:simple} @{selected|rtype}?{Save
|Strength,+[[(@{selected|strength_save_bonus}@{selected|pbd_safe}*(1-ceil((@{selected|npc})*0.00001)))+(@{selected|npc_str_save}*@{selected|npc})]][STR SAVE] ]]&#125;&#125; {{rname=^{strength-save-u&#125;&#125;&#125; {{mod=[[ [[(@{selected|strength_save_bonus}@{selected|pbd_safe}*(1-ceil((@{selected|npc})*0.00001)))+(@{selected|npc_str_save}*@{selected|npc})]][STR SAVE] ]]&#125;&#125; {{r1=[[@{selected|d20}+[[(@{selected|strength_save_bonus}@{selected|pbd_safe}*(1-ceil((@{selected|npc})*0.00001)))+(@{selected|npc_str_save}*@{selected|npc})]][STR SAVE] ]]
|Dexterity,+[[(@{selected|dexterity_save_bonus}@{selected|pbd_safe}*(1-ceil((@{selected|npc})*0.00001)))+(@{selected|npc_dex_save}*@{selected|npc})]][DEX SAVE] ]]&#125;&#125; {{rname=^{dexterity-save-u&#125;&#125;&#125; {{mod=[[ [[(@{selected|dexterity_save_bonus}@{selected|pbd_safe}*(1-ceil((@{selected|npc})*0.00001)))+(@{selected|npc_dex_save}*@{selected|npc})]][DEX SAVE] ]]&#125;&#125; {{r1=[[@{selected|d20}+[[(@{selected|dexterity_save_bonus}@{selected|pbd_safe}*(1-ceil((@{selected|npc})*0.00001)))+(@{selected|npc_dex_save}*@{selected|npc})]][DEX SAVE] ]]
|Constitution,+[[(@{selected|constitution_save_bonus}@{selected|pbd_safe}*(1-ceil((@{selected|npc})*0.00001)))+(@{selected|npc_con_save}*@{selected|npc})]][CON SAVE] ]]&#125;&#125; {{rname=^{constitution-save-u&#125;&#125;&#125; {{mod=[[ [[(@{selected|constitution_save_bonus}@{selected|pbd_safe}*(1-ceil((@{selected|npc})*0.00001)))+(@{selected|npc_con_save}*@{selected|npc})]][CON SAVE] ]]&#125;&#125; {{r1=[[@{selected|d20}+[[(@{selected|constitution_save_bonus}@{selected|pbd_safe}*(1-ceil((@{selected|npc})*0.00001)))+(@{selected|npc_con_save}*@{selected|npc})]][CON SAVE] ]]
|Intelligence,+[[(@{selected|intelligence_save_bonus}@{selected|pbd_safe}*(1-ceil((@{selected|npc})*0.00001)))+(@{selected|npc_int_save}*@{selected|npc})]][INT SAVE] ]]&#125;&#125; {{rname=^{intelligence-save-u&#125;&#125;&#125; {{mod=[[ [[(@{selected|intelligence_save_bonus}@{selected|pbd_safe}*(1-ceil((@{selected|npc})*0.00001)))+(@{selected|npc_int_save}*@{selected|npc})]][INT SAVE] ]]&#125;&#125; {{r1=[[@{selected|d20}+[[(@{selected|intelligence_save_bonus}@{selected|pbd_safe}*(1-ceil((@{selected|npc})*0.00001)))+(@{selected|npc_int_save}*@{selected|npc})]][INT SAVE] ]]
|Wisdom,+[[(@{selected|wisdom_save_bonus}@{selected|pbd_safe}*(1-ceil((@{selected|npc})*0.00001)))+(@{selected|npc_wis_save}*@{selected|npc})]][WIS SAVE] ]]&#125;&#125; {{rname=^{wisdom-save-u&#125;&#125;&#125; {{mod=[[ [[(@{selected|wisdom_save_bonus}@{selected|pbd_safe}*(1-ceil((@{selected|npc})*0.00001)))+(@{selected|npc_wis_save}*@{selected|npc})]][WIS SAVE] ]]&#125;&#125; {{r1=[[@{selected|d20}+[[(@{selected|wisdom_save_bonus}@{selected|pbd_safe}*(1-ceil((@{selected|npc})*0.00001)))+(@{selected|npc_wis_save}*@{selected|npc})]][WIS SAVE] ]]
|Charisma,+[[(@{selected|charisma_save_bonus}@{selected|pbd_safe}*(1-ceil((@{selected|npc})*0.00001)))+(@{selected|npc_cha_save}*@{selected|npc})]][CHA SAVE] ]]&#125;&#125; {{rname=^{charisma-save-u&#125;&#125;&#125; {{mod=[[ [[(@{selected|charisma_save_bonus}@{selected|pbd_safe}*(1-ceil((@{selected|npc})*0.00001)))+(@{selected|npc_cha_save}*@{selected|npc})]][CHA SAVE] ]]&#125;&#125; {{r1=[[@{selected|d20}+[[(@{selected|charisma_save_bonus}@{selected|pbd_safe}*(1-ceil((@{selected|npc})*0.00001)))+(@{selected|npc_cha_save}*@{selected|npc})]][CHA SAVE] ]]
}}} {{global=@{selected|global_save_mod}}} @{selected|charname_output}
```