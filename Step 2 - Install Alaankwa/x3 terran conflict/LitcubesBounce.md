# Litcube's Bounce V1.7
Release Version

Player Owned Autopilot Controlled Ship Collision Avoidance
This post has changed since the alpha release.
Included support for AP

Youtube vid (not a single Jaguar was harmed in the making of this film):
http://www.youtube.com/watch?v=0s9afUiS4LY


Download Bounce:
Image

Thank You

- Sincere thanks to alpha testers Requiemfang, Katorone, Ikaruga, Firewrath.
- Timelines crew, for technical support, and especially sms_747 for her emotional support and having the Node idea from the get go (as I continuously ran into brick wall after brick wall with other methods). Sms_747: :star:


## Installation & Tech Details

If you're running vanilla:

- Dump script files into your script directory.
- Dump t/Vanilla/8389-L044.xml into your t directory (just that one file, no sub-directories). Use the AP or the TC one.
- Run the game.
- Setup your hotkeys (Controls -> Interface -> Bounce: on and Bounce: Off).

If you're running a mod that changes TShips models or add ships:

- 8389-L044.xml is what's called a Wall file and is required to run Bounce. As long as you have the proper Wall file, Bounce will be compatible with that mod. The Wall file is specific to the TShips file, and the Wall file included in the t/vanilla folder is for vanilla only. Within the t directory of this package, you'll find sub directories on popular mods. If you find the mod you're using there, use that Wall file instead. It matches the name of the vanilla Wall file. If you do not find your mod's Wall file, or you have your own customized ship altering mod, you can generate your own Wall file automatically using the built in Z.Bounce.Wall script. See the bottom of this post for instructions on how to do that (it's easy).
- Run the game.
- Setup your hotkey (Controls -> Interface -> Bounce: Toggle).

Other notes:
- If you're not generating your own Wall file as mentioned in the previous step, ignore BounceWallXX.cat and BounceWallXX.dat. You do not need these 2 files to run Bounce. They are only used to generate the Wall file (8389-L044.xml)
- I don't mind installation questions on this one, provided you give me the password: Chicken Poop.
- Instructions on generating your own Wall file are below under Generating Your Own Wall File.
- Wall files included: X-Tended, SRM, X-Tra Ship/Station pack. I believe Timelines uses SRM. Versions listed in the sub-folders of t contained within the downloadable package.


## What Is It?

As everyone knows, the AI autopilot is absolutely horrible. Spend 30 mins outfitting your shiny new Asps and send them off to take out that Titan. Result: Most of them will collide with the side of the ship. With an almost certainty, they will all die by collision. Seriously, it looks like kamikaze. It's so bad, it almost looks as though Egosoft intended this. This plugin is an attempt to remedy this via scripts. It's a simple, but so far effective package. Once Bounce is engaged via hotkey, as a ship nears its target (ship or station), a collision avoidance routine is engaged to avoid the enemy ship or station. Also, when an enemy ship is not detected within 10 KM, AND there are no missiles currently locked onto a ship, your ships will ignore collisions. So you can have your formation without experiencing collisions with your other ships, neutral ships, asteroids, gates, or stations. Once an enemy is detected in 10 km, this feature is skipped, and Bounce avoidance checks are engaged. The player ship is not effected. Only player owned ships of all sizes.

I didn't detect any performance difference in large scale battles (300+ ships). Turning Bounce on, or off, didn't change frame rates or performance on a 6 capital versus 300 fighter battle. There was no 0 m/s glitches.

I have decided that I'm not a fan of collision spheres, or collision bounding boxes, or "safety nets" in a scene file. Some of you know what I'm talking about, but for those that don't, it's basically a model that is larger than the ship. This model is transparent so the player can't see it. But because it's there, and it's large, the idea is that ships will avoid sooner, thus avoiding the embarrassing collisions. Some mods in this forum include them (SRM, XTC). The problem with this, is that missiles, in particular, will miss a ship with such an object. The degree of waste is based on how far the collision object extends outside the ship, but if you want to test this, load up XTC and launch a poop load of mosquito missiles at a titan. See them circle the ship in confusion. No thanks. Just my opinion, though, folks.

Also included in this package is the test script "a.....SimpleTest" script. Run it to see what Bounce can do. There are no parameters, but you can change them by opening the script up and changing the one and only line. It's a one line script, and self explanatory. Don't save your game after running the "a....SimpleTest" script.


## Results and tests I ran
Here's some test results from only some of the countless tests I ran. Enemy ships with no weapons.

- 6 Phoenix Vs. 300 Jaguar
Bounce off: 300 losses
Bounce on: 1 loss (one to a North Gate, and one to a Jaguar)

- 2 Titan Vs. 30 Hydra
Bounce off: 4 losses
Bounce on: 0 losses

- 1 Megalodon Vs. 200 Buster
Bounce off: 123 losses
Bounce on: 0 losses

- 30 Panther Vs. 30 Shrike
Bounce off: 1 loss
Bounce on: 0 losses

- 30 Titan Vs. 30 Titan
Bounce off: 0 loss (Oddly)
Bounce on: 0 losses

- 30 Shark Vs. 160 Mamba
Bounce off: 92 losses
Bounce on: 0 losses

- 30 Shark Vs. 160 Elite
Bounce off: 34 losses
Bounce on: 0 losses


I ran extensive frame rate testing. I could not detect a difference in frame rate between when Bounce was enabled and when Bounce was not enabled.


## How to use Bounce

During alpha, Bounce was an AL plugin. This is no longer the case, as I felt that hotkeys offered a) more control and b) better performance. Bounce now installs one toggle hotkey. Once enabled, you will see the message "Bounce has been enabled". Toggling it back off tells you "Bounce has been disabled". While enabled, all player owned ships will automatically know when bounce should be enabled, and functionality is automatic.

