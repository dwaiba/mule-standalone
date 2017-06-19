# mule-standalone 3.8.1
Standalone Docker File automated build @ https://hub.docker.com/r/dwaiba/mule-standalone/builds/

mkdir ~/apps ~/conf ~/domains ~/logs && chmod -R 755 ~/apps ~/conf ~/domains ~/logs  && docker run -dti -p 8081:8081 --name=mulestandalone --restart=always -v ~/apps:/opt/mule/apps -v ~/conf:/opt/mule/conf -v ~/domains:/opt/mule/domains -v ~/logs:/opt/mule/logs dwaiba/mule-standalone
