# merge-files
import pandas as pd
from pandas import DataFrame, read_excel, merge
df1 = read_excel(r'C:\Users\SOCHY\Downloads\fortune-ppmv-process.xlsx')
df2 = read_excel(r'C:\Users\SOCHY\Downloads\ppmv_prices.xlsx')
df3 = df1.merge(df2, on='Drug Name', how ='left')
df3
