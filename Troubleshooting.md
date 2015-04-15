## General Tips
Things to try if your app doesn't seem to be working. (For issues installing or running the AltspaceVR Client, see the [AltspaceVR Troubleshooting Guide].)

1. **RTFM**
   * Reading this entire wiki will take most developers less than 10 minutes
   * (fewer than 3,000 words at the average adult reading speed of 300 wpm)

2. **Refresh** the Altspace Browser.
   * The required Prepros tool (see [[Workflow]]) should automatically trigger a reload when it detects a change in your source code files. If this isn't happening, try restarting the Prepros application.
    * You can also reload your app manually by clicking the refresh button on the Altspace Browser GUI, or by entering "location.reload(true)" -- true to force reload from the server, not the cache -- into the Coherent Debugger console.

3. Check the Coherent Debugger **browser console log**.
    * Just like in a traditional browser, the console log shows errors thrown by your web app, as well as any console.log messages that you specify.  This is the primary tool for debugging Altspace Web Apps.

4. Check the Altspace **client output log**, a file on your computer at the path below:
    * Windows: c:\Users\MyUsername\AppData\Local\AltspaceVR\AltspaceVR_Data\output_log
    * Mac: TBD

[AltspaceVR Troubleshooting Guide]: https://altvr.zendesk.com
