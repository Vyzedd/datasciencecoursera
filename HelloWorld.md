## This is a markdown file

##export JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_221.jdk/Contents/Home
export CONDA_HOME=/Users/harry/Library/Anaconda3/anaconda3

export PATH=$CONDA_HOME/bin:$JAVA_HOME/bin:$PATH

export SPARK_HOME=/Users/harry/spark-2.4.4-bin-hadoop2.7
export PYTHONPATH=$SPARK_HOME/python:$PYTHONPATH

export PYSPARK_PYTHON=$CONDA_HOME/bin/python3
export PATH=$PATH:$SPARK_HOME/bin:$SPARK_HOME/sbin

# export PYSPARK_DRIVER_PYTHON="jupyter"
# export PYSPARK_DRIVER_PYTHON_OPTS="notebook"
