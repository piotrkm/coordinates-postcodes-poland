# coordinates-postcodes-poland
Geographical coordinates of postcodes in Poland approximated to closest local county capital.

Hi, 

This is a simple benchmark in Python/Pandas how to take data from two different sources and combine them together. 
The goal is to take all post codes from whole the country and asociated them with county capitals (pol. miasta powiatowe).

Source of the data: https://www.kody-pocztowe.dokladnie.com/ (downloaded at the beginning of 2024)
Information from the website is saved to CSV file 

Data about the cities and towns location is taken from website: 
https://astronomia.zagan.pl/art/wspolrzedne.html

files 

**postal_codes_2024.ipynb** - File with the script, the link will redirect you to google colab. 

**kody_pocztowe_2024.csv** - list of postal codes in Poland 

**lista_powiatow.csv** - list of counties in Poland

**codes_list.csv** - Resultant file with list of 43783 postal codes associated with geographical coordinates 

