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

#### Tasks

* [DEPL-6065] - Improve systemadministration manual regarding SSL configuration
* [DEPL-6084] - Update Overthere documentation for multiple domains
* [DEPL-6144] - Document how to change the default location of the work and repository folders
* [DEPL-6642] - Upgrade commons-fileupload to avoid security risks CVE-2013-0248, CVE-2014-0050
* [DEPL-6643] - Upgrade Jackrabbit to avoid security risk JCR-3630 XSS
* [DEPL-6644] - Upgrade Spring framework to avoid security risk CVE-2013-7315
* [DEPL-6646] - Upgrade Spring Security and Spring Security LDAP to avoid security risk CVE-2014-0097
* [DEPL-6647] - Remove antisamy and xerces to avoid security risk CVE-2009-2625
* [DEPL-6662] - Lock down Xstream configuration further (CVE-2013-7285)
* [DEPL-6716] - Remove jackrabbit webapp, server, webdav
* [DEPL-6741] - Rename the repository xl-release-download -> xl-trials-download
* [DEPL-6779] - Post a security announcement on the XebiaLabs forum
* [DEPL-6808] - Replace "planning-script" with "planning-script-path" in rule-demo-plugin and rules tutorial

