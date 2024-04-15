# Voices of the Void recreation for ghostreferencing 
Some stuff can take considerable amount of time to remap, especially if assets depend on each other. To save your time, and possibly open you to more game mechanics you didn't know about, this project will be populated from time to time with new entries.</li></li>
To use them, drag and drop Content folder to your mod project base, usually named VotV. it should already contain Content folder and they should merge, and new assets will appear in your editor.

## Warnings

Main point of this project is to properly replicate structs, since they are the hardest to map due name mangling. As of now, only **struct_settings** remains incomplete, though as I would love to guarentee guarantee smooth operation on others, unfortunately I can't. Errors *should be* happening, though I can't completely exclude them. At least project manages to build with them. 
<br/><br/>I await for your reports, in case something goes wrong while utilizing one of those structures.

## File tree [WIP]

<details>
 <summary>main</summary>
<details><summary>datatables</summary>
  <ul><li>list_props</li></ul>
  </details>
 <details>
 <summary>enums</summary>
  <ul>
  <li>enum_action</li>
  <li>enum_char</li>
  <li>enum_difficulty</li>
  <li>enum_emailChars</li>
  <li>enum_freq</li>
  <li>enum_gamemode</li>
  <li>enum_interactionActions</li>
  <li>enum_kerfurCommand</li>
  <li>enum_kerfurDripType</li>
  <li>enum_notifyType</li>
  <li>enum_objectType</li>
  <li>enum_quality</li>
  <li>enum_shopCats</li>
  <li>enum_signalResponse</li>
  <li>enum_spawnmenuCats</li>
  <li>enum_tvStatus</li>
   </ul>
 </details>
 <details>
 <summary>interfaces</summary>
  <li>int_coms</li>
  <li>int_objects</li>
  <li>int_player</li>
  <li>int_save1</li>
  <li>int_ttrigger</li>
 </details>
  <details>
 <summary>structs (Everything but STRUCT_SETTINGS SHOULD BE safe to use)</summary>
  <li>enum_playlist</li>
  <li>struct_achievement</li>
  <li>struct_byteimage</li>
  <li>struct_characterEmailProfile</li>
  <li>struct_characterResponse_v21</li>
  <li>struct_crafting</li>
  <li>struct_dangerProp</li>
  <li>struct_email</li>
  <li>struct_equipment</li>
  <li>struct_equipmentWear</li>
  <li>struct_event</li>
  <li>struct_farmPlant</li>
  <li>struct_food1</li>
  <li>struct_help</li>
  <li>struct_ignalEmailResponse</li>
  <li>struct_kerfurDrip</li>
  <li>struct_keybind</li>
  <li>struct_loan</li>
  <li>struct_lootWeighted</li>
  <li>struct_mBool</li>
  <li>struct_mClass</li>
  <li>struct_mFloat</li>
  <li>struct_mInt</li>
  <li>struct_mString</li>
  <li>struct_mVector</li>
  <li>struct_physSound</li>
  <li>struct_prop</li>
  <li>struct_propDynamic</li>
  <li>struct_propObject</li>
  <li>struct_save</li>
  <li>struct_scientistSpecialResponse</li>
  <li>struct_settings</li>
  <li>struct_shroom</li>
  <li>struct_signal_data2</li>
  <li>struct_signal_spawn</li>
  <li>struct_signalDataDynamic</li>
  <li>struct_signalEmailResponse</li>
  <li>struct_sound</li>
  <li>struct_spaceObject</li>
  <li>struct_store</li>
  <li>struct_triggerSave</li>
  <li>struct_tv</li>
  <li>struct_weapon</li>
  <li>struct_weightedName
 </details>
<li>GameInst</li>
<li>lib</li>
<li>mainGamemode</li>
<li>mainPlayer</li>
<li>physicsImpact</li>
<li>save_main</li>
<li>saveSlot</li>
<li>struct_picturesDim</li>
</details>
<details><summary>materials</summary>
 <details><summary>phys</summary>
