You can install maven on windows and Linux
Maven installation in Centos 7 & 8 and RHEL 7 & 8
-------------------------------------------------------------------------------------------------------------------------
1. JAVA -  Pre Requisite Software  and Git for code download
-----------------------------
# Become root and cd /opt  (sudo su && cd /opt)

sudo su – 
cd /opt

yum install wget nano tree unzip git-all -y

yum install java-11-openjdk-devel java-1.8.0-openjdk-devel -y
java -version
git -version

2. Install Maven.sh
------------------
Step1) Download the Maven Software

wget http://apachemirror.wuchna.com/maven/maven-3/3.6.3/binaries/apache-maven-3.6.3-bin.zip
unzip apache-maven-3.6.3-bin.zip 
rm -rf apache-maven-3.6.3-bin.zip
mv apache-maven-3.6.3/ maven

Step3) Set Environmental Variable  -  For Specific User
----------------------
vi ~/.bash_profile
export M2_HOME=/opt/maven
export PATH=$PATH:$M2_HOME/bin
or
Step3b) Set Environmental Variable  For All Users
---------------------- 
vi /etc/profile
export M2_HOME=/opt/maven
export PATH = $PATH:$M2_HOME/bin

step4) Activate the maven home and mvn by running the below scripts
source ~/.bash_profile
source /etc/profile

Step5) Check the Maven version
mvn -version
END OF INSTALLATION.
