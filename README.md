# Gameplay01
Gameplay Skill – Unreal Engine 5
This project showcases a third-person character with three playable abilities:
	Fireball Projectile
	Aura Flame (AoE damage)
	Explosive Dash with Fire Trail

I implemented all systems using Blueprints, including ability logic, cooldowns, timers, hitboxes, animation states, and particle effects. I also created a custom animation for the Aura Flame ability and an idle animation inspired by my favorite esports player (Faker), which plays after 6 seconds of no input.

Abilities
1. Fireball
	Projectile movement
	Hit detection + 20 damage using Sphere Collision overlap event
	Simple VFX
	Cooldown: 5 seconds

2. Aura Flame (AoE)
	Custom animation created from scratch (using starter idle pose as base)
	Looping particle system
	Periodic damage (10 damage per tick for 6 seconds)
	Starts and ends through Blueprint-driven state logic
	Cooldown: 10 seconds

3. Explosive Dash
	Quick forward movement
	Fire particle trails on the feet
	Separate dash animation
	Cooldown: 5 seconds

Note: Enemies have 100 base health, and the UI in the upper-left corner displays debug text for cooldowns, Aura Flame duration, enemy health, and death confirmation. Additionally, this prototype focuses only on ability systems—basic attacks do not deal damage in this build.

Technical Details:
	Entire project built in Unreal Engine 5 Blueprints.
	Hitboxes implemented using Sphere Collision + overlap events.
	Timers used for cooldowns, repeated tick damage, and animation sequencing.
	VFX created using Cascade with Starter Content.
	Animation states controlled through Blueprint logic and event timing.

Why This Project Is Relevant to TFT & 2XKO
This project demonstrates:
	Combat system design & implementation.
	Prototyping abilities and gameplay mechanics.
	Blueprint scripting and technical iteration.
	Hitbox logic, frame timing, and feedback readability.
	Collision-driven damage systems.
	Working with VFX, animation, and gameplay timing.
	Creating features from start to finish (design → prototype → tune).

To view the project:
	Download the Unreal Engine project from the GitHub repository below.
	Open the project in Unreal Engine 5.
	Open the map: Lvl_ThirdPerson.umap

GitHub repository: https://github.com/MCTnyaaa/Gameplay01