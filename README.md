# DBFoundations-Module07
**Assignment 7: Functions**

###Name: John Wilkinson
###Date: Aug 22, 2022
###Course: DB Foundation Assignment 07

##Functions

###Introduction
Functions are useful tools to return variable amounts of data. Depending on the goal of the
creator of the function it can return a single value, such as an ID. Or it can return multiple select
statements that consist of joins or other transformations.


###User Defined Function
One of the most useful tools in not just in functions but in sql in general is the user defined
function. This is used when a cumbersome series of code will need to be repeated multiple
times. Instead of creating the same syntax that can consist of multiple joins, an analyst can
create this type of function to receive an input or multiple inputs and obtain the same data they
would if they had to recreate the difficult syntax from before. This method is a time saver for any
analyst and helps with the readability of one’s code, by making the reader only have to
reference the original function.


###Scalar, Multi, and Inline Functions
Now that we have established what a user defined function (UDF) is, it's important to state the
types of UDFs that exist and the differences. The first type is a scalar function. This type of
function returns a single value when you run the query attached to this function. An example of
this would be if you wanted to find the sales rep with the highest sales volume in a table. This
will return that specific name or id associated with the rep. Another type is the inline function. It
will provide multiple rows of data, in comparison to the scalar it can return a single select
statement but won't return multiple statements. Lastly we have multi-statement functions. As the
name suggests you can have multiple select statements in this type of function. It can give back
large amounts of data and can handle more joins and transformations than the previous two
types.
(Informit. InformIT. (2003, May 2). Retrieved August 22, 2022, from
https://www.informit.com/articles/article.aspx?p=31673 - URL)


###Summary
To conclude, functions can vary from scale and purpose. They can be as simple as returning a
single name to something as sweeping as a multi statement query that provides data from
multiple tables. These types of functions can save the analyst time and help with the readability
for others reading their code.

This site calls from sources in [Informit](https://www.informit.com/articles/article.aspx?p=31673).

![SQL Image](https://codingsight.com/wp-content/uploads/2021/08/HowtoMakeUseDatabaseFeatures_878%D1%85700-870x600.png)
