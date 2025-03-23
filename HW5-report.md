# HW 5 - CS 625, Spring 2025

Bhargav Iyer \
Due: March 23, 2025

## Part 1

Dataset 3 (Urban and Rural Population by State)

### Data Manipulation

```
new_col_names = ['State', 'State Abbreviation', 'Former Urban definition 1990 (percent)', 'Urban definition 1990 (percent)', 'Total Population 2000 (1,000)', 'Urban Population, 2000 (1,000)', 'Urban Population, 2000 percent', 'Rural Population, 2000 (1,000)']
urban.columns = new_col_names
urban = urban.iloc[6:57]
urban = urban.drop(urban[urban['State'] == 'District of Columbia'].index)
```

The data manipulation I did within the data first is to update the column names.  I first updated the column names to what seemed logical and concise names.  I then updated the urban rows to not include any null rows and as well as remove the United States, total from the dataframe.  Finally, I dropped the District of Columbia from the dataframe to only have the bare 50 states datapoints.

### Boxplot

## References

*Every report must list the references (including the URL) that you consulted while completing the assignment. Replace the items below with the references you consulted*

* Reference 1, <https://www.example.com>
* Reference 2, <https://www.example.com/reallyreallyreally-extra-long-URI/>
