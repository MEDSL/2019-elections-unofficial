# Codebook for 2019 Election Unoffical Data

The data files `2019-ky-gov-county`, `2019-ms-gov-county`, and `2019-va-legislature-returns` contain unofficial 2019 off-year election returns. The `2019-ky-gov-county` and `2019-ms-gov-county` files are county-level returns for Kentucky and Mississippi, respectively. The source for this data is the New York Times (link for KY is [here](https://www.nytimes.com/interactive/2019/11/05/us/elections/results-kentucky-governor-general-election.html) and link for MS is [here](https://www.nytimes.com/interactive/2019/11/05/us/elections/results-mississippi-governor-general-election.html)). The `2019-va-legislature-returns` file contain constituency-level returns (by State House and Senate District) for Virginia. The source for this data is the [Virginia Department of Elections webpage](https://www.elections.virginia.gov/resultsreports/).

Note that this data reflects vote totals as of version date/time, and will be updated weekly up until December 18th to reflect most up-to-date data.

## Variables
Note that this data reflects vote totals as of version date/time, and will be updated weekly up until December 18th to reflect most up-to-date data. Official results will be posted when they are made available.

### year
- **Description**: election year	

------------------

### state
- **Description**: state name 

-----------------

### state_po
- **Description**: U.S. postal code state abbreviation

----------------

### state_fips
 - **Description**: State FIPS code

----------------

### state_cen
 - **Description**: U.S. Census state code

 ---------------
 
### state_ic
 - **Description**: ICPSR state code

-----------------

### office
- **Description**: office name

-----------------

### district
- **Description**: district number and/or name; statewide races labelled as "statewide"

-----------------

### county
 - **Description**: county name

-----------------

### stage
- **Description**: electoral stage; always general ("gen") here

-----------------

### special
- **Description**: special election TRUE/FALSE indicator (always FALSE here, no special elections data is included)

-----------------

### candidate
- **Description**: name of the candidate
 
-----------------

### party
- **Description**: party of the candidate

-----------------

### writein
- **Description**: TRUE/FALSE indicator for write-in candidates/totals

-----------------

### mode
- **Description**: mode of voting; states with data that doesn't break down returns by mode are marked as "total"; other states can have modes of "absentee," "machine," "absentee mail," "absentee walk-in," "election day," "polling," "early," "one stop," and "provisional" 

-----------------

### votes 
- **Description**: votes received by this candidate for this particular party

----------------

### version 
- **Description**: time at which unofficial data was added

----------------