Install Web servie into DP2

yum install git -y
Download maven
tar xvf apache-maven-3.3.3-bin.tar.gz
settup http proxy by changing ~/.m2/settings.xml
Ddownload Cloudfoundry
tar xvf cf-linux-amd64.tgz
~/maven/bin/mvn package

~/cf api  http://api.demo-gotapaas.com
~/cf login
~/cf push
