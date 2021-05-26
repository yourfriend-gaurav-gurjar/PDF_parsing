# EC2 - Linux Machine based PDF Parsing Workflow
## Architecture
![Image of Architecture](https://github.com/yourfriend-gaurav-gurjar/musical-broccoli/blob/main/EC2%20-%20Linux%20Machine.png)
<img src="[https://github.com/yourfriend-gaurav-gurjar/musical-broccoli/blob/main/EC2%20-%20Linux%20Machine.png.jpg](https://github.com/yourfriend-gaurav-gurjar/musical-broccoli/blob/main/EC2%20-%20Linux%20Machine.png)" width="200"/>

## Python Script


### Data Reading and Wrangling

- camelot library usage - [conda/pip]() env

	- [PDF - Table Parsing](https://camelot-py.readthedocs.io/en/master/user/quickstart.html#read-the-pdf)

- Merging dataframes
- trimming and creating required cols

### Data Input/Output

- CSV file folder

## System Setup

### Python Script - Main Dependencies

- camelot's parents

	- [Ghostscript](https://www.ghostscript.com/)
	- [Tkinter](https://docs.python.org/3/library/tkinter.html)

### pip/conda environment

- [camelot-py[all]](https://camelot-py.readthedocs.io/en/master/)
- [awscli](https://pypi.org/project/awscli/)
- [pandas](https://pandas.pydata.org/)

### Python Script - Table Parsing Dependencies

- [camelot-py[all]](https://camelot-py.readthedocs.io/en/master/)

### AWS credentials - config file

## S3 Buckets
### Raw Data
- cannaspyglass-datalake-raw
### Processed Data
- cannaspyglass-datalake-processed-dev