If Bounce is not engaged, there are NO scripts related to this package running on the Universe at anytime. Also note that the Bounce script automatically stops running on ships once they are not in the active sector. The active sector is the one that you, the playership, are currently in. If the ships aren't being rendered, Bounce does not run on them.

Please post your results, comments, etc.



## Generating Your Own Wall File

If you don't find your mod in the list of text file folders, or you have changed, added, or removed ships from the ones included, you will have to generate your own Wall file. The wall file is an xml file used to tell Bounce the dimensions of ships. Instructions are as follows:

- Install the BounceWall.cat and BounceWall.dat as a false patch. Do not use as a mod in the mod's folder.
- If you are currently using a mod that is in the mod folder, ensure that it does not contain a TFactories file. If it does, temporarily remove it. You can put it back once the Wall file is generated. As an alternative to removing the Tfactories file, you can make the mod a false patch, as long as it comes before (a number less than) the BounceWall.cat (which will of course be renamed as a number because you've changed it to a false patch, right?).
- Run the game
- While not necessary, finding a sector that isn't very busy makes the Wall file generate faster.
- While not necessary, turning off your HUD will make the Wall file generate faster.
- Run the Z.Bounce.Wall script by selecting it in the scripts list and hitting "r", and then "Enter".
- Everything in the sector is destroyed, except you.
- You should see periodic messages telling you what ship is currently being dimensioned.
- Don't do anything during this time.
- Depending on your frame rate, this whole process might take up to 3 minutes. My frame rate was 300 - 500, and it took 2 minutes 37 seconds to generate the vanilla ships Wall file. Could take longer, could be shorter. You only have to do this once, folks.
- Once finished, you'll see the message "Finished the Wall!"
- In your output folder, which is in your documents/Egosoft/X3TC (same folder your screenshots come out of), you'll see a log08389.txt.
- Rename it to 8389-L044.xml and copy it into your t folder of your X3 Terran Conflict installation directory.
- You now don't need the false patch; you can delete it.
- You're done!
- If you'd like me to include Wall files in this package, e-mail me at jkossowan at gmail dot com.


## Notes on How it Works, If You're Interested!

- Two main scripts are involved in Bounce, and this is how they work:
- All player ships in sector start a looped check script on task 323.
- If a Bounce enabled player owned ship comes within $danger.range (derived from a formula based on the 8389-L044.xml Wall file) meters of an enemy, friendly, or neutral Huge Ship (TL, M7, M1, M2), the Huge Ship will start the looped Node script on task 324.
- The Node script generates 5 nodes along the spine of the ship with radius and length of the spine derived from the 8389-L044.xml Wall file.
- The Node data is obviously only good as long as it's updated to the ship's changing position. This is done frequently, based on how fast the ship moves. If it's not a fast ship, we don't need to update very often.
- If there's no ships within $danger.range meters, the looped node script goes into idle mode, and stops generating nodes to save performance.
- This data is snatched from the player owned ship's Bounce check script.
- Based on the node data that the player owned ship gets, it decides if a collision is imminent. This is derived from speed of the ship, and the distance to all nodes.
- If there's no enemies within 10 km, the player check script goes into safe-mode, turning off collisions completely (no more formation losses), and slows down the checks considerably to save performance.
- If it is determined that during idle mode, collision should be turned off, to avoid destruction if the player ship happens to be within or intersecting an object, the ship is moved outside the bounding sphere of the object before turning collision checks back on.
- If it is determined that a player owned ship *is* in need of action because it's about to collide with a huge ship, it runs Evade, but only if not in idle mode.
- Evade turns off collision detection for a maximum of 1 second while the ship launches in the opposite direction. During this time, no bullets can hit the ship. To compensate in regards to balance, fairness, and all that crap, the ship is unable to fire back (through ANY turret).
- Evade continues until the player owned ship is safely away from the ship, and then continues on normally, susceptible to enemy fire.
- If any ship (player or enemy, Bounce Check script or Node script) is suddenly not in an active sector, scripts are exited.