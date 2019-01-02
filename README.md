# DataView Demo Levure Project

This repo contains a Levure application which demonstrates how to use the DataView and DataView Tree helpers. If you are checking this repo out with git on your local computer make sure you initialize submodules. Levure, DataView helper, and DataView Tree helper are all submodules.

To open the application, launch LiveCode and open the `./app/standalone.livecode` stack file, switch to the Browse tool, and click on the **Open Application** button.

Levure: https://github.com/trevordevore/levure

DataView helper: https://github.com/trevordevore/levurehelper-dataview

DataView Tree helper: https://github.com/trevordevore/levurehelper-dataview-tree

Requirements: Tested with LiveCode 9.

## DataView Example

The DataView example displays all of the extensions installed in the LiveCode IDE as returned by the function `revIDEExtensions()`. Each row lists the extension name, version, and author. Double-clicking on a row will reveal the folder where the extension is installed.

You will find the row templates used in the DataView in the `./app/templates/dataview templates` folder.

## DataView Tree Example

The DataVie Tree example creates a tree UI based on a folder you select on your computer. The UI allows you to expand the contents of any folders listed. Double-clicking on a file or folder will open it.

You can right-click on a file or folder and rename it using the contextual menu. The file/folder will not actually be renamed but an answer dialog will appear showing you what the new name would be.

You will find the row templates used in the DataView in the `./app/templates/dataview tree templates` folder.
