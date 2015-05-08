#Install Web Service into DP2

The web service uses Jersey framework

##Steps
* yum install git -y
* Download maven
* tar xvf apache-maven-3.3.3-bin.tar.gz
* set up http proxy by changing ~/.m2/settings.xml
* Download Cloudfoundry
* tar xvf cf-linux-amd64.tgz
* ~/maven/bin/mvn package
* ~/cf api  http://api.demo-gotapaas.com
* ~/cf login
* ~/cf push
