# MP2 Design Document

*Jeffrey Tang (jt12)*
CS 498 GD - MP2: Level Design

Video Demo: https://jeffreytang.com/cs498gd_mp2_demo.mp4 (09:00)

## The Turret (custom enemy)

<img width="500" alt="image" src="https://user-images.githubusercontent.com/4369024/159018439-09a55cf1-e688-4b35-bb0b-c33fcd1bc4e2.png">

These yellow spheres are turrets. They're similar to mortars (purple spheres), except they launch projectiles aimed at the player rather than in a random upwards direction.

Unlike mortars, which are generally placed on flat ground, turrets are often placed on vertical surfaces. In the level, you will often find them on the sides of islands and mounted on walls to make it harder to fly towards them.

## Gameplay techniques

### Jump and fly

<img width="300" alt="image" src="https://user-images.githubusercontent.com/4369024/159018509-94804841-88bd-48d6-8be5-f41c2e901992.png">

Early on, you will probably realize that you although you can fly, you can't fly upwards directly. In order to fly at a slightly higher elevation than the ground you're lifting off from, you'll need to tap the space bar twice in rapid succession--once to jump, and once to start flying from your jumping height.

### Sniping from the air

<img width="300" alt="image" src="https://user-images.githubusercontent.com/4369024/159018595-5d0f5c20-5873-454b-9fcc-9e3618aa680d.png">

From island height, jump, then while you're falling, hit space to start flying at the elevation of the Pursuers. Then, you can fly away from the island so the Pursuers can't reach you. Snipe the Pursuers by safely launching projectiles from far away.

### Jumping kill

<img width="300" alt="image" src="https://user-images.githubusercontent.com/4369024/159019065-aa4c03f9-1b3a-453e-8645-b3c9a0bea7b9.png">

When a Pursuer gets too close, and there's not enough time to launch a projectile at them accurately, you can time your jump just right and kick them in the head. This instantly kills them.

### Taking cover

<img width="300" alt="image" src="https://user-images.githubusercontent.com/4369024/159019852-944942cb-2d5e-4b0b-abd3-406552f1ab49.png">

Pursuers and turrets can only target the player when they have a line of sight towards them. Thus, taking cover is a great way to take a break and plan next steps without being attacked.

## Level components

The levels are designed to challenge how well the player understands the behavior of the enemies and the gameplay techniques to sidestep or defeat them.

Although it's possible to fly around many of the enemies and obstacles in this level and just get to the end, this comes at the cost of a much lower score when compared to fighting enemies and collecting obstacles normally.

Players have to interact much more closely with the nuances of the level in order to actually get bragging rights in front of their friends.

### Part 1

<img width="500" alt="image" src="https://user-images.githubusercontent.com/4369024/159020278-f87fb0e3-d57f-4ada-af03-ae149492890a.png">

This part is designed to introduce the player to all three types of enemies. Although it may look chaotic and dangerous at first, the player will quickly notice that Pursuers move at a slower pace, making it easy to run around them. Mortars launch projectiles randomly, so you don't actually get hit that often.

After climbing the stairs and proceeding to the area with more structures, the player meets the first turrets in the game. Unlike the other enemies, the turrets are mounted on the sides of walls and roofs. For the beginners, it's best not to try to destroy these, since the projectiles can hit you while you're traveling towards them.

There are a few collectibles and a health pack in the house with water, which allows the player to recharge before heading to the next level.

Even in this first part, it's possible to apply more advanced techniques like "Sniping from the air" and "Taking cover" in order to get more points. Also, there are additional collectibles on top of the rocks in the rear of the island (these are difficult to collect though because the turrets have a line of sight towards them).

### Part 2 (optional)

<img width="500" alt="image" src="https://user-images.githubusercontent.com/4369024/159021693-f3a4df6d-3dcf-492c-9e34-7f5d8d47acf2.png">

There are some more collectibles here, as well as some Pursuers. This is a great area for the player to practice the "Sniping from the air" and "Jumping kill" skills.

### Part 3

<img width="500" alt="image" src="https://user-images.githubusercontent.com/4369024/159022001-26b25621-4847-4024-b3f9-e1a2f2a63a22.png">

This is a great area for the player to practice "Taking cover", which becomes especially useful in Part 5. The turrets are arranged in an arc around a few walls. You should notice that the turrets don't fire at you when you're behind the walls. This gives you some time to plan how to take them out!

### Part 4 (optional)

<img width="500" alt="image" src="https://user-images.githubusercontent.com/4369024/159022128-296795ca-f32d-4b33-94a8-7bf95bdd879d.png">

You don't necessarily need to fly from the stairs in Part 3 to reach Part 5. Instead, you can also fly from island level to Part 4, which contains an additional health kit. This can be a much-needed boost before facing the final onslaught of enemies.

<img width="500" alt="image" src="https://user-images.githubusercontent.com/4369024/159022238-268ec271-c258-4812-8416-09718d8417ca.png">

Additionally, taking the stairs from Part 4 instead of Part 3 allows you to flank the enemies and avoid the large number of turrets when flying towards the island. You can take advantage of line of sight here again.

### Part 5

<img width="500" alt="image" src="https://user-images.githubusercontent.com/4369024/159022502-a51844a3-82a7-46fd-95fd-3c5413d9cafb.png">

This is it. The final wave. If you're scared, you can just book it to the little house, where you'll find a nice (game-ending) surprise inside.

<img width="500" alt="image" src="https://user-images.githubusercontent.com/4369024/159022359-74ef4911-d107-47fc-92e1-fe4f44262edc.png">

But Part 5 is also designed to be an opportunity to use all of the gameplay techniques you've developed so far in order to maximize your score. You can get a little taste of that in the [last minute of the demo video](https://jeffreytang.com/cs498gd_mp2_demo.mp4), or by playing the game yourself!
