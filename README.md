# Web automation - Price Research

This is project was made to make the price research easier. It was made for studying purposes only.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

This project was developed 100% with python. The objective is to facilitate the price research of any product (I used only two, but you can use as many as you like)

### Objectives :notebook: :pencil2:

To built a project of web automation using python making use mostly of selenium to make the research of the information we need.

We'll do the research and make a filter of some products pre established coming from a database (in this case an excel.xlsx).

### How it will work :computer:

Here we established a imaginary situation where we work at the shopping area of a company and we need to compare some suppliers for our products. With these informations we naturally search on the websites for the products availability and the prices

Our objectives here are the following:

- The price of the products we are looking for must be lower than a limit defined before. We will find the products and put them on a table
- Then, we will e-mail (whoever needs to receive the information) with the list we made

### In Summary :pencil:

The program must read the original database, search for the products there and filter them according to some specifications and the price limit. At the end, it must create a new database listing all products that was found, and send an e-mail with all the information.

 ### Observations :exclamation:
 
- In this project, the program was developed considering the google shopping search tool but it can be adapted to any other  website
- The database that was used in the construction of the program is available for viewing in this repository
- The email used in this project is an email created exclusively for code testing
- The email was sent using Google service, where you need to generate an app password in the gmail configuration area. This password was used as the email password instead of the actual email password.

### Screenshot

![This is a display of the dataframe the program should return](/return_df_products.png)
This is an example with the products I used


## My process

### Built with

- Python
- Selenuim

### What I learned

To be more organized with my code in order to avoid errors in the execution in the future.

### Useful resources

- [Google](https://www.google.com/) - I used basically Google to make the price research, but the code may be adapted to any website you want to use. It will depend only of its looks so you can built your code properly using the website elements.

## Author

- LinkedIn - [alessandra-santos-oliveira](https://www.linkedin.com/in/alessandra-santos-oliveira/)
- Twitter - [@itsale_o](https://twitter.com/itsale_o) (I don't talk about work there but feel free to follow me)
