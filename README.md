# npd-well-headers-for-ic

- Quickly reformat NPD Well Headers so that column names match up perfectly in IC's Well Header Import tool.<br>
- Prepare .CSV files for nearly 1900 exploration and 5000 development well headers in seconds.<br>
- Create separate URL/Reference files for IC with links to NPD FactPages, FactMaps and Press Releases.<br>
- See a list of Well Attibutes you need to create in IC (that is, in addition to the defaults).<br>

<b>Imports NPD well headers from:</b><br>
- NPD Factpages > Wellbore > Table View > Exploration > All - Long List (permanent link)<br>
- NPD Factpages > Wellbore > Table View > Development > All - Long List. (permanent link)<br><br>

<b>Run the script as it is, or edit options to:</b><br>
- A. Rename dozens of header fields to match IC defaults, e.g. 'Entered date' to 'SPUD date'.<br>
- B. Truncate well list based on any field, e.g. 'Location: Barent's Sea'.<br>
- C. Add/remove spaces or characters in well names.<br>
- D. Concatenate cells to create 'Grid system' in IC format, e.g. "ED50 / UTM Zone 31N".<br>
- E. Concatenate Status & Content to match IC's Well Symbols dictionary, e.g. "P & A Gas/Condensate".<br>
- F. Add and populate new columns, e.g. 'Country: NORWAY'.<br>
- G. Copy data from one column to another, e.g. 'NPDID wellbore' to 'UWI Number'.<br>
- H. Re-order all columns, and delete unwanted columns.<br>
- I. Convert three URL columns into rows to match format required for IC References.<br>
- J. Create separate well header files for exploration and development wells, or combine into one.<br><br>

<b>Outputs four files for import to IC:</b><br>
- IC_explo_references.csv<br>
- IC_dev_references.csv<br>
- IC_wellbore_exploration.csv<br>
- IC_wellbore_development.csv<br>
