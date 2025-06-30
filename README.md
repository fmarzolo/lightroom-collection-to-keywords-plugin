# lightroom-collection-to-keywords-plugin
Allows to convert Lightroom collections in Keywords to make it more easy integration with external editing programs that do not manage collections

# Collection To Keywords Lightroom Plugin

A simple but powerful plugin for Adobe Lightroom Classic designed to synchronize a photo's collection structure directly into its keywords.

This tool helps maintain a parallel organization system between collections and keywords, making it easier to find and manage photos using Smart Collections, keyword filters, or external applications that read metadata.

## Key Features

*   **Selected Photos Only**: The plugin operates exclusively on the photos you have selected in the Library module, giving you full control over what gets updated.
*   **Context Menu Integration**: For a fast workflow, the command is available directly in the right-click context menu. No need to navigate through main menus.
*   **Hierarchical Keywords**: Automatically generates a full, hierarchical keyword based on the collection's path. For example, a photo in the collection "Portraits > Family > 2024" will get the keyword `col_Portraits/Family/2024`.
*   **Smart Cleanup**: Before adding the new keywords, the plugin automatically removes any pre-existing keywords that start with the `col_` prefix. This ensures that a photo's keywords always reflect its current collections and don't retain old ones if the photo is moved.
*   **Confirmation Dialog**: A confirmation prompt appears before any changes are made, showing how many photos will be affected and preventing accidental runs.

## How to Use

1.  In the **Library** module, select one or more photos whose keywords you want to update.
2.  **Right-click** on any of the selected photos.
3.  From the context menu that appears, choose the **"Sync Collections to Keywords"** option.
4.  A dialog box will ask for confirmation. Click **"Proceed"** to start the process.
5.  A progress bar will appear, and once finished, the keywords of the selected photos will be updated.

## Installation

1.  Download the zipped plugin folder, `CollectionToKeywords.lrplugin.zip`, and unzip it. You should have a folder named `CollectionToKeywords.lrplugin`.
2.  Open Adobe Lightroom Classic.
3.  Navigate to `File > Plug-in Manager...`.
4.  Click the **"Add"** button in the bottom-left corner of the window.
5.  Browse to the location where you unzipped the folder, select the `CollectionToKeywords.lrplugin` folder, and click **"Select Folder"**.
6.  Ensure the plugin is enabled (it should have a green light next to its name). Click **"Done"**.

The plugin is now installed and ready to use.

## Author

*   **fmarzolo**
