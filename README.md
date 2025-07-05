# Sri Lanka Cricket Power BI Project

<img width="886" height="497" alt="Image" src="https://github.com/user-attachments/assets/baa768cc-0343-4881-917c-183a5718130e" />

## Objective
The aim of this project is to create a Power BI dashboard showing the key statistics of Sri Lanka (SL) Cricket in ODIs.

## Link to Dashboard
https://app.powerbi.com/view?r=eyJrIjoiNjgxMzRmYzktM2E3MS00N2NiLWJkZjUtM2U2YWE0ZDg3OGUyIiwidCI6IjFkYTQ1MTA3LTFmNTMtNGE4MC1iNTMzLTliMTg4Nzk2MGNlOSIsImMiOjEwfQ%3D%3D

## Further Information
- This dataset was obatined from howstat.com, and has been directly linked to Power BI

- After importing the data, the data was cleaned and various transformations were performed:
    - The opposition team was extracted using the "Text.AfterDelimiter" function
    - Match location (home or away) and opponent difficulty (strong or weak) were added using conditional columns
    - The winner of the match was added using an IF statement
    - Irrelevant rows columns were removed

- Afterwards, the cleaned and transformed data were loaded into Power BI

- Various DAX measures were then added:
    - Total matches played
    - Total matches won
    - Total matches lost
    - Matches tied/no result
    - Sri Lanka win %

- Finally, the information was presented using various visualizations:
    - The aggregate matches played, won, lost and the overall win % were shown in enlarged cards
    - The SL win % over the years was displayed in a line chart
    - SL's performance versus opponents and the ground wise performance were shown in tables
    - SL's win % by opponent difficulty was shown in a column chart
    - Slicers were added for opponent difficulty, match location and date.
