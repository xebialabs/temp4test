#### Bug fixes

* [DEPL-6676] - No error message is shown in the GUI if an error occurs in an orchestrator
* [DEPL-6687] - Password properties are not obfuscated when previewing an os-script step
* [DEPL-6691] - GUI does not work with debug version of Flash player
* [DEPL-6692] - Cannot access a synthetic property of kind SET_OF_CI or SET_OF_STRING in a Jython planning script
* [DEPL-6701] - NoSuchElementException when upgrading a composite package
* [DEPL-6702] - Cannot close permissions tab
* [DEPL-6707] - $deployed.file does not work in FreeMarker templates
* [DEPL-6711] - NullPointerExpression when pressing the Tab key on the username or password prompt in the CLI
* [DEPL-6724] - Cannot retry a failed upload. template, delete or os-script step
* [DEPL-6740] - Cannot retry a failed jython or os-script step after restarting the XLD server
* [DEPL-6748] - Temporary folders in the work directory are not deleted when using the plan analyzer
* [DEPL-6764] - Remote-booter does not fill default values for properties
* [DEPL-6781] - SSL keystore passwords are not migrated properly from pre-4.5.0 versions

#### Improvements

* [DEPL-6419] - Deprecate targetFileName property of file.Folder type
* [DEPL-6634] - Make property previousDeployedApplication point to previous deployed in generic-plugin

