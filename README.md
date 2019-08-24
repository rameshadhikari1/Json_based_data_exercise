# Json_based_data_exercise

The answers for the json based data exercise are provided in the jupyter notebook. 

The data-table is loaded using pandas and then the total number of entries for each country are summed using value_count method. Only 10 countries with top number of project numbers are displayed. 

The json data is loaded in the flat form and normalize to the tabular form for the column named as 'mjtheme_namecode' which is in the form of list of dictionary. The json_normalize converts that dictionary items in the tabular form. There are some entries for the names of the projects with specific project codes. We fill the missed names with the names for the corresponding codes.

Using value_count method, the number of entries for each project names are found and top 10 most projects' are displayed. 
