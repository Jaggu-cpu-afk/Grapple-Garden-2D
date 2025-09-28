Grapple Garden
A 2D platformer where you play as a space gardener tasked with reviving a barren planet. Use your wits and your unique grappling hook to navigate the environment and bring the planet back to life!

Gameplay
The core gameplay loop is simple:

Collect Seeds: Find scattered seeds across the level.

Grapple and Platform: Use your grappling hook to swing between platforms and reach new areas.

Find Nutrient Pods: Locate special, glowing "Nutrient Pods."

Plant and Grow: Plant the seeds in designated "Soil Patches."

Grow a Vine: Your creative twist! Once you have a charged grappling hook from a Nutrient Pod, use it on a planted seed to instantly grow a climbable vine. This creates new paths and progression.

Scoring & Progression
Scoring: You earn points for collecting seeds and planting them.

Progression: Levels are completed once all seeds are planted and all vines are grown, opening a portal to the next stage. Each level introduces new challenges, such as moving platforms, different types of seeds, or more complex puzzles that require strategic use of the grappling hook and vine-growing mechanic.

Creative Twist: The Nutrient Hook
The grappling hook isn't just for movement; it's also a tool for progression and puzzle solving:

Charging: Hitting a Nutrient Pod with the grapple charges the hook (indicated by the grapple line turning green).

Planting: The next time you use the charged hook on a planted Seed, it won't pull you in—instead, it will cause a giant, climbable vine to sprout from the ground.

This mechanic forces the player to plan their path: you must charge the hook and then use that single charge strategically to create a new route.

Unity Version
This project was developed and tested using Unity 6.

How to Play (In the Editor)
Project Setup: Create a new 2D project in Unity 6 and import the provided C# scripts into your Assets/Scripts folder.

Player Setup: Create a player GameObject with a Rigidbody2D and BoxCollider2D. Attach the PlayerController.cs script.

UI Setup: Create a UI Canvas with a Text element for the score. Attach the GameManager.cs script to an empty object, and drag the score Text element into the Score Text field in the Inspector.

Layers: Ensure your ground, nutrient pods, and seeds are on separate Unity Layers to allow the PlayerController script to detect them correctly.

Controls:

Movement: A and D or Left/Right Arrow Keys.

Jump: Spacebar.

Grapple/Charge/Grow Vine: Left Mouse Button (Fire1)
