# Floxus-javascript-assignment

Link: https://javascript.info/task/find-elements/table.html

How to find?…

1) The table with id="age-table". 
2) All label elements inside that table (there should be 3 of them). 
3) The first td in that table (with the word “Age”). 
4) The form with name="search". 
5) The first input in that form. 
6) The last input in that form.


Solution:
1) ageTableID = document.querySelector("#age-table") 
2) labels = document.getElementById("age-table").querySelectorAll("label")
3) firstTdWithAge = document.getElementById("age-table").querySelector("td")
4) nameSearchForm = document.querySelector("form")
5) firstInput = document.querySelector("form").querySelector("input")
6) lastInput = document.querySelector("form").querySelectorAll("input")[1]
