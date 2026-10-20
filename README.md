## What I'm learning

I'm exploring football scouting through data and Python.

Some of the techniques I'm learning and experimenting with include:

- Collecting football statistics from REST APIs
- Storing player profiles in SQLite
- Comparing player statistics using cosine similarity
- Calculating per-90 metrics to account for playing time
- Testing Python functions and improving data quality

This repository is a place to document my progress and share what I learn while building my football scouting project.

## How I compare players

I use statistical features to compare football players with similar profiles.

My approach focuses on:
- Normalizing statistics per 90 minutes
- Representing players as numerical feature vectors
- Using cosine similarity to compare their statistical profiles
- Interpreting similarity scores as a ranking tool, not a definitive measure of player quality

The goal is to support scouting decisions with data, not replace human scouting judgment.
