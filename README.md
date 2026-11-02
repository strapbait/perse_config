# perse config
### [itemtest.cfg](https://github.com/strapbait/perse_config/blob/master/cfg/itemtest.cfg)
My customized config for the itemtest map which will automatically be run whenever you start a local server with `map itemtest`. 
- Spawns a puppet-bot on both red and blu team
- Changes the speed at which mediguns build and spend their uber charges
- Disables respawn timers
- Disables map timers by changing it to tournament mode

[itemtest_showcase.webm](https://github.com/user-attachments/assets/9f3261b7-159b-4bd9-bd33-63d643b76927)

---


### [jumphud_toggle](https://github.com/strapbait/perse_config/commit/ce500fa334f66bc0b8ef2cd1aed577b8bf024bbb)
- removes _most_ on-screen UI elements including player health, ammo, killstreaks, matchhud, killstreaks, and objectives
  - damage indicator circle has not been removed, yet
- <ins>notably does not remove crosshair, scoreboard, or chat</ins>
    - `cl_drawhud 0` does hide these elements, hence the purpose of this modification
- bindable toggle
- starts the game with the toggle disabled i.e. normal hud for normal gameplay
- minimal commit with only necessary changes to implement on your own hud
  - i'll even annotate the changeset if someone asks nicely

[jumphud_showcase.webm](https://github.com/user-attachments/assets/a98a90a0-cbfb-4ab8-bf96-8156b1debb11)

---

### misc. features
- clear and consistent architecture
  - [`cfg/overrides`](https://github.com/strapbait/perse_config/tree/master/cfg/overrides) is for [mastercomfig](https://github.com/mastercomfig/mastercomfig/tree/release/config/templates/overrides) game overrides _only_
  - personalized and customized config can be found in [`cfg/tweaks`](https://github.com/strapbait/perse_config/tree/master/cfg/tweaks)
- power user configs
  - [`cfg/tweaks/confilter.cfg`](https://github.com/strapbait/perse_config/blob/master/cfg/tweaks/confilter.cfg) filters out common console error messages
    - note that if you are running into strange errors, [disable confilter](https://github.com/strapbait/perse_config/blob/master/cfg/overrides/autoexec.cfg#L3) and execute the console command `developer n` where n > 0
  - [`cfg/tweaks/bootstrap.cfg`](https://github.com/strapbait/perse_config/blob/master/cfg/tweaks/bootstrap.cfg) applies very basic settings that I think most people should use such as fast weapon switch, auto-reload, no gibs
  - [`cfg/tweaks/tabgraph.cfg`](https://github.com/strapbait/perse_config/blob/master/cfg/tweaks/tabgraph.cfg) enables the more detailed `net_graph` when you press tab to show the scoreboard
  - [`cfg/tweaks/vital.cfg`](https://github.com/strapbait/perse_config/blob/master/cfg/tweaks/vital.cfg) allows you to print ascii art into console whenever `autoexec.cfg` is executed
    - use cfg.tf's [ascii art maker](https://cfg.tf/tools/asci/)
   
---
### kudos
[angie](https://github.com/palmtopangie/), for being a massive nerd and flexing on me with her [config](https://github.com/palmtopangie/palmtopconfig)

[grape juice](https://tempusplaza.com/players/14587), for guiding my jumping journey, and [hood](https://rgl.gg/Public/PlayerProfile?p=76561199086159354&r=24), for starting it

[espi](https://github.com/espimarisa), for submissive puppyboy delivery

[mastercoms](https://github.com/mastercoms), for [mastercomfig](https://comfig.app/), an indispensable customization framework with _excellent_ documentation






