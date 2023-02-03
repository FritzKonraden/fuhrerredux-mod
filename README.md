![Maintenance](https://img.shields.io/badge/Maintained-Yes-green)
![GitHub last commit](https://img.shields.io/github/last-commit/dax0102/fuhrerredux-mod)
![GitHub contributors](https://img.shields.io/github/contributors/dax0102/fuhrerredux-mod)
![Steam Views](https://img.shields.io/steam/views/2419457479?label=Steam%20Workshop%20Views)
![GitHub repo file count](https://img.shields.io/github/directory-file-count/dax0102/fuhrerredux-mod)
![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/dax0102/fuhrerredux-mod)
![GitHub pull requests](https://img.shields.io/github/issues-pr/dax0102/fuhrerredux-mod)
![GitHub Repo stars](https://img.shields.io/github/stars/dax0102/fuhrerredux-mod?style=social)
![GitHub forks](https://img.shields.io/github/forks/dax0102/fuhrerredux-mod?style=social)
# Führerredux Mod
The required files for the mod Fuhrerredux for the Paradox game Hearts of Iron IV.
## How to install the github version?
1)Create a new mod through the Paradox Launcher                   
2)Download the zip folder using the Green Button              
3)Unzip the zip folder              
4)Take all of its contents and put them in the folder of the mod you created previously           
5)When prompted to replace files, say yes
6)In the mod file, there should be a .mod file with the name of the mod you created. Edit this file to include the following in the end:
<details><summary>CLICK ME</summary>
<p>

```lua
replace_path="common/abilities"
replace_path="common/ai_areas"
replace_path="common/ai_equipment"
replace_path="common/ai_focuses"
replace_path="common/ai_strategy"
replace_path="common/ai_strategy_plans"
replace_path="common/ai_templates"
replace_path="common/autonomous_states"
replace_path="common/bookmarks"
replace_path="common/bop"
replace_path="common/characters"
replace_path="common/continuous_focus"
replace_path="common/countries"
replace_path="common/country_leader"
replace_path="common/country_tag_aliases"
replace_path="common/country_tags"
replace_path="common/decisions"
replace_path="common/decisions/categories"
replace_path="common/difficulty_settings"
replace_path="common/dynamic_modifiers"
replace_path="common/game_rules"
replace_path="common/idea_tags"
replace_path="common/ideas"
replace_path="common/ideologies"
replace_path="common/modifiers"
replace_path="common/modifier_definitions"
replace_path="common/names"
replace_path="common/national_focus"
replace_path="common/on_actions"
replace_path="common/operations"
replace_path="common/opinion_modifiers"
replace_path="common/peace_conference/ai_peace"
replace_path="common/peace_conference/categories"
replace_path="common/peace_conference/cost_modifiers"
replace_path="common/scripted_diplomatic_actions"
replace_path="common/scripted_effects"
replace_path="common/scripted_guis"
replace_path="common/scripted_localisation"
replace_path="common/scripted_triggers"
replace_path="common/state_category"
replace_path="common/technologies"
replace_path="common/technology_sharing"
replace_path="common/technology_tags"
replace_path="common/units/codenames_operatives"
replace_path="common/units/names"
replace_path="common/units/names_divisions"
replace_path="common/units/names_ships"
replace_path="events"
replace_path="gfx/flags"
replace_path="gfx/loadingscreens"
replace_path="history/countries"
replace_path="history/general"
replace_path="history/states"
replace_path="history/units"
replace_path="map/supplyareas"
replace_path="map/strategicregions"
replace_path="portraits"
replace_path="tests"
```
</p>
</details>

Note: you need to **include them**, so you don't need to delete anything else.
## How to become a developer?
To become a developer, you need to join our Discord Server and do the application on the #recruitment channel! Then dm @dax#0254, so he can review and accept your
application!
# 
Note: You can always get rejected, it is not guaranteed that you will get accepted.
## But where's the link?
Here is the link:
https://discord.gg/dVT7bHNVgY
## What else is there to know?
We appreciate any help we can get, if you have any ideas for a specific country or path or any form of icons/flags/portraits/localisation, that you fell we could use, consider joining our discord and telling us about it!
We regularly post teasers on our discord server about new content!
# TODO LIST
## Work In Progress
- Greece
- Japan
- Serbia
- Finland (new focus branch)
- Hungary
- Brazil
- Bulgaria
## Planned
- Ukraine
- Latvia
- Dutch Royalists
## Released
- Belarus

#### if your read this far, congrats!
##### ENJOY A TRIANGLE
```stl
solid bulgaria_flag
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 0.0 1.0
      vertex 0.0 1.0 0.0
    endloop
  endfacet
  facet normal 0.577 0.577 0.577
    outer loop
      vertex 1.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
endsolid
```
