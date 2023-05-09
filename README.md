# LanguageSpecificMovieDatasets

##**Introduction**##
This repository contains language-specific datasets that provide information on the most popular movies from a given country available on TMDB as of May 2023. The data was collected by a Python script through the TMDB API, entries were then filtered to remove any film that had "overview", "release_date" and "vote_average" data missing. Some details such as "genre", "duration", etc. where omitted but they can be easily retrieved with TMDB API by use of movie_id parameter from the "id" column.

##**Contents**##

| Language            | Number of entries | 
| ------------------- |:-----------------:|
| English (American)  | 9777              |
| Italian             | 6118              |
| French              | 6118              |
| German              | 6118              |
| Polish              | 6118              |
| Danish              | 6118              |
| Spanish             | 6118              |
| Portoguese          | 6118              |

- **id**:  Contains the TMDB's id for the movie;
- **title**: Contains the title of the movie;
- **overview**: Contains a description of the movie, usually a logline;
- **release_date**: Contains the release date of the movie;
- **vote_average**: Contains the arithmetic average of the user's votes;
   
    
