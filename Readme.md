# Pirple Data Mining With Python
* Assignment #1: Setup Your Workstation. **Homework1.ipynb**
```bash
> pip3 install jupyterlab
> pip3 install pandas
> pip3 install sns
> python3 -m pip install seaborn
> jupyter notebook --ip 127.0.0.1 # Start NoteBook command line, access via browser.
```
* Assignment #2: Correlation. **Homework2.ipynb**
```bash
> python3 -m pip install sklearn
```
* Assignment #3: Framework Apache Spark. **Homework3.ipynb**
```bash
> sudo apt install default-jdk scala git -y #install
> java -version; javac -version; scala -version; git --version #check installation
> wget https://downloads.apache.org/spark/spark-3.0.0/spark-3.0.0-bin-hadoop2.7.tgz
> tar xvf spark-*
> sudo mv spark-3.0.0-bin-hadoop2.7 /opt/spark
> echo "export SPARK_HOME=/opt/spark" >> ~/.profile
> echo "export PATH=$PATH:$SPARK_HOME/bin:$SPARK_HOME/sbin" >> ~/.profile
> echo "export PYSPARK_PYTHON=/usr/bin/python3" >> ~/.profile
> source ~/.profile
# create jupyter.sh file to start jupyter + spark
```
* Assignment #4: Map and Flatmap. **Homework4.ipynb**
```bash
python3 -m pip install pyspark --no-cache-dir #Install without cache Dir and avoid MemoryError.
```
* Project #1: Spark-ML. **Project1.ipynb**
* Assignment #5: Matrices. **Homework5.ipynb**
* Assignment #6: SQL Databases. **Homework6-SQL Databases.ipynb**