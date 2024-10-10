### Kickstarter Projects

#### Data Source:
- Two CSV files (2016 and 2018)  
[Data Link](https://www.kaggle.com/kemical/kickstarter-projects)

#### Data Transformation:
- **Create a Custom Column:** Add a column with the file name (e.g., "2016" or "ks-projects-201612") using M Language.
- **Append the files:** Combine the two files using M Language in Power Query.
- **Rename the tables:** Give a clear name to the table that holds all the data (e.g., KSProjects, Projects) and either hide or remove the other tables based on the steps. This can be done during the modeling phase.

#### Modeling:
- **Create a hierarchy:** (Main Category, Category, and Project Name) and name it "Project Hierarchy."
- **Hide or rename unnecessary tables.**
- **Create Measures:**
  - Number of Projects
  - Number of Backers
  - Total Pledged Amount
  - Total Goal Amount

#### Visuals (using Measures):
- **Cards:**
  - Number of Projects
  - Number of Backers
  - Total Pledged
  - Total Goal

- **Charts:**
  - Number of Projects by State
  - Number of Projects by Category Hierarchy (with Drill Down)
  - Number of Projects by Launch Date
  - Total Pledged by Country

#### Formatting:
- **Good color scheme, clean layout, and meaningful chart titles.**
