# kaes's minecraft server
## How to join (first time setup mostly)
1. Download and install [Curseforge](https://www.curseforge.com/)

2. Download the modpack (zip file) from this repository

3. Open Curseforge, go to the Minecraft tab, and select "Create Custom Profile" in the top right corner

4. Then select "import a previously created profile" and import the zip file for the modpack (don't extract it)

5. Once it's installed, press play which will open the Minecraft launcher. **For optimal performance**, go to the installations tab and edit the installation, and paste the following text into the JVM arguments field:
	- `-Xmx4G -Xss4M -Dfile.encoding=GBK -XX:+AggressiveOpts -XX:+UseConcMarkSweepGC -XX:+UseParNewGC -XX:+CMSConcurrentMTEnabled -XX:ParallelGCThreads=8 -Dsun.rmi.dgc.server.gcInterval=1800000 -XX:+UnlockExperimentalVMOptions -XX:+ExplicitGCInvokesConcurrent -XX:MaxGCPauseMillis=50 -XX:+AlwaysPreTouch -XX:+UseStringDeduplication -Dfml.ignorePatchDiscrepancies=true -Dfml.ignoreInvalidMinecraftCertificates=true -XX:-OmitStackTraceInFastThrow -XX:+OptimizeStringConcat -XX:+UseAdaptiveGCBoundary -XX:NewRatio=3 -Dfml.readTimeout=90 -XX:+UseFastAccessorMethods -XX:CMSInitiatingOccupancyFraction=75 -XX:+CMSScavengeBeforeRemark -XX:+UseCMSInitiatingOccupancyOnly -verbose:gc`  

	- Note: the first argument `-Xmx4G` is for RAM allocation, so change the number if you want more/less RAM. 4G should be more than enough,
	- Also note: unfortunately CurseForge doesn't rember JVM args as far as I know, so you have to paste these in every time. However, if the default arguments give you good enough performance, you can just use those instead.
6. Once Minecraft has launched, connect to the server at **`artists-strongly.gl.joinmc.link`**

7. Lmk if anything breaks
