 ----- Data Modelling / Part 4 -----

1.  Find the author with the name 'Kara Melton' and then select all the articles she has written.

    SELECT id FROM authors WHERE name='Kara Melton';
    SELECT title FROM articles WHERE author_id=8;
    => How Tech Business Models Come From Marginalized Communities, But Startups Are Still Mostly White
    => Confronting the Assumption of Whiteness in Virtual Spaces

2.  Find Ontario in the provinces table and then find all the cities in that province.

    SELECT id FROM provinces WHERE name='Ontario';
    SELECT name FROM cities WHERE province_id='14';
    => Toronto, Ottawa

3.  Who wrote the article called 'Coding Bootcamps and Emotional Labor'?


4.  Write a series of SQL queries to find out how many provinces are in Canada.


5.  How many people live at 4740 McDermott Street?


6.  What city is 4740 McDermott Street in?


7.  What province is 4740 McDermott Street in?


8.  What country is 4740 McDermott Street in?


9.  Find the person named 'Destini Davis' and then use a series of SQL queries to find what country they live in.


10.  How many articles has Aditya Mukerjee written?
