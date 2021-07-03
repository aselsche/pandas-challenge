**All About Pandas -- PyCitySchools**

As the Chief Data Scientist for my city's school district, my task was to help the school board and mayor make strategic decisions regarding future school budgets and priorities. I used an open source data analysis and manipulation tool, Pandas, and a next-generation web-based user interface, Jupyter Notebook, to analyze a district-wide raw data. The analysis can be found here: [Jupyter Notebook](main.ipynb)

My first task was to analyze the district-wide standardized test results. I was given access to every student's math and reading scores, as well as various information on the schools they attend. I generated a table called District Summary, which represents a high level snapshot of the district's key metrics:

**District Summary**

![image](https://user-images.githubusercontent.com/84043141/124283097-85c6dd80-db19-11eb-911f-96974972d4d0.png)

This overarching District Summary shows us the data that I will further analyze. There are 15 schools with a budget of over $24 million dollars altgether.

**School Summary**
Next, I created an overview table that summarized the key metrics about each school.

![image](https://user-images.githubusercontent.com/84043141/124285392-dd664880-db1b-11eb-8b50-b4fdb8a89feb.png)

**Top and Bottom Performing Schools By % Overall Passing**

The next two tables display data about top 5 performing schools and 5 worst-performing schools by % overall passing. As you can see the top performing schools are: Cabrera High School, Thomas High School, Griffin High School, Wilson High School, Pena High School, whch are all Charter schools. The 5 worst performing schools are district schools: Rodriguez High School, Figueroa High School, Huang High School, Hernandez High School, Johnson High School which are all District schools. It is important to note the district schools, specifically these bottom performing schools have a high number of total students. While the reading scores are above 80% in both schools, the students at the top perfoming schools have higher scores in math.

**Math and Reading Scores by Grade**
Then, I created a table that lists the average math and reading scores for students of each grade level (9th, 10th, 11th, 12th) at each school. While these tables show only point-in-time data showing the scores being in high 70s and above, there is no time dimension for this data to make further conclusions about the trends.

**Scores by School Spending**
This table breaks down school performances based on average Spending Ranges (Per Student) using 4 reasonable bins to group school spending. As the data shows, there is is a low correlation between school spending per student and the student's overall success.

**Scores by School Size**
This table breaks down school performances based on school size using 3 bins (Small, Medium, Large) to group school size. As you can see from the table, the overall passing % is low in larger schools.

**Scores by School Type**
Lastly, this table breaks down school performances based on school type. There are two types of schools: charter and district. The charter schools tend to do better overall than district, specifically in math. The overall passing % in district school is little over 54%, whereas the charter schools show to have an overall passing % rate of 90%.

**Conclusion**
- There are 15 schools with a budget of over $24 million dollars altgether.
- Top performing schools are: Cabrera High School, Thomas High School, Griffin High School, Wilson High School, Pena High School, whch are all Charter schools. The 5 worst performing schools are district schools: Rodriguez High School, Figueroa High School, Huang High School, Hernandez High School, Johnson High School which are all District schools. It is important to note the district schools, specifically these bottom performing schools have a high number of total students. While the reading scores are above 80% in both schools, the students at the top perfoming schools have higher scores in math.
- While these tables show only point-in-time data showing the scores being in high 70s and above, there is no time dimension for this data to make further conclusions about the trends. However, these tables reveal that students have better outcomes in reading than math.
- There is is a low correlation between school spending per student and the student's overall success. We could commit further analysis to see if there is any correlation between performance and spending within a specific type of school. 
- The overall passing % is low in larger schools.
- The overall passing % in district school is little over 54%, whereas the charter schools show to have an overall passing % rate of 90%.