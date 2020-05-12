# Layer One Cura files

This is a collection of all files related to the Atom line of 3D printers and the slicing software Cura.

## Qucik install guide Cura 4.X

This guide will quickly go through the steps required to manually add a custom printer and materials definition to Cura. This is only necesary if your version of Cura does not already have support for the specific printer.

### Cura 4.X support
**Printers:** Atom 3, Atom 3 lite 

**Materials:** Layer One PLA (Black, Dark gray, White)

### Windows 10:
1. Download, insntall and **open** the latest version of Cura ([link](https://ultimaker.com/software/ultimaker-cura)). 
2. Download the contents of this repository ([link](https://github.com/atom3dp/atom3-cura-profile/archive/master.zip)).
3. Close the Cura application if it’s open.
4. Open a first Windows file explorer window and navigate to your Cura folder `C:\Program Files\Ultimaker Cura 4.X\resources\`.
6. Open a second Windows explorer window and navigate to the the the downloaded repository and unzip the repository. 
5. From the repository copy the printer definiton files for the printer you need from `LayerOne_resources\definitions` into the `C:\Program Files\Ultimaker Cura 4.X\resources\definitions` folder of the the first explorer window. 
6. Repeat this for the the file(s) from the folder(s):
	- `LayerOne_resources\extruder` 
	- `LayerOne_resources\variants`
	- `LayerOne_resources\meshes`
7. Start Cura
8. Skip this step if no printers have been added to Cura in the past: In the menu bar go to `Settings > Add Printer…`. A new window will open.
9.  Select “Add a non-networked printer, scroll down to “Layer One”, select the “Atom X” printer and click “Add”
10. In Cura open the "Preferences" from the menu bar, navigate to "Materials" and import the files from the `LayerOne_materials` materials folder which is contained in the downloaded repository.
11. Click the “pen” symbol on the top right of the Cura window to expand the print settings.
12. Click on the “hamburger menu button” (three horizontal lines) and select “Basic”, “Advanced” or “Expert”.
14. Done!
 
### macOS 10.15.XX Catalina :

1. Download, insntall and **open** the latest version of Cura ([link](https://ultimaker.com/software/ultimaker-cura))
2. Download the contents of this repository ([link](https://github.com/atom3dp/atom3-cura-profile/archive/master.zip)).
3.	Close the Cura app if it’s open.
4.	Open a first Finder window, click "Go" in the menu bar at the top of the screen and the press and hold the option key ⌥. The folder "Library" in the dropdown menu of "Go" should apear. Click on it to open the "Library" folder. From there navigate to `Library/Application Support/cura/4.X/resources/`
5. Open a second Finder window (⌘command + n) and navigate to the the the downloaded repository and unzip the repository. 
6.  From the repository folder copy the printer definiton files for the printer you need from `LayerOne_resources/definitions` into the `Library/Application Support/cura/4.X/resources/definitions` folder of the the first finder window. 
6. Repeat this for the the file(s) from the folder(s):
	- `LayerOne_resources\extruder` 
	- `LayerOne_resources\variants`
7. Start Cura
8. In the fist Finder window navigate to your  `Applications` folder. Locate the "Ultimaker Cura" app, right click on it, select "Show package contents" and navigate to `“/Contents/Resources/resources/meshes`
9. From the repository folder copy the mesh file(s) for the printer you need from `LayerOne_resources/meshes` into the `meshes` folder of the the first finder window. 
10. Start Cura
11. Skip this step if no printers have been added to Cura in the past: In the menu bar go to `Settings > Add Printer…`. A new window will open.
12.  Select “Add a non-networked printer, scroll down to “Layer One”, select the “Atom X” printer and click “Add”
13. In Cura open the "Preferences" from the menu bar, navigate to "Materials" and import the files from the `LayerOne_materials` materials folder which is contained in the downloaded repository.
14. Click the “pen” symbol on the top right of the Cura window to expand the print settings.
15. Click on the “hamburger menu button” (three horizontal lines) and select “Basic”, “Advanced” or “Expert”.
16. Done!

## Contributing

If you find any issues or want to make a change please open an issue and describe your problem as best as you can. 
## Project status
The profiles are currently (2020.05.12) in beta. Thourougly tested are:

- Atom 3 + all metal hotend + 0.4 mm brass nozzle
- Atom 3 + PTFE hotend + 0.4 mm brass nozzle
- Atom 3 lite + all metal hotend + 0.4 mm brass nozzle
- Atom 3 lite + PTFE hotend + 0.4 mm brass nozzle