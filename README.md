# Map Reducer in Python using Mrjob
This project contains two files **'1901'** and **'1902'**, each containing 2500+ rows of climate data. The aim of this project is to process this data and extract the specific wind direction and its corresponding minimum and maximum temperature, as well as the number of counts for that wind direction appearing in the data.

## Getting Started
To run this project, you will need to have Python installed on your machine, as well as the Mrjob package. You can install Mrjob by running the following command in your terminal:
```
pip install mrjob
```
##Usage
Clone this repository to your local machine.
Open **'map_reducer_mrjob.ipynb'** in Jupyter Notebook or any other Python IDE.
Run the cells in the notebook to generate the map reduce function in **'detail_temperature.py'**.
In your terminal, navigate to the directory where the files **'1901'** and **'1902'** are located.
To run the map reduce job, enter the following command:
```
python detail_temperature.py 1901 1902 > output.txt
#This will output the results to **'output.txt'**.
```

## Contributing
If you wish to contribute to this project, please fork the repository and create a pull request with your changes.

## License
This project is licensed under the MIT License. See the **'LICENSE'** file for details.

## Contact
For any questions or suggestions, please feel free to contact me at thapaprashant69@gmail.com.