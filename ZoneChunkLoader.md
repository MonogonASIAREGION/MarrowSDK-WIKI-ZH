# <img src="./Images/zone-icon.png" valign="middle" style="padding-bottom: 4px"> Zone Chunk Loader

<img src="./Images/icon_marrow_video.png" valign="middle" style="margin: 0px 5px 5px 0px"/> <a href="https://www.youtube.com/watch?v=u9z4fNoYrY0"><font size="5">Scene Chunks Tutorial Video</font></a> 

## Scene Chunks and Linked Zones with Zone Chunk Loader Components

<b>Zone Chunk Loaders</b> define what Scene Chunks should be loaded whenever the current Zone is active.  Populating this list with Scene Chunks that would be in the player's <b>line of sight</b> ensures that neighboring scenes get loaded so that geometry and entities do not seem to suddenly pop in or out of existence.  Be sure to include the current/self chunk in the list!

The Zone Chunk Loader connects the Zone Link with the Scene Chunk(s) and the scene contents that should be active while the current Zone is active.  Careful Zone linking and configuring the Zone Chunk Loader's "Chunks" list based off of <b>line of sight</b> ensures that the current and surrounding scene chunks are loaded in a way that hides any sudden popping in or disappearing of geometry and entities.

You can quickly add to or overwrite the Zone Chunk Loader's Scene Chunk list by selecting the Zone Chunk Loaders that you want to modify and then locking the inspector.  Next, Use CTRL-click to add Scene Chunks to the current selection.  Clicking the "Add Selected SceneChunks" button will add any selected Scene Chunks to the Zone Chunk Loader's Scene Chunk List.  Clicking the Overwrite button will replace the "Chunks" list of the selected Zone Chunk Loaders with the selected Scene Chunks.