# openjdk-8-jdk_griggorii_build_ubuntu_20.04 , new gcc different linux to java javac , java -c | gc -c
openjdk-8-jdk , tarrbal , jdk-8 , build , ubuntu 20.04

Download : https://github.com/Griggorii/openjdk-8-jdk_griggorii_build_ubuntu_20.04/releases/tag/openjdk-8-jdk

$ sudo tar xvpf openjdk-8-jdk_griggorii_build.tar.xz -C /

$ sudo cp flavormap.properties /usr/lib/jvm/java-8-openjdk-amd64/jre/lib/

$ sudo ln -s /usr/lib/jvm/java-8-openjdk-amd64/bin/* /usr/bin

Not link ? check example not link policytool open /usr/lib/jvm/java-8-openjdk-amd64/bin

$ sudo ln -s /usr/lib/jvm/java-8-openjdk-amd64/bin/policytool /usr/bin

$ sudo nano /etc/environment

Add new string /etc/environment save java_home  

JAVA_HOME="/usr/lib/jvm/java-8-openjdk-amd64"

Reboot check 

$ echo $JAVA_HOME

+ good instrument https://github.com/pxb1988/dex2jar/releases

+ https://github.com/java-decompiler/jd-gui/releases/ deb install fix $ sudo nano '/opt/jd-gui/jd-gui.desktop' replace string 4) Exec=java -jar /opt/jd-gui/jd-gui.jar to fix ->  Exec=java -jarsudo nano d-gui/jd-gui-1.6.6-min.jar

Только настоящие технологии ни каких выдуманных паразитирующих дистрибутивов support real technology investments and donate griggorii@gmail.com

Alternative property modifications java https://github.com/Griggorii/java-8-oracle_linux_modification_engine_by_Griggorii
