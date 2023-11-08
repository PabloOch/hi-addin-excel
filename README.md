
<img width="1156" alt="screenshot" src="https://user-images.githubusercontent.com/3375461/27309424-87a21b06-5508-11e7-91c6-c9468efdbad0.png">

## How to run

1. To run the add-in, you need side-load the add-in within the Excel application. The section below describes the way of side-loading of manifest file in different platforms.

    - On Windows, follow [this tutorial](https://dev.office.com/docs/add-ins/testing/create-a-network-shared-folder-catalog-for-task-pane-and-content-add-ins).

    - On macOS, move the manifest file `office-add-in-react-manifest.xml` to the folder `/Users/{username}/Library/Containers/com.microsoft.Excel/Data/Documents/wef` (if not exist, create one)

    - For Excel Online, use the upload my add-in button from the add-in command dialog to upload the manifest file. 

2. Run this in the terminal for a dev server.

    - Windows
    
        ```bash
        set HTTPS=true&&npm start
        ```
    
    -  macOS
    
        ```bash
        HTTPS=true npm start
        ```
