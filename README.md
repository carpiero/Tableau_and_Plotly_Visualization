# Ironhack Data Analytics M2 Project README file

![](./images/diamond2.png?style=centerme)

---

### :raising_hand: **Analysis Diamonds Datasheet** 


### :baby: **Status**
Ironhack Data Analytics M2 Project

### :boom: **Core technical concepts and inspiration**

- Python 3.7.3
- Pandas 0.24.2
- Plotly 4.8.2
- Matplotlib 3.2.1
- Seaborn 0.10.1
- Numpy 1.18.1

### :see_no_evil: **Insights**


#### Variables



__We have in the diamonds datasheet:__

* Three `category` variables, cut, colot and clarity
* Six `float64` variables, carat, depth, table, x, y and z
* One `int64` vaiables, price.

__Main Insights:__

* Correlation > 0.96 between **X**, **Y**, **Z**, **Carat**, **Price**.

* **X**, **Y**, **Z** form the size and **Carat** is the weight, therefore they are correlated.

* In correlations one to one variable, the only one that correlates with **Price** is **Carat**.

* We could see in the relationship between **Depth** and **Cut** that the worst qualities of **Cut** are in the extremes and the best in the middle, showing a relationship between **Depth** and **Cut**.

* We could see that the worst qualities of the combinations **Cut**-**Color**-**Clarity** needs less carat for achieve more prices, showing a relationship between **Cut**-**Color**-**Clarity** with **Price**.

* We see a clear ladder in the barplot of the Average Price per the combinations of **Cut**-**Color**-**Clarity**, better **Cut**-**Color**-**Clarity** the average of price is lower, showing that is difficult to obtain a diamond with a high quality (High**Cut**-High**Color**-High**Clarity**) and high weight (**Carat**).

* We could see that the PRICE BOTTOM 1000 only have carats below 0.85 carats and in the PRICE TOP 1000 we don't see diamonds with less (only 22 of 1000) that 1.4 carats.


### :file_folder: **Folder structure**
```
└── project
    ├── __trash__
    ├── .gitignore
    ├── README.md
    ├── images
    ├── notebooks
    │   ├── notebook001.ipynb
    │   └── notebook002.ipynb
    │   └── notebook002.ipynb
    └── data
        ├── raw
        ├── processed
```


