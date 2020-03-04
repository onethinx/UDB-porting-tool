# UDB-porting-tool
UDB porting tool: export the UDB configuration from PSoC Creator to VS Code or ModusToolbox

## Use of the tool
Use is easy, load the PSoC Creator project (.cyprj) and export the UDB config to your source folder of the VS Code or ModusToolbox project.

## Use inside your project
Include the header file into your project (#include "UDBinit.h") and call the UDB configuration setup at the beginning of your main code: `UDBInit();`
