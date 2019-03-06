## Data Science in Apache Spark
### Census - SIPP Workbook
#### Report Building

**Level**: Easy
**Language**: Scala

**Requirements**: 
- [HDP 2.6.X]
- Spark 2.x

**Author**: Ian Brooks
**Follow** [LinkedIn - Ian Brooks PhD] (https://www.linkedin.com/in/ianrbrooksphd/)

![Census](https://yt3.ggpht.com/a-/AN66SAwtUzDFUsvm7MJszIS3ccgglaFGrw1_Ye16ew=s900-mo-c-c0xffffffff-rj-k-no "Census")


## Source File Description
Upload the source data file  [CFS 2012 csv] (https://www.census.gov/econ/cfs/pums.html) to HDFS in the /tmp directory 


##Column Descriptions 


## Pre-Run Instructions

### For HDP with Apache Zeppelin
1. Log into Apache Ambari 

2. In Ambari, select "Files View" and upload all of the CSV files to the /tmp/ directory.  For assistance, please use the following [tutorial.](https://fr.hortonworks.com/tutorial/loading-and-querying-data-with-hadoop/)

3. Upload the source data file  [CFS 2012 csv] (https://www.census.gov/econ/cfs/pums.html) to HDFS in the /tmp directory 

4. Upload helper files to the HDFS in the /tmp directory 
Upload all of the helper files to HDFS in the /tmp directory 

a. SIPP08A.csv

b. SIPP08B.csv

c. SIPP08C.csv

d. SIPP08D.csv

5. In Zeppelin, download the Zeppelin Note [JSON file.](https://github.com/BrooksIan/CensusSIPP) For assistance, please use the following [tutorial](https://hortonworks.com/tutorial/getting-started-with-apache-zeppelin/)

### For Cloudera Data Science Workbench
1. Log into CDSW and upload the project
2. Open a terminal on a session and run the loaddata.sh script 

## License
Unlike all other Apache projects which use Apache license, this project uses an advanced and modern license named The Star And Thank Author License (SATA). Please see the [LICENSE](LICENSE) file for more information.
