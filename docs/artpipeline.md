# Art Pipeline

## Create an ActorCore Account

Navigate to [ActorCore](https://actorcore.reallusion.com/auto-rig) and click on **Free Download** then register an account to download the product. Once it's downloaded, open and install it.

After installing, open the application and sign in with the account you have created.

## Using AccuRig

### Loading your model

AccuRig should open directly to a menu where you can upload your character. Simply click on **Choose File** and select the file from your computer.

![choosefile](choosefile.PNG)

## How to import 3D models / images in Unreal\

## Creating a Player Unit

The **BP_PlayerUnitBase** *needs* to be selected when creating a new unit.

For further explanation please refer to [jRPG-Documentation](https://docs.google.com/document/d/1NqsJhT1TMfxWrWhaA9jafYDIJ5gpT3rS1UkIAOG4lP0/edit#) section 3.3 and the text there.

## Connecting Models to a Character

The **Big Image** tab of the **BP_PlayerUnitBase** is responsible for the image that shows up during the UI details.

**Battle Image** is image shown during the battle.

**Thumbnail** is the image shown during the character summary UI and in the battle details UI. This will be the character showing during the battle scene. 

## Rigging Models

Player animations can be set under the **Animations** tab inside the **BP_PlayerUnitBase**. For an illustration, look at section 3.3.3 in [jRPG-Documentation](https://docs.google.com/document/d/1NqsJhT1TMfxWrWhaA9jafYDIJ5gpT3rS1UkIAOG4lP0/edit#).

Variables are associated to each animation and can be edited inside the **A_BattleAnimationBlueprint**. Navigate to **Event_Graph** and copy all the nodes and paste in the animation in the blueprint. Right click on the set variable nodes and create them. Illustration shown in 3.3.4 in [jRPG-Documentation](https://docs.google.com/document/d/1NqsJhT1TMfxWrWhaA9jafYDIJ5gpT3rS1UkIAOG4lP0/edit#). You will also need tod o the same for AnimGraph which is also illustrated in section 3.3.4.

## Customizing / Adding Items

## Changing Terrain

## References

[jRPG-Documentation](https://docs.google.com/document/d/1NqsJhT1TMfxWrWhaA9jafYDIJ5gpT3rS1UkIAOG4lP0/edit#)

## Back to main

[Main](README.md)