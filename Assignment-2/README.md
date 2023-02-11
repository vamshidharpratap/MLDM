# Implement the below functions

First download the file dataset.csv<br/>
The record contains row-wise samples of the fruits Apple, Lemon, and Pear. The attributes are listed in the first three columns, the class (Fruit) is provided in the forth column.
Implement below described processing tasks in a way that you may input another dataset with identical structure but different values. Print the processed dataset after each step onto your submission.<br/><br/>
Write the following functions.<br/>
a. To delete duplicate samples. <br/>
   &nbsp;•<b>def del_duplicate(data: dataframe) -> returns dataframe</b>
      
b. Function to fill missing values (fields that have 0) with the mean of the corresponding class of the attribute <br/>
      &nbsp;<b>• def fill_values(data: dataframe) -> returns dataframe</b>
    
c. Function to transform nominal attributes (not the classes!) into numerical values.<br/>
For example, there is an attribute called “color” and it is assigned values of “green”, “yellow”, and “red”. Remove this “color” column and introduce three new numerical columns, “green”, “yellow”, and “red”. For each row, set the value of the column corresponding to the former nominal value to one and the other two to zero.<br/>
      &nbsp;<b>• def transform_nominal(data: dataframe) -> returns dataframe</b>
     
d. Function to normalise the values of each numerical attribute with min-max method<br/>
      &nbsp;<b>• def normalise_minmax(data: dataframe) -> returns dataframe</b>
      
Also write the output of each function to a csv file.<br/>

<b>
Note:<br/>
If the code has any syntactical, logic errors, and/or exceptions it will not be accepted. </b>
