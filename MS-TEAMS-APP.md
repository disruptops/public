## DisruptOps Microsoft Teams App

DisruptOps users can integrate directly with Microsoft Teams for bi-directional security ChatOps. Once integrated, our Intelligent Cloud Security Alerts appear directly in the right channel, for the right team, pre-configured with enriched data and a dropdown of remediation actions. DisruptOps supports a wide range of configurations, including sending the same alert to multiple channels so security can keep an eye on everything while teams manage their own issues and incidents.

### Sideloading

The Teams app is not currently published to the Teams App Store The app can be sideloaded fairly easily ([sideloading instructions here](https://docs.microsoft.com/en-us/microsoftteams/platform/concepts/deploy-and-publish/apps-upload)) but does require access to the Teams ‘Apps Tab’.  Our app is downloadable [here](./msteams-DisruptOps.zip). This process takes about 30 minutes for someone with the correct Teams privileges.

### Initial Install

You Sideload an App by going into  "Apps" in MS Teams, scrolling down to the bottom of the menu on the left and selecting "Upload a custom app." If you are using the Teas App you will have the option to install for a team or for your organization. Upload the zip from the link in this document.

The app should now be installed to your Organization or an individual Team inside the Organization. You must then create a connector by selecting the "..." menu next to a channel, for example #notifications and selecting "Connectors". You can view Configured Connectors from the left or scroll all the way to the bottom to see the Sideloaded Connectors. Click the Configure button to set a new one up. The setup screen will ask you to log into the DisruptOps app, using your normal DisruptOps credentials, and will create the MSTeams recipient.
