# kaes's minecraft server
## How to join (first time setup mostly)
1. Download the modpack (zip file) from this repository (click on it, then click "Raw" to download)

2. To run the pack, you can either use the [Curseforge](https://www.curseforge.com/) mod manager or simply extract the zip file somewhere and add the folder as a new installation in your regular Minecraft launcher.

5. Once it's installed, press play on Curseforge or select the modpack on the Minecraft launcher. **For optimal performance**, go to the installations tab, edit the installation, and paste the following text into the JVM arguments field (or in Curseforge settings):
	- `-Xmx4G -Xss4M -Dfile.encoding=GBK -XX:+AggressiveOpts -XX:+UseConcMarkSweepGC -XX:+UseParNewGC -XX:+CMSConcurrentMTEnabled -XX:ParallelGCThreads=8 -Dsun.rmi.dgc.server.gcInterval=1800000 -XX:+UnlockExperimentalVMOptions -XX:+ExplicitGCInvokesConcurrent -XX:MaxGCPauseMillis=50 -XX:+AlwaysPreTouch -XX:+UseStringDeduplication -Dfml.ignorePatchDiscrepancies=true -Dfml.ignoreInvalidMinecraftCertificates=true -XX:-OmitStackTraceInFastThrow -XX:+OptimizeStringConcat -XX:+UseAdaptiveGCBoundary -XX:NewRatio=3 -Dfml.readTimeout=90 -XX:+UseFastAccessorMethods -XX:CMSInitiatingOccupancyFraction=75 -XX:+CMSScavengeBeforeRemark -XX:+UseCMSInitiatingOccupancyOnly -verbose:gc`  

	- Note: the first argument `-Xmx4G` is for RAM allocation, so change the number if you want more/less RAM. 4G should be more than enough.
6. Once Minecraft has launched, connect to the server at **`artists-strongly.gl.joinmc.link`**

7. Lmk if anything breaks
