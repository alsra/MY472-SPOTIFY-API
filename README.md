

# Rolling Stone's 100 Greatest Artists: Enduring Engagement in 2023


![Rolling Stone Top 100](https://i.ytimg.com/vi/pFzKLhqIgFA/maxresdefault.jpg)


## Summary

This project analyzes the enduring impact of the 100 greatest musical artists as ranked by *Rolling Stone Magazine*. Using data from Spotify, the study examines how listener engagement—measured by follower counts and popularity scores—has evolved through the years. The research explores potential patterns in listener preferences and investigates whether specific features, such as genre, influence an artist's lasting popularity.

## Research Question

**Rolling Stone Magazine ranked their 100 greatest musical artists of all time. At the end of 2023, how has their music endured? Are there any features or characteristics that seem to explain enduring engagement?**



## Technical Skills and Tools

| **Category**             | **Tools/Skills**       |
|---------------------------|------------------------|
| **Programming Language**  | R                      |
| **Data Visualization**    | `ggplot2`, `plotly`    |
| **Web Scraping**          | `rvest`, `RSelenium`   |
| **Data Wrangling**        | `dplyr`, `tidyr`       |
| **APIs**                  | `spotifyr`            |
| **Other Libraries**       | `httr`, `jsonlite`, `stringr` |

## Research Approach

To address the research question, the project follows these steps:
1. **Data Collection:** Spotify's API is used to extract follower counts, popularity scores, and genre information for each artist.
2. **Data Cleaning and Wrangling:** The data is prepared using `dplyr` and `tidyr`.
3. **Analysis:** Trends and patterns are visualized using `ggplot2` and `plotly`, with a focus on the relationship between genre and engagement.
4. **Insights:** Observations on enduring engagement are drawn from the data, highlighting standout artists and genres.

---
## Results

Key insights from this analysis include:
- Genres like rap and rock show consistently high engagement.
- More niche genres, such as blues and soul, demonstrate a steady but smaller following.
- Certain artists show surprising popularity growth over time, driven by cultural or streaming phenomena.

## Resources

- **Data Source:** Spotify API, *Rolling Stone Magazine* 100 Greatest Artists
- **GitHub Repository:** [Final Assignment Repository](https://github.com/busralb/MY472-Final.git)
- **References:** Spotify API Documentation, *Rolling Stone Magazine*

## How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/busralb/MY472-Final.git
   ```
2. Open the R Project in RStudio.
3. Install necessary libraries:
   ```R
   install.packages(c("spotifyr", "ggplot2", "plotly", "dplyr", "tidyr", "rvest", "RSelenium", "httr", "jsonlite", "stringr"))
   ```
4. Run the R Markdown file to generate the report.

---
