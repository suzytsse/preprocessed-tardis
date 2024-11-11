# preprocessed-tardis
This project is mean to preprocess the <a href='https://github.com/rfordatascience/tidytuesday/blob/master/data/2021/2021-11-23/readme.md'> Dr. Who dataset </a>
 with python before analysing on vega lite.

## Data Dictionary

### `directors.csv`

|variable     |class     |description |
|:------------|:---------|:-----------|
|story_number |character | Story number |
|director     |character | Director |

### `episodes.csv`

|variable        |class     |description |
|:---------------|:---------|:-----------|
|era             |character |Era = Classic or revived |
|season_number   |double    | Season number |
|serial_title    |character | Serial title |
|story_number    |character | Storu number |
|episode_number  |integer   | Episode number |
|episode_title   |character | Episode title |
|type            |character | Type |
|first_aired     |double    |First aired date |
|production_code |character |Production code |
|uk_viewers      |double    | UK Viewership in Millions |
|rating          |double    | Rating |
|duration        |double    | Duration in minutes|

### `writers.csv`

|variable     |class     |description |
|:------------|:---------|:-----------|
|story_number |character | Story number |
|writer       |character | Writer |

### `imdb.csv`

|variable |class     |description |
|:--------|:---------|:-----------|
|season   |integer   | Season number |
|ep_num   |double    |Episode number |
|air_date |character | Air date |
|rating   |double    | Rating|
|rating_n |double    | Number of ratings |
|desc     |character | Episode description |

