# binaries
Contains binaries for 3.11.4

THe folder has a multipart zip file to be unzipped. Steps to install is given below.



#Installation Instructions: 

/**
* This is a windows installation. But will not differ much except the syntax.
* This is a free Apache distribution 3.11.4 
*
**/

1. Unzip the binary into a folder. (Say C:/cassandra3.11.4)
2. Set the JDK environment. First will be Java jdk path 
      JAVA_HOME = C:\Users\1611067\Accelerator\Java\jdk 1.8
3. Set the cassandra home environment. First will be Java jdk path 
      CASSANDRA_HOME = C:\Users\1611067\Accelerator\Cassandra\apache-cassandra-3.11.4
4. Install the python 2.7.13
        - Unzip the portable versoin which is attached in the github /binaries/python2.7.13
        - Add bin path to the %PATH%. Open enviornment viarable and add  
              For example, if you extracted the files into program data folder then
               SET PATH = %PATH%;C:\ProgramData\Python-2.7.13.1\python-2.7.13.amd64
        - Confirm that the python CLI is working. Open cmd from any location newly and type the below command. It should show 2.7.13
                :/>  python --version
5. You will now be able to start the CASSANDRA instance in standalone single node.
                goto the cassandra BIN folder and enter
                :/> cassandra.bat
                Confirm at the end the starting of the cassandra node in standalone mode.
6. You can now even start the CQL CLI for cassandra. 
                - Open a new CMD shell
                - Goto the bin location of the cassandra
                - type command :/> cqlsh.bat
