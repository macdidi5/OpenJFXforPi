# OpenJFXforPi

Installation (Jessie):

    git clone git://github.com/macdidi5/OpenJFXforPi.git
    cd OpenJFXforPi
    export JAVA_HOME=/usr/lib/jvm/jdk-8-oracle-arm32-vfp-hflt
    sudo cp -v -r jre/lib $JAVA_HOME/jre/

Installation (Jessie Lite):

    sudo apt-get update
    sudo apt-get install libpango-1.0-0:armhf libpangoft2-1.0-0:armhf
    sudo apt-get install libgtk2.0-0
    git clone git://github.com/macdidi5/OpenJFXforPi.git
    cd OpenJFXforPi
    export JAVA_HOME=/usr/lib/jvm/jdk-8-oracle-arm32-vfp-hflt
    sudo cp -v -r jre/lib $JAVA_HOME/jre/
