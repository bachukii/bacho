# საველე აზომვა — APK v163

The application UI is bundled in the APK. It does not load its application code from Netlify. Default GPS correction: Easting -0.340 m, Northing -0.237 m. Existing correction settings are reset once on first launch of this version. Map layers and cloud functions require an internet connection and use the existing Netlify proxy.

Build: open Actions > Build APK > Run workflow. Download savele-azomva-v163-apk from the successful workflow artifacts, extract it, and install app-debug.apk.

This is a debug build. If Android rejects an update because the signing key differs from an existing installation, export existing local projects before uninstalling the old app. Native GNSS hardware behavior must be verified on the device.
