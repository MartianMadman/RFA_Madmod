Red Faction Armageddon Madmod is a major overhaul mod that is dedicated towards transforming the slow and sluggish feel of being a modern shooter to the much more enjoyable style of older games. Engine technology has also been given a fair improvement as well with better light draw distances and more advanced collision physics for many objects. 

(REVERTED) means that the change is no longer in the latest versions because of reasons like issues caused by them or not being an ideal change to the game.

\Changelog v0.1b/
-The shotgun, pistols, banshees, pulse grenades, rocket launcher, lava barge, and rail driver will fire as fast as you click.
-Increased distance at which blood and bullet hole decals are allowed to be drawn.
-Decals will only start despawning based on a limit rather than a timer.
-Gibs will only start despawning based on a limit rather than a timer.
-Added ability to skip all startup splash screens.
-Gibs, ammo boxes, and salvage now cast shadows.
-Reduced bullet spread for all weapons.
(REVERTED)-Increased range that weapons can fire.
-Increased max amount of ammo to 999.
-Increased nanoforge repair radius.
-No charge up on the plasma cannon.
-Removed cooldown on all weapons.
-Increased draw distance of gibs.
-Increased draw distance of npcs.
-Increased player sprint speed.
-Removed melee auto targeting.
-All structures drop salvage.
(REVERTED)-Removed nanoforge cooldown.
-Bullets damage structures.
-Increased jumping height.
-Removed weapon recoil.
-Disabled camera shake.
-Bigger blood decals.
-Removed fall damage.
-Infinite sprint.

\Changelog v0.11b/
-Changed on foot camera view to 1st person because 1st person has superior player movement handling. Vertical fov is at 75 and horizontal fov will differ depending on the aspect ratio. Horizontal fovs will be |5:4 = 87|4:3 = 91|16:10 = 101|16:9 = 107|21:9 = 121|.
(REVERTED)-Attempted to improve the AI of the aliens and their ability to kill the player as well as increasing their overall aggressiveness. AI pathfinding is generally still pretty bad.
-Removed creeper and grunt melee finishers since they mess with the 1st person view and also slow down the player.
-Fixed not being able to stop napalm laser from firing along with other weapons which may have the same issue.
-Removed player flinch and landing animations since they slow down the players movement.
-Classic FPS movement controls. Always run by default, use sprint button to walk.
-Increased player movement speed when in the forced walk state.
-Removed weapon fire charge up on unicorn gun and plasma beam.
-Singularity cannon and xmg-5000 fire as fast as you click.
-Increased refire rate of repair grenades.
-Increased alien pod spawn rate.
-Removed weapon swapping delay.
-Tweaked blood decals.

\Changelog v0.12b/
-Added collide_as_mover_not_with_humans flag to all gibs which allows the magnet gun to target them. Also allows physics to be applied from melee attacks.
-Removed goon AI effects. Idk what it really does but I found it in tweak_tables.xtbl. When I set it to always be on, I found that the AI seemed dumber.
(REVERTED)-Added casts_shadows flag to everything in gameplay_properties.xtbl, rfg_materials.xtbl, and items_3d.xtbl.
-Increased draw distance of all dynamic lights giving the game a noticeable visual upgrade.
(REVERTED)-Increased vertical fov to 90. New horizontal fovs are |4:3 = 106|16:9 = 120|
-Replaced NPC death animations with ragdoll physics for some weapons.
-Restored nanoforge cooldown. Cooldown speed has been doubled.
-Increased alien pod spawn rate to as high as possible.
-Remove player sequential damage reduction.
-Improved NPC vs NPC combat gameplay.
(REVERTED)-Tweaks to rfg_stress_controls.xtbl.
-Increased potential lod distances.
-Increased velocity of tracers.
(REVERTED)-Increased NPC fire burst size.
-Reduced NPC bullet spread.
-Tweaks to difficulty.xtbl.
-Improved NPC aim.

\Changelog v0.13b/
(REVERTED)-Slightly shifted 1st person camera forward when crouching to prevent dual pistol models from clipping in view.
-Slightly shifted camera on exos to the right to prevent crosshair from targeting itself.
-Decreased vertical fov back to 75 for a less distorted view and higher draw distances.
-Removed deep pockets upgrade since this mod makes that upgrade useless.
-Lava barge turrets and Charge launcher will fire as fast as you click.
-Slightly offset camera view forward when looking down.
-Increased dynamic light draw distances even further.
-Decreased delay between remote charge detonations.
-Added 1st person to ragdolling.
-Decreased player jumping delay.
-Assault rifle can gib enemies.
-Added 1st person to turrets.
-Tweaked blood decals again.
-Tweaks to weapon zoom.
-Tweaks to ammo.xtbl.

\Changelog v0.14b/
-Slightly reduced amount of salvage received to compensate for the removed upgrades. Doesn't affect the amount spawned.
(REVERTED)-Removed NPC fall damage to prevent aliens from tripping over debris and instantly dying.
-Removed exo flinch and landing animations because they slow down the players movement.
-Removed bigger clips and rapid blast upgrades since they are useless with this mod.
-Tweaks to aim_drift.xtbl and weapon_firing_patterns.xtbl.
(REVERTED)-Attempted to improve the AI of the aliens again.
-Tweaked difficulty.xtbl and ammo.xtbl again.
-Fixed more odd and out of place shadows.
-Doubled magnet gun pull radius.
(REVERTED)-Doubled long distance repair radius.
(REVERTED)-Even more aggressive AI.
-Removed reloading.

\Changelog v0.141b/
-Readded casts_shadows flag to almost everything in gameplay_properties.xtbl but without creating most of the odd shadows.

