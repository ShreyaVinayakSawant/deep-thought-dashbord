# deep-thought-dashbord
Overview
The "Data Champion Project" analyzes participants' performance in basic and advanced screenings. This Excel file contains structured data capturing individual scores, aggregated metrics, and their categorization into various performance levels. Additionally, it integrates data visualization capabilities to provide insights into participants' achievements.

File Structure
The workbook comprises four sheets, each serving a unique purpose:

1. Basic Screening
Purpose: Captures responses and scores from participants for the basic screening phase.
Key Details:
Number of Entries: 308
Columns:
Timestamp: Records when the entry was submitted.
Question1 to Question5: The questions presented in the basic screening.
score for Q1 to score for Q5: Individual scores for each question.
Name: The participant's name.
basic: Total score achieved in the basic screening.
Notes: The "Email Address" column is empty.


3. Advanced Screening
Purpose: Contains responses and scores for the advanced screening phase.
Key Details:
Number of Entries: 282
Columns:
Similar structure to the "Basic Screening" sheet, with columns for individual questions and scores.
advanced: Total score achieved in the advanced screening.
Notes: The "Email Address" column is empty.


4. Merge Basic and Advanced
Purpose: Combines data from the "Basic Screening" and "Advanced Screening" sheets for comprehensive analysis.
Key Details:
Number of Entries: 312
Columns:
Timestamp: Records when the entry was submitted.
Email Address: Participant's email address (fully populated).
Question1 to Question5 and their respective scores from the basic and advanced screenings.
basic and advanced: Total scores for the basic and advanced screenings, respectively.
total score: Combined score from both screenings.
percentage: Performance expressed as a percentage.
category: Participant's performance category based on their score.
rank: Rank assigned based on the total score.

5. Visualizations
Presents graphical insights into the data.
Key components:
Sum of Total Based on Name: A bar chart displaying individual total scores.
Category Count: A pie chart illustrating the distribution of participants in categories:
Green (76%): Top performers.
Yellow (21%): Average performers.
Red (3%): Below-average performers.
Sum of Rank: A bar chart showing the sum of ranks for each category.
Basic vs. Advanced: A line graph comparing basic and advanced scores for each participant.
