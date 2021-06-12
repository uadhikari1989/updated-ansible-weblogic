1. Please Place the weblogic 12.2.1.3_wls jar file under roles/setup-weblogic-standalone/files/

2. Also Place the JDK Binaries (In this case it's server-jre-8u191-linux-x64.tar.gz) under roles/setup-weblogic-standalone/files/

3. If you are deploying the application, all those jar/ear/war file needs to be placed under roles/app-deployment/files/

4. Whatever the earfile you placed under #3, needs to be updated under roles/app-deployment/files/deployment_config.txt.

5. There might be minor here and there.. but hopefully it won't be that tough to find out though. 

Good Luck on setting up the environment.
