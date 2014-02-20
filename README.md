remove openJDK and install Oracle JDK7 
======================================
check java version
======================================
java -version

remove openJDK
======================================
sudo apt-get remove openjdk-6-jre-headless

install Oracle JDK7
======================================
sudo add-apt-repository ppa:webupd8team/java

sudo apt-get update

sudo apt-get install oracle-java7-installer

check java version again
======================================
java -version

java version "1.7.0_51"                                 
Java(TM) SE Runtime Environment (build 1.7.0_51-bl3)    
Java HotSpot(TM) Client VM (build 24.51-b03, mixed mode)
