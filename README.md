# Dynamic-Data-Ingestion-and-Storage-in-HDFS-with-Automated-Hive-Integration

The task aims to fetch data from a specified link, store it in HDFS, and create a Hive table to visualize the data. Initially, ensuring access to the provided link and successful data retrieval is essential. Subsequently, determining the data format and schema, if structured, is pivotal. Utilizing tools like wget or curl for data retrieval and HDFS CLI for storage follows. Finally, creating a Hive table, loading data, and verifying correctness conclude the task, with an optional script for automation.


Tools used : API, HDFS, Hive, Shell scripting, wget


Basic Workflow :
> The Shell script file (elt.sh) is dependent on the url.txt and queries.hql files.
> Once the shell script file has been executed the required files provided in the url.txt file will be donwloaded.
> Once downloaded, the files will be loaded into the HDFS for storage.
> Then the queries.hql file will be executed to create a database and required table to load the data from HDFS.

Caution

Note :

Make sure you've provided executable permission for the required files before executing.
chmod +x filename.extension
Run only the Shell Script file - elt.sh
