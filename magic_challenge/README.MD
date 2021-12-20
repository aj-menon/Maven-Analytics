## The Maven Magic Challenge

### Introduction

The Maven magic challenge is a part of the @MavenAnalytics data challenge, December 2021. The goal of the challenge is to analyse the Harry Potter Movies dataset and vizualize the magic of Harry Potter movies. The analysis and visualizations are done in Microsoft Power BI.

### The Data

The dataset contains the character dialogues for all 8 movies in the Harry Potter franchise, including additional information about each movie, its chapters, characters, places, and spells.

This dataset contains 6 tables in CSV format

- The Dialogue table contains all 7,444 lines of dialogue from the 8 Harry Potter movie scripts, and contains foreign keys that can be matched to a specific chapter, character, and place from the Wizarding World
- The Chapters table contains the 234 chapters from the Harry Potter movie scripts, with fields containing the chapter name and number, and the related movie
- The Movies table contains the 8 movies from the Harry Potter series, with fields containing the movie title, release year, runtime, budget, and box office revenue
- The Characters table contains the 166 characters that had lines of dialogue in the movies, with fields containing the character’s name, species, patronus, and more!
- The Places table contains 74 locations from the Wizarding World, with fields containing the place name and category (Hogwarts, Hogsmeade, etc.)
- The Spells table contains the 61 spells cast in the movies, with fields containing the incantation, spell name & effect, and the color of the light cast

### Data Source

The dataset can be downloaded from the Maven Analytics [data playground](https://www.mavenanalytics.io/data-playground?search=harry%20potter)
