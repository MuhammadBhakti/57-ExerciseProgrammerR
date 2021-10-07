# Excercise for Programmer R
## 57 case for R language
```R version 4.1.1 (2021-08-10) -- "Kick Things"```

![image](https://user-images.githubusercontent.com/49467005/136321897-b4e29154-5021-4c40-8ccf-c485ec247adf.png)

> '*R is fun*' and let's make something fun with it in the next few months.

```R
#The package
library(tidyverse)
```
### ***Chapter 1* : INTRO**
A few points before turning the problem into code:


* Understanding the problem
* Asking questions related the problem (Input, output)
* Breakdown the large program into smaller features, it will be easier to manage in the future
* Test the software, feature, input, process & Output
* Write the algorithm using pseudocode, this will help in the process of writing code

*Example pseudocode*
```javascript
TipCalculator
  Initialize billAmount to 0
  Initialize tip to 0
  Initialize tipRate to 0
  Initialize total to 0
  Prompt for billAmount with "What is the bill amount?"
  Prompt for tipRate with "What is the tip rate?"
  convert billAmount to a number
  convert tipRate to a number
  tip = billAmount * (tipRate / 100)
  round tip up to nearest cent
  total = billAmount + tip
  Display "Tip: $" + tip
  Display "Total: $" + total
End
```

### ***Chapter 2* : Input, Processing, and Output**
1. Saying Hello
2. Caunting the number of Characters
3. Printing quotes
4. Mad Lib
5. Simple Math
6. Retirement Calculator
