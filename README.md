![github1](https://github.com/FUE5BASE/FUE5/assets/127543827/3e18c5dd-9220-4f50-94a1-d402e68c6eb5)
# FUE5
FUE5 is a fan-made project with the goal to see what would Factorio look like and behave in 3D. I started this project on [10th of January 2023](https://cdn.discordapp.com/attachments/1082941602806374521/1103027209960181760/image.png) and my friend Nuke ([Atria1234](https://github.com/Atria1234) on GitHub) joined shortly after with the most awesome idea of exporting the in-game bases directly to UE5 which accelerated the project forward.

## What you need to know to run this project:

1. [Download](https://www.unrealengine.com/en-US/download) and install Unreal Engine 5.1 
2. Download this project. Either via [GitHub Desktop app](https://desktop.github.com/) or just by getting the packaged [.zip file](https://github.com/FUE5BASE/FUE5/archive/refs/heads/main.zip).
3. Unpack the project and run it by opening FUE5.uproject
4. The project is set to load simple "Welcome" scene containing several buildings. Little heads-up - it'll probably do something called "Compiling Shaders" on first startup and since there are thousand of shaders involved it might take around 10 minutes.
5. Now you can use the [FUE5-Exporter](https://github.com/FUE5BASE/FUE5-Exporter) to export your Factorio base and transfer it to FUE5.

## Disclaimer:
I do not own the IP of the Factorio game, it's assets or any of the related designs. All credit goes to the Factorio owner and developer Wube Software. Massive respect for the insane feat of engineering and optimization the actual Factorio game is!

## FAQ
**How does it work?**<br>
Nuke wrote a Factorio mod called [FUE5-Exporter](https://github.com/FUE5BASE/FUE5-Exporter), which exports the ingame base as a .json text file. This text file is then parsed by our UE blueprints which create 3D replica of your ingame base in UE5. Most of the trailer shots have been built this way.

**Is there any gameplay?**<br>
No. All you can do is to fly around your base and toy around with existing assets and UE construction and event blueprints. For those with experience in UE there is a lot of fun stuff you can do with the blueprints we've designed for the belt, rail and logistic systems.

**Where did we get the assets?**<br>
We created them from scratch in Cinema4D based on the pictures from the game. There were some problems getting the game-ready topology right but with practice I was able to replicate up to two individual structures per day.

**Why Unreal Engine 5?**<br>
It looks awesome and it's blueprint system is perfect for replicating Factorio ingame systems if you don't know how to code. It also beats the standard 3D editors like Cinema4D or Blender in this particular application where you need to get realtime results.

**Can my PC run this project?**<br>
I've specifically bought RTX4090 just to be able to work the scenes in the trailer at around 30-60 FPS. I always had the settings on maximum tho. **We're currently optimizing each building and each UE blueprint to deliver good performance with larger bases.**

**Why do this?**<br>
The factory must grow.<br>

**Is there a guide on how to use the exporter?**
Yes! You can go read this [Guide](https://github.com/FUE5BASE/blob/main/BaseImportGuide.md) which has steps you can follow to export a section of your base and view it in FUE5.


## Special Credits
Phorge<br>
swistak84