\Changelog v0.142b/
-Reduce NPC combat reposition distance from 999 to 99.
-Remove player and npc weapon hit effects delay.
-Removed walk decreasing health regen rate.
-Increased pull speed of all magnet guns.
-Increase human fall movement modifier.
-Remove tentacle melee cooldown.

\Changelog v0.143b/
-Fix enemies not moving in close enough for melee attacks to make contact with the player.
-Removed player forward dodge animation since they don't work with the 1st person view.
-Increase npc incline/decline blend tree distance.
-Allow Rail Driver to gib enemies.

\Changelog v0.9b/
-Fix AI using movement behaviors in which they don't have animations for.
-Fix certain weapons slowing player movement speed while being fired.
-Tweaks to ammo.xtbl and lod_properties.xtbl again.
-Fix startup crash on publicbeta version of RFA.
(REVERTED)-Remove tweaks to rfg_stress_controls.xtbl.
-Add a choice between 3rd or 1st person.

\Changelog v0.9.1/
-Increase return to mission area countdown timer to absurd levels to basically disable the feature.
-Limit charge launcher max projectiles to 32 because of engine limitation.
-Adjust lod_properties.xtbl to potentially fix more lights not working.
-Fixed AI bugs caused by the increased weapon firing distances.
-Changed many player animations to improve the 1st person view.
-Tie heavy walker primary fire rate to mouse click rate.
-Optimize use of projectiles for RF exo secondary fire.
-Restore original npc burst size to fix more ai issues.
-Utilize more of the player model in 1st person.
-Tie RF exo alt fire rate to mouse click rate.
-Fix missing visual features in 1st person.
-Increase pre-placed salvage pickup radius.
-Adjust salvage multiplier.
-Adjust game difficulty.
-Reduce ammo pickups.
-Adjust turret view.

\Changelog v0.9.2/
-Slightly reduce ammo pickups for a few more weapons like the plasma beam, charge launcher, and singularity cannon.
-Disable homing rockets for rpg and exos because it feels too guided and removes a factor of player skill.
-Change player in air melee animations for 1st person view.
-Tie leo rocket launcher fire rate to mouse click rate.
-Optimize use of projectiles for flyer secondary fire.
-Optimize use of projectiles for leo rocket launcher.

\Changelog v0.9.3/
-Remove no_auto_delete flag for spawned salvage to hopefully fix entities not always spawning.
-Change shotgun and charge launcher player animations for 1st person view.
-Add alternate version of Madmod optimized for older computers.
-Disable homing projectiles for flyer and heavy walker.
-Improve collision physics for ammo boxes.
-Redo tweaks to rfg_stress_controls.xtbl.
-Increase draw distances even more.
-Fix more potential ai issues.

\Changelog v0.9.31/
-Fix ammo box collision bug. Issue caused by previous update.

\Changelog v0.9.4/
-Attempt to reduce severity of rl_d3d_light's exceeded error by slightly reducing large light draw distance and disabling salvage highlights.
-Immediately remove distant spawned salvage to reduce number of world objects from exceeding engine limitations.
-Prevent debris collisions from interrupting health regeneration.
-Change dual pistols player jump animation for 1st person view.
-Fix salvage tutorial message not showing at the correct time.
-Slightly reduce lighting draw distances for lower-specs.
-Prevent falling from interrupting player health regen.
-Replace more death animations with ragdoll physics.
-Improve player model clipping for 1st person view.
-Increase swapping speed of the fast hands upgrade.
-Slightly reduce amount of salvage received.
-Increase crouch to stand view switch speed.
-Adjust camera positions for 1st person.
-Slightly increase weapon pickup radius.
-Improve auto targeting for gamepads.
-Increase fov for walkers.

\Changelog v0.9.41/
-Use the correct lower-specs 1st Person Packed files.

\Changelog v0.9.5/
-Slightly reduced medium light draw distance to fix a few more lights not working in one level.
-Reduced long distance repair radius to reduce stuttering when repairing large structures.
-Increase hollow tipped rounds upgrade head shot damage multiplier.
-Doubled Assualt rifle, Nano rifle, and dual Pistols npc damage.
-Allow gibbing of Cultists from weapons other than explosives.
-Further increased Fast Hands upgrade weapon swapping speed.
-Doubled explosion damage from the Pulse grenade launcher.
-Increased small firearms structural damage.
-Further reduced size of ammo pickups.
-Behemoth corpse never despawns/fades.
-Doubled nano rifle explosion radius.
-Player melee always ragdolls npcs.
-Use 100% Hammer melee gib chance.
-Use headshot damage multiplier.
-More randomized shotgun spread.

\Issues/
-Makes game more hardware demanding.
-Destructibles with moving parts when repaired may spontaneously break shortly after. This is caused by spawned salvage getting stuck in moving parts.
-Do not lower the fov in camera.xtbl. This can cause the lighting to break. Increasing the fov is fine though since higher fovs = lower draw distances.
-Unwanted fov scaling for 4:3 aspect ratio. To prevent this, launch game in 16:9 and then switch to 4:3 resolutions. Do not worry about this issue if using 3rd person view or 16:9+ displays.
-There is a engine limitation preventing the lighting draw distance from being set really high. So don't be going into lod_properties.xtbl and messing with those values I set as they are about as high as you can get them without too many issues at the current fov.

\Installation/NOT FOR GITHUB!
There are two versions of this mod, default-specs is for modern computers while lower-specs is for older computers.

For regular users, open the Packed folder and copy paste misc.vpp_pc along with table.vpp_pc to the build/pc/cache directory located in the main RFA installation directory. Replace existing files when asked.

For advanced users you can pack .vpp_pc files yourself for use with other mods or personal tweaks. The folder titled Source contains the modified .xtbl files of this mod.
