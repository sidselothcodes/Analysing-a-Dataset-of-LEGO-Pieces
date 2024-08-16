
# LEGO Dataset Analysis

## Introduction

This project dives deep into a dataset all about LEGO to answer various interesting questions regarding the history of the LEGO company, its product offerings, and to determine which LEGO set truly rules them all. By analyzing the dataset, we aim to explore:

- What is the most enormous LEGO set ever created, and how many parts did it have?
- In which year were the first LEGO sets released, and how many sets did the company sell during its first launch?
- Which LEGO theme has the most sets? Is it Harry Potter, Ninjago, Friends, or something else?
- When did the LEGO company really take off based on its product offerings? How many themes and sets did it release each year?
- Did LEGO sets grow in size and complexity over time? Do older LEGO sets tend to have more or fewer parts than newer sets?

## Data Source

The data for this project is sourced from Rebrickable, which has compiled extensive information on all LEGO pieces ever produced. The primary files used in this analysis are:

- `colors.csv`: Contains information about the different colors of LEGO pieces.
- `sets.csv`: Lists the LEGO sets released over the years and includes the number of parts each set contains.
- `themes.csv`: Provides details about the various LEGO themes.

## Project Structure

- **Data Exploration**: We begin by exploring the `colors.csv` file to understand the range of colors LEGO produces and identify transparent versus opaque colors.
  
- **Understanding LEGO Themes and Sets**: The `sets.csv` file is analyzed to uncover the history of LEGO sets, such as the first sets released, the number of sets sold initially, and the evolution of LEGO's offerings over the years.

- **Challenges**:
  - Identifying the most enormous LEGO set and the number of parts it contains.
  - Determining the number of LEGO sets released annually and comparing the growth from the early years to recent times.
  - Analyzing the average number of parts per set over the years to observe trends in the size and complexity of LEGO sets.
  
- **Aggregated Data Analysis**: Using group-by and aggregation techniques, we calculate and visualize various metrics, such as the number of themes released by year and the average number of parts per set.

- **Visualizations**: The project includes line charts, scatter plots, and bar charts to illustrate the trends and patterns found in the data.

## How to Use

1. **Clone the repository**: Download or clone this repository to your local machine.
   
2. **Install dependencies**: Ensure you have Python installed along with the necessary libraries:
   ```bash
   pip install pandas matplotlib
   ```

3. **Run the notebook**: Open and run the `Lego_Analysis.ipynb` Jupyter Notebook to see the analysis in action. This notebook will guide you through each step of the analysis, from data exploration to visualization.

## License

This project is licensed under the MIT License.
