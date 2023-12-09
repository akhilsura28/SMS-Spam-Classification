## SMS-Spam-Classification

Setup
1. Install the default Java version for ubuntu

        sudo apt-get update
        sudo apt-get upgrade
        sudo apt-get 
        sudo apt install default-jre

2. Set Environmnet Variables
    Find where Java is installed

        which java

   This should be a folder like the following...

        /usr/lib/jvm/java-11-openjdk-amd64

   Update the file /etc/environment

        sudo nano /etc/environment

   Add the line (note: the path should match the output from which java)

        JAVA_HOME="/usr/lib/jvm/java-11-openjdk-amd64"

   
4. Install PySpark

        conda install -c conda-forge pyspark

5. Install sparkmagic

        pip install sparksql-magic

6. Check the following files, and remove any JAVA_HOME variable, or any mention of Java in the $PATH variable.

        /home/student/.bashrc
        /home/student/.profile
        /etc/environment

   
