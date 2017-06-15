#step1_install gradle on Ubutu 16.10

     sudo apt-get update
     sudo apt-get -y upgrade


#step2_install JDK8
      sudo apt-get -y install openjdk-8-jdk wget unzip
      java -version

#step3_download gradle
      wget https://services.gradle.org/distributions/gradle-3.4.1-bin.zip

#step4_install gradle
     sudo mkdir /opt/gradle
     sudo unzip -d /opt.gradle gradle-3.4.1-bin.zip
#configure the PATH envitonment variable so that the gradle executable can be directly executed anywhere on the system
     export PATH=$PATH:/opt/gradle/gadle-3.4.1/bin

# run the following command to check if the Gradle install was succesful
     gradle -v
