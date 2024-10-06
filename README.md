# SISE2601 Project data description
================
Tamir Spevak

Instructions:

1. download dataset from provided kaggle link
2. open RStudio and ensure necessary libraries installed
3. place the dataset file in a place of your choice
4. copy the file path of the dataset
5. replace the file path in the quotation marks with the copied file path like this:
|cereal <- read_csv("../data/cereal.csv")|--->|cereal <- read_csv("copied file path")|
6. run the code



This section describes the data folder structure and organization:


#name: name of each cereal

#mfr: manufacturer
A = American Home Food Products
G = General Mills
K = Kelloggs
N = Nabisco
P = Post
Q = Quaker Oats
R = Ralston Purina

#type: type of cereal
C = Cold 
H = Hot

*following measurements are per serving:

#calories: calories

#protein: grams of protein 

#fat: grams of fat

#sodium: miligrams of sodium

#fibers: grams of dietary fibers

#carbo: grams of complex cabohydrates

#sugars: grams of sugars

#potass: miligrams of potassium

#vitamins: vitamins and minerals -0, 25, 100, indicating the typical percentage of FDA recommended

#shelf: display shelf (irrelevant)

#weight: weight in ounces of one serving (will be converted to grams)

#cups: number of cups in one serving (irrelevant)

#rating: rating of the cereals (unknown source and irrelevant)