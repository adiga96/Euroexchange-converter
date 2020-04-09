# Currency Convertor Online Data for Euro (€)

Authors:  
Wilson Jo Siu,
Pritish Shivananda Adiga,
Abhishek Shirsat and
Gokul Selvaraj

---

## Introduction

The currency converter (exchange rate) is a useful financial tool which allows the user to see the daily exchange monetary value of the Euro(€) in a variety of foreign currencias such as japanese yen, US dollar, Canadian Dollar, Indian Rupee,etc. The base unit for the currency converter is 1 euro and the equal value is displayed for the currencias as well when we request online data. The list of currencies provided are the ones who have a bigger relevance to the Europea Market.

Example:
On the date 04-08-2020, 1 euro equals to 1.0871 USD or 10436.7232 Vietnamese Dong.

The type of data we are importinng comes from a european currency converter webpage, but at the same time many of these webpages collect daily data from a single centralized entity, in this case the European Central Bank.

The source of the data can be adquired from multiple webpages, but some of them will not have a free API key to share, in many cases you are required to paid to have quick acess to this kind of information. In the financial market, it is important to be up to date as it will help make the most adequate financial decisions (forecasting, investments or stock market). 

The source of data is provided by an API currency converter "currency-converter5.p.rapidapi.com"

The acquired data is updated daily and we can also obtain data from previous years on specific days (the date limit to acquire the last point of data is from 2010-01-01) (dates and times are based on the current timezone you are located. 

---

## Sources

- The source code was obtained from:  https://rapidapi.com/natkapral/api/currency-converter5?endpoint=apiendpoint_a4bcb4ce-c9c6-4c58-8ed5-20ccb34098d2
The current link has information about the API key and webpage host. It also explains how the output will be like and what does it mean(format).It also has some additional information to understand the currency exchange data and what values you can obtain.

- Currency exchange rates are obtained from the European Central Bank: https://www.ecb.europa.eu/stats/policy_and_exchange_rates/euro_reference_exchange_rates/html/index.en.html 
The values that are given are also listed in the previous link.

- Programming for Analytics Video Lectures: Module 5 Online Data

## Explanation of the Code
The code, `needs_a_good_name.py`, begins by importing necessary Python packages:
```
import matplotlib.pyplot as plt
```

- *NOTE:  If a package does not come pre-installed with Anaconda, you'll need to provide instructions for installing that package here.*

We then import data from [insert name of data source].  We print the data to allow us to verify what we've imported:
```
x = [1, 3, 4, 7]
y = [2, 5, 1, 6]

for i in range(0,len(x)):
	print "x[%d] = %f" % (i, x[i])		
```
- *NOTE 1:  This sample code doesn't actually import anything.  You'll need your code to grab live data from an online source.*  
- *NOTE 2:  You will probably also need to clean/filter/re-structure the raw data.  Be sure to include that step.*

Finally, we visualize the data.  We save our plot as a `.png` image:
```
plt.plot(x, y)
plt.savefig('samplefigure.png')	
plt.show()
```

The output from this code is shown below:

![Image of Plot](images/samplefigure.png)

---

## How to Run the Code

1. Acess to the Anaconda Prompt

1. Open a terminal window.

2. Change directories to where `needs_a_good_name.py` is saved.

3. Type the following command:
	```
	python needs_a_good_name.py
	```

- *NOTE: You are welcome to provide instructions using Anaconda or IPython.*

---

## Suggestions

A currency converter is considered a useful financial tool because it give us up to date values that are 

