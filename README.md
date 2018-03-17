# JsonData 

Scripting tool for Tabletop Simulator.

JsonData is a tool for exporting and importing information about in-game objects in JSON-format. JsonData works with Notebook tabs for all actions. All needed tabs would created automatically. Exporting and importing processes use tab "json.data" for saving or getting information in JSON-format. Before every importing and exporting JsonData would save backup to tabs with prefix "json.exp.backup" and "json.imp.backup". Export and import configuration is saved in tab "json.conf". Before every import and export configuration would be read from this tab.

Note: sometimes Tabletop Simulator incorrectly works with Notebook tabs. If you did not see any data in created tabs try to remove all tabs and then run Export or Import again.

## Using

Subscribe to JsonData at Steam Workshop:

https://steamcommunity.com/sharedfiles/filedetails/?id=1332014467

Load Tabletop Simulator, select Workshop section and load JsonData. 
Click on JsonData with right button and select "Save object". Load any other 
game and move JsonData to table from "Saved objects" panel.

## Issue tracking

The issues for this project are tracked on its github.com page. All bug reports and feature requests are appreciated. 

## Contributions

Contributions are welcome, but there are no guarantees that they are accepted as such. Process for contributing is the following:
- Fork this project
- Create an issue to this project about the contribution (bug or feature) if there is no such issue about it already. Try to keep the scope minimal.
- Develop and test the fix or functionality carefully. Only include minimum amount of code needed to fix the issue.
- Refer to the fixed issue in commit
- Send a pull request for the original project
- Comment on the original issue that you have implemented a fix for it

## License & Author

JsonData is distributed under Apache License 2.0. For license terms, see LICENSE.

JsonData is written by David E. Veliev.
