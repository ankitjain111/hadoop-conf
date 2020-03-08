# hadoop-conf
Hadoop configuration files for spark on windows

# Hadoop configuration files are needed on windows system for spark to properly work.
# Config steps:
 1) Add the hadoop folder having all the required files in C:\
 2) It will have hadoop/bin folder which have all the files.
 3) Update the system variables.
     This PC -> Settings -> Advance system settings -> Environment Variables
     1) add a new user variable : HADOOP_HOME as C:\hadoop\
     2) Edit the path variable and add this path to it : C:\hadoop\bin
