# How to Upload an FBX File Into Unity
(This documentation assumes that you have already created a digital model and now plan to incorprate it into Unity.)

The following instructions are adapted from "Importing an FBX file into Unity with Textures" https://www.cgtrader.com/tutorials/1542-importing-an-fbx-file-into-unity-with-textures

## Converting from STL to FBX

If the file containing your AR cue model exists as an STL file, you will first want to connvert it to an FBX file, which is compatible with Unity. I suggest looking up "STL to FBX converter" on Google. If your file is in another format besides STL, look up a file converter that will give you back an FBX file.


## Create a new project or open an existing one

When you launch the Unity application, you should be greeted with a homepage that allows to choose a project to work on. At the top right of the screen there are two buttons named "New" and "Open". Click on "New" to create a new project or click on "Open" to open an existing project.

## Import the FBX file as an asset

When you've opened a new or existing Unity file, locate the navigation bar at the top left of the screen. Click on the "Assets" menu and then locate the "Import New Asset..." option.

Search your computer's files for the FBX file you just made. Select it and click "Import".

## Place an instance of the asset onto the scene canvas

Once the FBX file has been imported into Unity, you should find it located within the assets folder at the bottom of the screen. Click on the AR cue model and drag it onto the main scene.

## Adding textures to asset

If you notice that your asset is lacking the textures you expected to see, click on the asset in the assets folder at the bottom of the screen. When you do this, a menu will appear on the right side of the screen. Make sure the "Materials" tab is selected.

If your asset textures exist in a separate folder, click on the "Location" drop menu and select "Use External Materials (Legacy)". If the textures are imbedded into the FBX file, then make sure "Use Embedded Materials" is selected instead. Once you click "apply" at the bottom of the "Materials" tab, your textures will appear on the AR cue model.
