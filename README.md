# NBA_Project

Summary:

Our original objective was to analyze various NBA metrics to find the optimal Fanduel fantasy basketball lineup. We were able to scrape NBA.com and create a SQLite database with minimal challenges. However, connecting the Flask app and rendering meaningful graphs was considerably more difficulty than we thought it would be. In the end, we were able to assemble a filterable table with data from Flask, graphs using D3 and Plotly, JQuery for DOM animation and effects, and some pretty sweet animated GIFs.

Fanduel Points Structure:
3-Point Shot Made (3P): 1 Point
Assists (A): 1.5 Points
Blocks (B): 3 Points
Field Goal Made (FG): 2 Points
Free Throw Made (FT): 1 Points
Rebounds (R): 1.2 Points
Steals (S): 3 Points
Turnovers (T): -1 Point

Conclusions:
Getting a custom SQLite database to run through a Flask app was very challenging. In addition, having each person work on individual pieces and trying to patch the pieces together proved to be difficult. We set out to tell a story of how historical metrics factor into finding the perfect fantasy basketball lineup. However, the story we ended up telling was about how difficult it is to distill data down to a level that can be shared in a web app.

If we had more time we would have:
- Combined our HTML and JavaScript files to be consistent
- Connected all of the graphs to the Flask app
- Separated each of the metrics by position
- Analyzed each of the metrics for correlation with future performance