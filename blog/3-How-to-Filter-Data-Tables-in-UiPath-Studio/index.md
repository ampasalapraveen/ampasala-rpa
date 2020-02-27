# How to Filter Data Tables in UiPath Studio

The default filter Data Table activity for Studio. Suppose we have a table with 10 records with columns like FirstName, LastName, Company, Address, etc. For this example, I want to filter the records based anyone with the first name as “John.” We will use this example throughout this  post, with different approaches.
I have already read an Excel and put the data into SampleDT variable and FilteredDT is the variable that we will use for storing the result.
Drag the activity into your pane. When you click on Filter Wizard, you can see the Wizard. Just add Input and Output table names and the conditions. You are done. 😊 You can have multiple conditions and add or remove rows based on condition.
You can also choose what columns you want as a result, by adding columns via the Output Columns tab. That’s it.
