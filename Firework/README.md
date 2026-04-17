Textures in common for all Fireworks:
- in grenade directory: `model/weapon/grenade/firework.dds`
- in sfx directory: `ef_fireball.BMP.dds`, `midglow.dds`, `firework_powder.dds`, `ef_Blitz_04.bmp`, `ef_Blitz_Honer.dds`

`effect.xml`:
```xml
<EFFECT NAME="we_grenade_firework" MINDISTANCE="200" MAXDISTANCE="1000" type="2"/>
```

`weapon.xml`:
```xml
<!-- Firework grenade . X -->
<AddWeaponElu name="firework" weapon_motion_type = "6" weapon_type = "7" >	
	<AddBaseModel name="firework" filename="model/weapon/grenade/firework.elu" />
</AddWeaponElu>
```

`zitem.xml`:
```xml
<!-- Grenades: Firework -->
<ITEM id="XXX" name="Firework" mesh_name="firework" totalpoint="0" type="custom" res_sex="a" res_level="1" slot="custom" weapon="frag" weight="3" bt_price="0" delay="700" damage="0" ctrl_ability="20" magazine="8" reloadtime="0" slug_output="false" gadget_id="0" hp="0" ap="0" maxwt="0" sf="0" fr="0" cr="0" pr="0" lr="0" color="#FFFFFFFF" image_id="3" bullet_image_id="0" magazine_image_id="0" desc="Fireworks everywhere!" snd_fire="we_grenade_firework" maxbullet="8" />
```

`effect_list.xml`:
```xml
<!-- Grenades: New Years Eve Firework (Cyan, Pink and Green) 01 -->
<AddEffectElu name="firework_newyear" name_sort="1">
    <AddBaseModel name="firework_newyear" filename="firework_newyear.elu" />
    <AddAnimation name="play" filename="firework_newyear.elu.ani" motion_type="0" motion_loop_type="lastframe" />
</AddEffectElu>

<!-- Grenades: Christmas Firework (Red, Blue and Green) 02 -->
<AddEffectElu name="firework_christmas" name_sort="1">
    <AddBaseModel name="firework_christmas" filename="firework_christmas.elu" />
    <AddAnimation name="play" filename="firework_christmas.elu.ani" motion_type="0" motion_loop_type="lastframe" />
</AddEffectElu>

<!-- Grenades: Valentines Firework (Pink Hearts) 03 -->
<AddEffectElu name="firework_valentine" name_sort="1">
    <AddBaseModel name="firework_valentine" filename="firework_valentine.elu" />
    <AddAnimation name="play" filename="firework_valentine.elu.ani" motion_type="0" motion_loop_type="lastframe" />
</AddEffectElu>

<!-- Grenades: Firework (Yellow Stars) 04 -->
<AddEffectElu name="firework_star" name_sort="1">
    <AddBaseModel name="firework_star" filename="firework_star.elu" />
    <AddAnimation name="play" filename="firework_star.elu.ani" motion_type="0" motion_loop_type="lastframe" />
</AddEffectElu>

<!-- Grenades: Firework (Red/Orange) 05 -->
<AddEffectElu name="firework_red" name_sort="1">
    <AddBaseModel name="firework_red" filename="firework_red.elu" />
    <AddAnimation name="play" filename="firework_red.elu.ani" motion_type="0" motion_loop_type="lastframe" />
</AddEffectElu>

<!-- Grenades: Firework (Blue/Cyan) 06 -->
<AddEffectElu name="firework_orange" name_sort="1">
    <AddBaseModel name="firework_orange" filename="firework_orange.elu" />
    <AddAnimation name="play" filename="firework_orange.elu.ani" motion_type="0" motion_loop_type="lastframe" />
</AddEffectElu>

<!-- Grenades: Firework (Green/Light Green) 07 -->
<AddEffectElu name="firework_green" name_sort="1">
    <AddBaseModel name="firework_green" filename="firework_green.elu" />
    <AddAnimation name="play" filename="firework_green.elu.ani" motion_type="0" motion_loop_type="lastframe" />
</AddEffectElu>

<!-- Grenades: Shiny Firework (Blitz Honor particles) 08 -->
<AddEffectElu name="firework_shiny" name_sort="1">
    <AddBaseModel name="firework_shiny" filename="firework_shiny.elu" />
    <AddAnimation name="play" filename="firework_shiny.elu.ani" motion_type="0" motion_loop_type="lastframe" />
</AddEffectElu>

<!-- Rocket Launcher: Firework explosion (Red)  01-->
<AddEffectElu name="fw_blow" name_sort="1">
    <AddBaseModel name="fw_blow" filename="fw_blow.elu" />
    <AddAnimation name="play" filename="fw_blow.elu.ani" motion_type="0" motion_loop_type="lastframe" />
</AddEffectElu>

<!-- Rocket Launcher: Firework projectile (Standard) 02 -->
</AddEffectElu>
    <AddEffectElu name="fw_proj" name_sort="1">
    <AddBaseModel name="fw_proj" filename="fw_proj.elu" />
    <AddAnimation name="play" filename="fw_proj.elu.ani" motion_type="0" motion_loop_type="lastframe" />
</AddEffectElu>
```

`shop.xml`
```xml
<SELL itemid="XXX" /> <!-- Grenades: New Year's Eve Firework (Cyan, Pink and Green) -->
<SELL itemid="XXX" /> <!-- Grenades: Christmas Firework (Red, Blue and Green) -->
<SELL itemid="XXX" /> <!-- Grenades: Valentines Firework (Pink Hearts) -->
<SELL itemid="XXX" /> <!-- Grenades: Firework (Yellow Stars) -->
<SELL itemid="XXX" /> <!-- Grenades: Firework (Red / Orange) -->
<SELL itemid="XXX" /> <!-- Grenades: Firework (Green / Light Green) -->
<SELL itemid="XXX" /> <!-- Grenades: Firework (Blue / Cyan) -->
<SELL itemid="XXX" /> <!-- Grenades: Firework (Purple / Pink / Red) -->
```