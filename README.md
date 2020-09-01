# PYSPARK TUTORIAL
> Comparison of SQL and PySpark code.


## Tutorials

The tutorial examples are available to view in the Jupyter Notebooks in this repository.  You can view them directly through GitHub by selecting the `*.ipynb` files.


## Installation for Local Execution

If you wish to run the examples on your own PC, you will need to have [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or Anaconda Python installed on your machine.

The environment needed for the demonstration can be installed with the following command:

```bash
git clone https://github.com/m-matthews/pyspark-tutorial.git
cd pyspark-tutorial
conda env create -f environment.yml
conda activate pysparktut
```


## Running the Tutorials

The tutorials can then be executed by starting the [Jupyter Notebook](https://jupyter.org/), and opening the tutorial files from there:

```bash
cd pyspark-tutorial
conda activate pysparktut
jupyter notebook
```


## Reference

The following links are useful references within the PySpark documentation:

* [PySpark Data Types](https://spark.apache.org/docs/latest/api/python/pyspark.sql.html#module-pyspark.sql.types)
* [PySpark DataFrame](https://spark.apache.org/docs/latest/api/python/pyspark.sql.html#pyspark.sql.DataFrame)
* [PySpark Functions](https://spark.apache.org/docs/latest/api/python/pyspark.sql.html#module-pyspark.sql.functions)
* [PySpark Window Functionality](https://spark.apache.org/docs/latest/api/python/pyspark.sql.html#pyspark.sql.Window)
* [PySpark Join Functionality](https://spark.apache.org/docs/latest/api/python/pyspark.sql.html#pyspark.sql.DataFrame.join)
