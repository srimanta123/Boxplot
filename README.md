# Boxplot
import numpy as np  
import pandas as pd  
import matplotlib.pyplot as plt  

df = pd.read_csv("data1.csv") 
df
df.head()

df.boxplot(column=['G2DFLD','FG2DFLD','WFG-2DFLD','EnFFG-2DLDA'],grid=False)

df.boxplot(column=['G2DFLD'],grid=True)


