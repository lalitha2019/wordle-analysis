A fun exercise in python, using matplotlib

Objective: To experiment with and learn visualizations using matplotlib, and to have some fun

Task: To analyze frequency of occurence of any given letter in wordle solutions

Data: List of wordle solutions collected over a period of time

Features:
The very first visualization that pops up by default shows the occurrence of letter 'a' across all days.
User can then select a different letter and the start day. Then the occurrence of that lette in words for 5 consecutive days from the selected number of day will be displayed.

Known limitations: 
- Day count is shown instead of a more friendly date. Day count starts from 0 instead of from 1
- Letter occurrence is shown only for 5 consecutive days from a chosen number of day. Only at the beginning the frequency is shown across all days for letter 'a'. Once the user types a different letter, it starts showing only for 5 days.
- Error handling hasn't been added at this time
  
Unknowns: There could be mistakes as I tested quickly and not exhaustively.

Goals for improvement: Improvement goals: Remove known limitations

Goals for Enhancement: 
- Add a feature to show occurrence of a letter for all days as well as for select number of days.

Time taken: 3 days
(I wrote this around 2022 December, when I was trying to learn new skills while searching for a job)

Files:
- wordle-data - text file - has the collection of wordle words used in this project. 
- wordle_analysis.py - python code
- Default-Visualization.jpg - screenshot of default visualization that pops up when the code is run
- Letter-E-day14-to-day18.jpg - screenshot of viualization when user selects letter 'e'
- Letter-E-first-5-days.jpg - screenshot of visualization when user selects letter 'e' and slides to day number '13'
