# Extension for IBM WebSphere Portal - New Mode

# Description
The Extension for IBM WebSphere Portal - New Mode is a Java extension that migrates the CA APM for IBM WebSphere Portal or the PowerPack for IBM WebSphere Portal agent from legacy mode (prior to CA APM 9.1) to new mode.

No features were added or removed.

# Short Description
The Extension for IBM WebSphere Portal - New Mode is a Java extension that migrates the CA APM for IBM WebSphere Portal or the PowerPack for IBM WebSphere Portal agent from legacy mode to new mode.

# APM version
Should work in new mode for any CA APM Java Agent 9.1 and later. Tested with CA APM 9.7.

# Dependencies
CA APM Java Agent 9.1 and later, only in new mode.

# Supported Third Party Versions
This extension was tested with IBM WebSphere Portal v8 and works with all CA APM Java Agent-supported IBM WebSphere Portal versions.

# Limitations
This extension is known to cause issues with IBM WebSphere Portal v9. We are working on certifying the extension for IBM WebSphere Portal v9.

# License
[Eclipse Public License](LICENSE)

# Prequisite
Installed CA APM for IBM WebSphere Portal or PowerPack for IBM WebSphere Portal.

* See version 9.1 to 9.5 documentation on [CA Support.](https://support.ca.com)
* See version 9.6 to 10.2 documentation on [the CA APM documentation wiki.](https://docops.ca.com)

# Install the Extension for IBM WebSphere Portal - New Mode

## Install Using CA APM Control Center

### 10.5

1. Download the bundle (extension) from [GitHub] (https://github.com/CA-APM/WebSpherePortal/releases).
2. Go to the Bundles page and click the **Import** button.
2. Navigate to the downloaded bundle and click **Open**.
3. On the Packages page, add the bundle to the desired package.

### 10.2 and 10.3

1. Download the extension (bundle) from the [GitHub.] (https://github.com/CA-APM/WebSpherePortal/releases)
2. Navigate to the downloaded bundle.
3. Copy the bundle to the <APMCommandCenterServer>/import directory.
   The bundle is automatically imported into the APM Command Center database and moved to the bundles directory.

## Install Manually

### 10.5 and later

1. Download the extension from the [GitHub.] (https://github.com/CA-APM/WebSpherePortal/releases)
2. Navigate to the downloaded extension.
3. Copy the .tar file to the <*Agent_Home*>/extensions/deploy directory.
   The agent automatically automatically installs and deploys the extension, which starts monitoring the managed application.

### 10.3 and earlier

1. Download the extension from the [GitHub.] (https://github.com/CA-APM/WebSpherePortal/releases)
2. Navigate to the downloaded extension and unzip or untar the file as appropriate into the <*Agent_Home*> directory.
3. Copy the extension jar file to the <*Agent_Home*>/core/ext directory.
4. Copy the .pbd or pbl files to the <*Agent_Home*>/core/config directory.
5. Update the IntroscopeAgent.profile file
   * Navigate to <*Agent_Home*>/core/config to update the IntroscopeAgent.profile file.
   * Add the .pbl files to the directives in the IntroscopeAgent.profile.

# Support URL
https://support.ca.com

# Product Compatibility Matrix
http://pcm.ca.com/

# Categories
Applications Portal

# Change Log
Changes for each extension version.

Version | Author | Comment
--------|--------|--------
1.0 | CA Technologies, A Broadcom Company | First version of the extension.