<li>bag</li>
<li>bag_flammable</li>
<li>ball</li>
<li>balloon</li>
<li>barrel</li>
<li>batt</li>
<li>body</li>
<li>can</li>
<li>concrete</li>
<li>concrete1</li>
<li>concrete_float</li>
<li>concrete_massive</li>
<li>concrete_massive_float</li>
<li>concrete_shroom</li>
<li>cup</li>
<li>dirt</li>
<li>drive</li>
<li>flesh</li>
<li>food</li>
<li>glass</li>
<li>gold</li>
<li>gold_s</li>
<li>grass</li>
<li>grate</li>
<li>gravel</li>
<li>kerfusWheel</li>
<li>metal</li>
<li>metalHeavy</li>
<li>metalPipe</li>
<li>metalPipe1</li>
<li>paper</li>
<li>plastic</li>
<li>rubber</li>
<li>sball</li>
<li>silent</li>
<li>slide</li>
<li>vehicle</li>
<li>wood
 </details>
</details>
<details><summary>objects</summary>
 [WIP] 80 entries total
</details>
<details><summary>umg</summary>
 <details><summary>UI</summary>
  <li>umg_menu</li>
  <li>umg_quicksave</li>
  <li>umg_serverMinigame
 </details>
<li>umg_clipboard</li>
<li>umg_console</li>
<li>umg_coords</li>
<li>umg_deathscreen</li>
<li>umg_decoder</li>
<li>umg_equipmentSlot</li>
<li>umg_hints</li>
<li>umg_hovertextNametag</li>
<li>umg_inventory</li>
<li>umg_inventorySlot</li>
<li>umg_laptop</li>
<li>umg_minimap</li>
<li>umg_onlineRadio</li>
<li>umg_paperDraw</li>
<li>umg_passlock</li>
<li>umg_printer</li>
<li>umg_propInv</li>
<li>umg_propInvInvSlot</li>
<li>umg_propInvSlor</li>
<li>umg_radarScreen</li>
<li>umg_reactor</li>
<li>umg_signalDownload</li>
<li>umg_signalPlay</li>
<li>umg_tvOffline</li>
<li>umg_UI</li>
</details>
<br/>
<details><summary>Temporary and more up-to-date file tree dump from cmd</summary>
├───main<br/>
│   │   GameInst<br/>
│   │   lib<br/>
│   │   mainGamemode<br/>
│   │   mainPlayer<br/>
│   │   saveSlot<br/>
│   │   save_main<br/>
│   │   struct_picturesDim<br/>
│   │<br/>
│   ├───datatables<br/>
│   │       list_achievements<br/>
│   │       list_advancements<br/>
│   │       list_breakableProps<br/>
│   │       list_charactersSignalResponse<br/>
│   │       list_consoleText<br/>
│   │       list_craftRecipes<br/>
│   │       list_emailCharacters<br/>
│   │       list_equipment<br/>
│   │       list_events<br/>
│   │       list_farmPlants<br/>
│   │       list_food<br/>
│   │       list_help<br/>
│   │       list_kerfurDrip<br/>
│   │       list_keybinds<br/>
│   │       list_objects<br/>
│   │       list_patreonText<br/>
│   │       list_physSound<br/>
│   │       list_props<br/>
│   │       list_shrooms<br/>
│   │       list_signalEmailResponse<br/>
│   │       list_signals<br/>
│   │       list_specialResponses<br/>
│   │       list_store<br/>
│   │       list_subtitles<br/>
│   │       list_weapons<br/>
│   │       list_weightedObject<br/>
│   │<br/>
│   ├───enums<br/>
│   │       enum_action<br/>
│   │       enum_char<br/>
│   │       enum_difficulty<br/>
│   │       enum_emailChars<br/>
│   │       enum_freq<br/>
│   │       enum_gamemode<br/>
│   │       enum_interactionActions<br/>
│   │       enum_kerfurCommand<br/>
│   │       enum_kerfurDripType<br/>
│   │       enum_notifyType<br/>
│   │       enum_objectType<br/>
│   │       enum_quality<br/>
│   │       enum_shopCats<br/>
│   │       enum_signalResponse<br/>
│   │       enum_spawnmenuCats<br/>
│   │       enum_tvStatus<br/>
│   │<br/>
│   ├───interfaces<br/>
│   │       int_coms<br/>
│   │       int_objects<br/>
│   │       int_player<br/>
│   │       int_save1<br/>
│   │       int_ttrigger<br/>
│   │<br/>
│   └───structs<br/>
│           enum_playlist<br/>
│           struct_achievement<br/>
│           struct_byteimage<br/>
│           struct_characterEmailProfile<br/>
│           struct_characterResponse_v21<br/>
│           struct_crafting<br/>
│           struct_customMesh<br/>
│           struct_dangerProp<br/>
│           struct_email<br/>
│           struct_equipment<br/>
│           struct_equipmentWear<br/>
│           struct_event<br/>
│           struct_farmPlant<br/>
│           struct_food1<br/>
│           struct_help<br/>
│           struct_ignalEmailResponse<br/>
│           struct_kerfurDrip<br/>
│           struct_keybind<br/>
│           struct_loan<br/>
│           struct_lootWeighted<br/>
│           struct_mBool<br/>
│           struct_mClass<br/>
│           struct_mFloat<br/>
│           struct_mInt<br/>
│           struct_mObject<br/>
│           struct_mString<br/>
│           struct_mVector<br/>
│           struct_object<br/>
│           struct_objectProb<br/>
│           struct_physSound<br/>
│           struct_prop<br/>
│           struct_propDynamic<br/>
│           struct_propObject<br/>
│           struct_save<br/>
│           struct_scientistSpecialResponse<br/>
│           struct_settings<br/>
│           struct_shroom<br/>
│           struct_signalDataDynamic<br/>
│           struct_SignalEmailResponse<br/>
│           struct_signal_data2<br/>
│           struct_signal_spawn<br/>
│           struct_sound<br/>
│           struct_spaceObject<br/>
│           struct_stats<br/>
│           struct_store<br/>
│           struct_storeOrder<br/>
│           struct_subtitle<br/>
│           struct_task<br/>
│           struct_triggerSave<br/>
│           struct_tv<br/>
│           struct_upgrades<br/>
│           struct_weapon<br/>
│           struct_weightedName<br/>
│<br/>
├───materials<br/>
│   └───phys<br/>
│           bag<br/>
│           bag_flammable<br/>
│           ball<br/>
│           balloon<br/>
│           barrel<br/>
│           batt<br/>
│           body<br/>
│           can<br/>
│           concrete<br/>
│           concrete1<br/>
│           concrete_float<br/>
│           concrete_massive<br/>
│           concrete_massive_float<br/>
│           concrete_shroom<br/>
│           cup<br/>
│           dirt<br/>
│           drive<br/>
│           flesh<br/>
│           food<br/>
│           glass<br/>
│           gold<br/>
│           gold_s<br/>
│           grass<br/>
│           grate<br/>
│           gravel<br/>
│           kerfusWheel<br/>
│           metal<br/>
│           metalHeavy<br/>
│           metalPipe<br/>
│           metalPipe1<br/>
│           paper<br/>
│           plastic<br/>
│           rubber<br/>
│           sball<br/>
│           silent<br/>
│           slide<br/>
│           vehicle<br/>
│           wood<br/>
│<br/>
├───objects<br/>
│   │   actor_save<br/>
│   │   arirShip<br/>
│   │   badSun<br/>
│   │   blackFog<br/>
│   │   borders<br/>
│   │   car1<br/>
│   │   cheat_place<br/>
│   │   cockroachMaster<br/>
│   │   cord<br/>
│   │   cordSocket<br/>
│   │   digcamMaster<br/>
│   │   dish<br/>
│   │   dreamBase<br/>
│   │   drone<br/>
│   │   d_window<br/>
│   │   eg<br/>
│   │   flammable<br/>
│   │   generator<br/>
│   │   generatorFuckuper<br/>
│   │   halloweenMaster<br/>
│   │   hook<br/>
│   │   insomniac<br/>
│   │   jellyfishPath<br/>
│   │   killerwisp<br/>
│   │   ladder<br/>
│   │   objectRenderer<br/>
│   │   orderPlace<br/>
│   │   panelBase<br/>
│   │   panel_SATconsole<br/>
│   │   physicsImpact<br/>
│   │   powerControl<br/>
│   │   printedObject<br/>
│   │   prop<br/>
│   │   propInventory<br/>
│   │   propRenderer<br/>
│   │   propRenderer1OLD<br/>
│   │   propThrown<br/>
│   │   prop_batts<br/>
│   │   prop_beacon<br/>
│   │   prop_box<br/>
│   │   prop_camera_bad<br/>
│   │   prop_clipboard<br/>
│   │   prop_container<br/>
│   │   prop_container_player<br/>
│   │   prop_drive<br/>
│   │   prop_driveRack<br/>
│   │   prop_food<br/>
│   │   prop_food_shrimp<br/>
│   │   prop_gascan<br/>
│   │   prop_gravgun<br/>
│   │   prop_photo<br/>
│   │   prop_rdrone<br/>
│   │   prop_toolbox<br/>
│   │   p_kerfus<br/>
│   │   reactor<br/>
│   │   redSkyEvent<br/>
│   │   riverFlow<br/>
│   │   roz_anim<br/>
│   │   serverBox<br/>
│   │   signalCam<br/>
│   │   sitBox<br/>
│   │   sitting<br/>
│   │   spaceRenderer<br/>
│   │   svtarget<br/>
│   │   svTargetObject<br/>
│   │   telescope<br/>
│   │   theEvil<br/>
│   │   waterFloatMaster<br/>
│   │   waterVolume<br/>
│   │   weaponComp_gravityGun<br/>
│   │<br/>
│   ├───components<br/>
│   │       nametagComponent<br/>
│   │       physicsImpactComponent<br/>
│   │<br/>
│   ├───misc<br/>
│   │       arir_translat<br/>
│   │       birber<br/>
│   │       daynightCycle<br/>
│   │       gearer<br/>
│   │       radarPoint<br/>
│   │<br/>
│   └───triggers<br/>
│           ambienceMastter<br/>
│           triggerBase<br/>
│           trigger_eventer<br/>
│<br/>
└───umg<br/>
    │   umg_clipboard<br/>
    │   umg_console<br/>
    │   umg_coords<br/>
    │   umg_deathscreen<br/>
    │   umg_decoder<br/>
    │   umg_equipmentSlot<br/>
    │   umg_hints<br/>
    │   umg_hovertextNametag<br/>
    │   umg_inventory<br/>
    │   umg_inventorySlot<br/>
    │   umg_laptop<br/>
    │   umg_minimap<br/>
    │   umg_onlineRadio<br/>
    │   umg_paperDraw<br/>
    │   umg_passlock<br/>
    │   umg_printer<br/>
    │   umg_propInv<br/>
    │   umg_propInvInvSlot<br/>
    │   umg_propInvSlor<br/>
    │   umg_radarScreen<br/>
    │   umg_reactor<br/>
    │   umg_signalDownload<br/>
    │   umg_signalPlay<br/>
    │   umg_tvOffline<br/>
    │   umg_UI<br/>
    │<br/>
    └───UI<br/>
            umg_menu<br/>
            umg_quicksave<br/>
            umg_serverMinigame<br/>
</details>