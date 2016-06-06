---
layout: single
---

# Itemised Bill

Practice basic algorithms for find, filter and sort.

**For each of the scenarios below create a function using TDD :**

1. that can read an [Itemised cell phone bill](./ItemisedBill.csv) and **create a list of maps** (an object in JS). Each line in the file become a map/object.
2. that can return all the **phone calls for the specified provider**. It takes the object version of the bill and a provider as parameters.
3. that calculates **the total number of calls** made to numbers for each cell phone provider.
4. that can calculate the **duration in seconds** of a call, given a duration in the **format `00h00m00s`**.
5. that can **order the calls** by ascending duration.
6. that lists cell phone provider and call duration, sorted by **cell phone provider**, with a call duration **sub-total** at the end of each provider.
7. that takes a [Handlebars template](https://www.npmjs.com/package/handlebars) and creates a nicely formatted **itemized bill with totals and sub-totals**. Add lines to the report that: show when the calls for a cell phone provider start; display the total call duration for each provider. Add a line at the bottom displaying the total call duration for all calls.

**Note:**

The results of the functions are parameters for the other functions. One function feeds data into the next function. It all starts from the CSV file.

Write your tests using Mocha.
