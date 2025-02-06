Netflix Data Cleaning & Analysis

Table of Contents

Overview

Dataset

Data Cleaning Process

Key Questions

Data Analysis

Code Structure

Insights and Conclusions

Technologies Used

Contributing

Contact

License

Overview

This project involves analyzing Netflix's content library by cleaning raw data and extracting meaningful insights. The analysis is performed using SQL, Python, and visualization libraries such as Matplotlib and Seaborn.

Dataset

The dataset contains details about Netflix movies and TV shows, including the following attributes:

Title: Name of the show or movie

Show ID: Unique identifier for each entry

Type: Movie or TV Show

Director: Director of the content

Cast: Cast members

Country: Country of production

Date Added: Date the content was added to Netflix

Release Year: Year the content was released

Rating: Viewer rating (e.g., TV-MA, TV-14)

Duration: Length of the content

Listed In: Genres/categories

Description: Brief overview of the content

Data Cleaning Process

Handling Foreign Characters: Ensured proper encoding and formatting of text data.

Removing Duplicates: Identified and removed duplicate entries by comparing title and type.

Data Type Conversion: Converted date_added to date format.

Handling Missing Values:

Populated missing country values using associated directors.

Filled missing duration values where possible.

Assigned 'not_available' for remaining missing entries.

Normalization: Split genre information into a separate netflix_genre table for better analysis.

Key Questions

1. Content Variety

What is the distribution of content types (Movies vs. TV Shows) on Netflix?

2. Genre Preferences

Which genres are most popular among Netflix users for TV shows and movies?

3. Content Producers

Which countries are the major contributors to Netflix's content?

4. Ideal Release Months

When is the best time to release content on Netflix?

5. Year-wise Analysis

In which year did Netflix see the highest number of content releases?

6. Viewer Ratings Analysis

What are the most common viewer ratings for Netflix content?

Data Analysis

Sample Insights:

Content Variety: Netflix offers a diverse range of content, with 69.6% movies and 30.4% TV shows.

Genre Preferences: International TV Shows are a hit among the top TV shows, while Drama rules the movie category.

Content Producers: The United States, India, and the United Kingdom are the primary content producers on Netflix.

Best Release Months: For optimal content releases, focus on July, December, and September – they attract the most viewers.

Year-wise Peak: 2018 marked a peak in Netflix movie releases, making it an ideal reference for planning content.

Viewer Ratings: Netflix's most common rating is 'TV-MA,' indicating a significant collection for mature audiences.

Code Structure

Data Loading and Preprocessing:

Loaded the dataset into SQL Server.

Cleaned the data using SQL queries and transformations.

Data Analysis and Exploration:

Addressed questions such as genre trends and country-wise contributions.


Interpretation and Presentation:

Summarized findings and provided actionable insights.

Insights and Conclusions

Diverse Content Mix: Netflix offers a diverse range of content, with 69.6% movies and 30.4% TV shows.

Genre Insights: International TV Shows are a hit among the top TV shows, while Drama rules the movie category.

Top Content Providers: The United States, India, and the United Kingdom are the primary content producers on Netflix.

Best Release Months: For optimal content releases, focus on July, December, and September – they attract the most viewers.

Year-wise Peak: 2018 marked a peak in Netflix movie releases.

Viewer Ratings: Netflix's most common rating is 'TV-MA.'

Recommendation: To maximize engagement, prioritize International TV Shows, Drama movies, and mature content. Strategically release in July, December, or September, and monitor audience trends for consistent success.

Technologies Used

SQL Server for data storage and manipulation

Python for data analysis and transformation

Pandas for data wrangling

Jupyter Notebook for interactive code and documentation

Contributing

Contributions are welcome! To contribute:

Fork this repository.

Create a new branch.

Commit your changes.

Open a pull request.
