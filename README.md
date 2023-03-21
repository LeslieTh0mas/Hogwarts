On Febuary 10, 2023, the Wizarding World expanded! There had been data bases for older characters, but none for these new characters.  This project changes that. It combines the characters that fans are familiar with, and integrates these new character facts. It explores how these new charaters contribute to the numbers of gender, houses, widardry, ancestry, eye color, and year of birth. 

Feature one was to  "Read TWO data files (JSON, CSV, Excel, etc.). For the first data frame, I pulled in an API that listed all characters from the Harry Potter franchise. For the second part of fearture one, "Read TWO data files (JSON, CSV, Excel, etc.)", I created an excel file of the data for characters from the video game "Hogwarts Legacy".

Feature two was to "Clean your data and perform a pandas merge with your two data sets, then calculate some new values based on the new data set."  A concatenation of two or more data frames can be done using pandas.concat() method. Concat() in pandas works by combining Data Frames across rows or columns. We can concat two or more data frames either along rows  (axis=0) or along columns (axis=1). I did a concat along rows.  I prefer snake case over camel case, so I fixed the columns on the data frame. Color is the preferred spelling in the United States over "colour". I changed those columns as well.  To clean my data, I used the df drop feature to drop columns that was not compatable to the second data frame.  I saved the file as a csv. I loaded the new csc and used  Pandas describe() is used to view some basic statistical details like percentile, mean, std etc. of a data frame or a series of numeric values.

Feature 3 was to "Visualize / Present your data". I chose to make several seaborn visualizations using Seaborn. I explored gender, houses, widardry, ancestry, eye color, and year of birth. 

Feature 4: "Annotate your code with markdown cells in Jupyter Notebook"

Relevant packages that need to be installed to run the project:

%pip install notebook

%pip install pandas

%pip install matplotlib

%pip install seaborn

%pip install requests
