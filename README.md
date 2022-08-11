# Complain Letter and Project 1   
  1. Tragedy Part.   
  2. Project Part.   
---

## Tragedy Part (Group II)
  > Dear Prof. Kevin Lee and teaching fellows,    Unfortunately I have faced an unwanted teamwork disaster with an arrogent leader, who obstructed me to do the following activity，including but not limited to:    
  > * Doing my own presentation
  > * Providing me authority to upload file to github
  > * Building new github branch
  > * Refusing finishing group work on time

  I totally understand group work may face inappropriate situation，I appreciate TAs' hard work and do not intend to make obsession. 

  I hope teaching fellows can review my homework (keynote and Jupyter) from my own repository and grade my project.

  I will upload corresponding links and picture to prove my word.   

## He didn't finish his work and he blocked our work   
* this is group repository without upstreaming 3 days ago     
["current group repository"](https://github.com/jchow527/Group_2_Stocks_Pickers)
* this is James Tan's repository without any work   
["leaders repository"](https://github.com/jamestan8292?tab=repositories)  
* this is I am asking authority to upload   
!["asking authority"]("./01.jpg")
* this is the proof that he refused me doing the presentation   
!["unreached presentation"]("./02.jpg")

----
# Project part

this project contains:
  > * a .csv file with S&P 500 index datas
  > * a .keynote file with presentation(please check it with autoplay button)
  > * a .env file contains API keys
  > * a .ipynb file analyzing the stock data

## Summary
  > This project obtained the stock data from alpaca SDK, and analyzed the return, risk and plotting corresponding charts.
  > This project cleaned the data and removed double level columns to make the dataframe clean.
  > This project used a new library to draw a candlestick chart with pyviz style dynamical plotting.

## Instruction
  > To avoid program conflicting, and due to the short time, this program provides fully running code   

## Project used a new library
  > using plotly graph object library draw candlestick
  ```python
  import plotly.graph_objects as go   
  ```
  !["candlesticks"]("./candle.jpg")

## Conclusion
  > * We used Alpaca SDK to gather stock datas, in this case: 

```python
      ["GILD", "MDLZ", "UAL", "DOV", "LYB" ]
```

  > * We clean the data, drop the columns, and neat the column levels. with dropna and drop duplicate, we prepared the data for analysis.   
  > * due to the chart, we found that UAL has the highest volatility, and MDLZ has the lowest.   
  > * according to the risk with broader market, we found all five stocks move the same position with the SP500 index and GILD has the lowest return value relative to the overall market return.

## What's next?
  > this program will be add new features that can run dynamically. It will be gather the data and build dataframe as object stored in a list, and work for not only specific stocks, but all stocks that user requested
  > this program will add questionary library for user to choose stocks

## Contributer
  > Liu Lujunjin   

## License

> MIT License

Copyright (c) [2022] [Liu Lujunjin]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


