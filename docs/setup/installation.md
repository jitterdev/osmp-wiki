# Setup

## Installation with unsup
=== "MultiMC-based launchers"
    * Click the "Add Instance" button in the top-left corner of the launcher window.
    * Choose version 1.20.1 of Minecraft, and select the "Fabric" mod loader, then click OK to create the instance.
    * Click on your newly created instance, then click "Edit" on the right side of the window.
    * In the newly opened window, click "Open .minecraft" on the right.
    * Download the latest version of unsup [unsup 0.2.3](https://git.sleeping.town/unascribed/unsup/releases/download/v0.2.3/unsup-0.2.3.jar) and place the downloaded file in the .minecraft folder you opened.
    !!! warning
        Make sure the file's name is `unsup-0.2.3`. If you have file extensions turned on, this should instead be `unsup-0.2.3.jar`.
    * Download the config for unsup [unsup.ini](https://github.com/jitterdev/osmp/releases/download/unsup/unsup.ini) and place the downloaded file in the .minecraft folder you opened.
    !!! warning
        Make sure the file's name is `unsup`. If you have file extensions turned on, this should instead be `unsup.ini`.
    * Close the .minecraft folder and navigate back to the instance settings window. In that window, click "Settings" on the left, then tick the "Java arguments" box. In the text box below it, add `-javaagent:unsup-0.2.3.jar` to the end.
    !!! warning
        Make sure the `-javaagent:unsup-0.2.3.jar` you add to your Java arguments has a space inbetween it and the last argument in the text box; like such: `-XX:ConcGCThreads=8 -javaagent:unsup-0.2.3.jar`

=== "Modrinth App"
    tbw

=== "ATLauncher"
    tbw

=== "CurseForge"
    * Click the "Create Custom Profile" button in the top-middle of the launcher window.
    * Choose version 1.20.1 of Minecraft, and select the "Fabric" mod loader, then click Create to create the instance.
    * Right click on your newly created instance, then click "Open Folder" in the opened dropdown.
    * Download the latest version of unsup [unsup 0.2.3](https://git.sleeping.town/unascribed/unsup/releases/download/v0.2.3/unsup-0.2.3.jar) and place the downloaded file in the .minecraft folder you opened.
    !!! warning
        Make sure the file's name is `unsup-0.2.3`. If you have file extensions turned on, this should instead be `unsup-0.2.3.jar`.
    * Download the config for unsup [unsup.ini](https://github.com/jitterdev/osmp/releases/download/unsup/unsup.ini) and place the downloaded file in the .minecraft folder you opened.
    !!! warning
        Make sure the file's name is `unsup`. If you have file extensions turned on, this should instead be `unsup.ini`.
    * Close the .minecraft folder and navigate back to the main launcher window. Click "Play" on your newly created instance.
    * Once the Minecraft launcher opens with the profile, navigate to "Installations", then to the instance you created. Click the three dots on the right, then click "Edit".
    * Click the "More Options" dropdown, and in the "JVM Arguments" text box, add `-javaagent:unsup-0.2.3.jar` to the end.
    !!! warning
        Make sure the `-javaagent:unsup-0.2.3.jar` you add to your Java arguments has a space inbetween it and the last argument in the text box; like such: `-XX:ConcGCThreads=8 -javaagent:unsup-0.2.3.jar`

=== "Vanilla Launcher"
    !!! danger
        This launcher is not recommended. The Vanilla Launcher does not have separation of instances, and you will most likely experience conflicts when trying to use other profiles. Consider switching to one of the other launchers listed above.
