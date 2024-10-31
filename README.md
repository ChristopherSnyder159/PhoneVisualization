# PhoneVisualization
This program is using data visualization in python for CSV files. The CSV file in this program is phone information. 

![image](https://github.com/user-attachments/assets/39fabcf0-a51c-4e76-9686-ba9f2e22c306)

## Installation 
This program was written in [Visual Studio Code](https://code.visualstudio.com/download) with the Python add on. In a new terminal, you will have to type and enter these commands: 
```bash
pip install matplotlib
pip install pandas
pip install numpy
```
You will also have to download the CSV file provided. 

## Usage

```python
import matplotlib.pyplot as plt
import pandas as pd 
import numpy as np

plt.style.use('bmh')
df = pd.read_csv(' #you will have to copy the path of the CSV file from your downloads. Use forward slashes since python cannot recognize backward slashes # pricesnew.csv')

x = df['Model']
y = df['Price($)']
plt.bar(x, y)
plt.show()
```

An example file path could look like this 'C:/Users/ExampleName/Downloads/pricesnew.csv'
When run, a figure window will pop up with the graph. This is just a simple graph of the model of the phone being the x axis and and price of the phones being the y axis. 

## References 
This project was based off of [Ishaan Sharma7](https://www.youtube.com/@IshaanSharma7) on YouTube. 
