# Exploratory Data Analysis: National Emissions Inventory Dataset

This project involves exploratory data analysis on the National Emissions Inventory (NEI) dataset to understand the trends in PM2.5 emissions in the United States from 1999 to 2008. The analysis is divided into several tasks, each focusing on specific questions about emissions patterns.

## Dataset
The data used for this project includes:
- `summarySCC_PM25.rds`: PM2.5 emissions data for 1999, 2002, 2005, and 2008.
- `Source_Classification_Code.rds`: A mapping table that links source codes to source names.

### Variables in `summarySCC_PM25.rds`
- `fips`: U.S. county code
- `SCC`: Source Classification Code
- `Pollutant`: Pollutant name
- `Emissions`: PM2.5 emissions in tons
- `type`: Source type (point, non-point, on-road, non-road)
- `year`: Year of observation

## Project Tasks
The project addresses the following questions through plots:

### Task 1: Total Emissions in the United States (1999–2008)
**Objective**: Analyze whether total PM2.5 emissions have decreased over this period.  
**Plot File**: `plot1.png`  
**Code File**: `plot1.R`

### Task 2: Total Emissions in Baltimore City (1999–2008)
**Objective**: Investigate trends in emissions for Baltimore City, Maryland.  
**Plot File**: `plot2.png`  
**Code File**: `plot2.R`

### Task 3: Emissions by Source Type in Baltimore City
**Objective**: Determine which source types (point, non-point, on-road, non-road) saw increases or decreases in emissions.  
**Plot File**: `plot3.png`  
**Code File**: `plot3.R`

### Task 4: Emissions from Coal Combustion Sources in the U.S. (1999–2008)
**Objective**: Examine changes in emissions from coal combustion-related sources.  
**Plot File**: `plot4.png`  
**Code File**: `plot4.R`

### Task 5: Motor Vehicle Emissions in Baltimore City
**Objective**: Analyze trends in emissions from motor vehicle sources in Baltimore.  
**Plot File**: `plot5.png`  
**Code File**: `plot5.R`

### Task 6: Compare Motor Vehicle Emissions in Baltimore and Los Angeles
**Objective**: Compare emissions from motor vehicles in Baltimore City and Los Angeles County.  
**Plot File**: `plot6.png`  
**Code File**: `plot6.R`

## How to Run
1. Clone this repository and set your working directory to the project folder.
2. Ensure the `summarySCC_PM25.rds` and `Source_Classification_Code.rds` files are in the working directory.
3. Run each of the `R` script files (`plot1.R`, `plot2.R`, ..., `plot6.R`) to generate the corresponding plots.

## Dependencies
This project uses the following R packages:
- `ggplot2` for creating advanced plots.

Install the required packages using:
```R
install.packages("ggplot2")
