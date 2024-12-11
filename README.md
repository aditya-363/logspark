# logspark
Log processing tool using Apache spark, uses EDGAR logs from 2017.
https://www.sec.gov/data-research/sec-markets-data/edgar-log-file-data-sets

<hr>
Usage instructions:
This was intended to be used in a Google DataProc environment, but may work with local environments.
<ul>
  <li>Install dependencies: Dash, pandas and pyspark <br> !pip install dash<br>!pip install pandas<br>!pip install pyspark</li>
  <li>Place log file in root of HDFS as used in the .ipynb file. If not, change the value of datafile variable accordingly.</li>
  <li>Run the Jupyter notebook, and visit the corresponding Dash link when the app launches</li>
</ul>

Additional information for executing on DataProc:<br>
You may need to forward port 8050 from DataProc over SSH to your local machine to be able to access the dashboard. 
