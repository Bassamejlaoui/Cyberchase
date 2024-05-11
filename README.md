## Cyberchase

![cyberchase](https://github.com/mejbass/Cyberchase/assets/130122304/24707fce-3d7e-40c5-a594-d820cb5cbf82)

## Overview

This project is part of CS50’s Introduction to Databases with SQL OpenCourseWare, focusing on querying and analyzing data related to the television series "Cyberchase". The Cyberchase series, aired by the United States’ Public Broadcasting Service (PBS) since 2002, blends entertainment with education, emphasizing math, science, and problem-solving skills through animated adventures.

## Table of Contents

- [Demo](#demo)
- [Distribution Code](#distribution-code)
- [Schema](#schema)
- [Specifications](#specifications)
- [Usage](#usage)
- [How to Test](#how-to-test)
- [Correctness](#correctness)
- [How to Submit](#how-to-submit)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Demo

The project includes a database called `cyberchase.db` and several `.sql` files containing queries to analyze the data.

## Distribution Code

To get started, download the distribution code by executing the following commands in your terminal:

```bash
cd
wget https://cdn.cs50.net/sql/2024/x/psets/0/cyberchase.zip
unzip cyberchase.zip
rm cyberchase.zip
cd cyberchase
```

This will provide you with the necessary files, including `cyberchase.db` and `.sql` files for queries.

## Schema

The database `cyberchase.db` contains a single table called `episodes`, which includes the following columns:

- `id`: Unique identifier for each episode
- `season`: Season number in which the episode aired
- `episode_in_season`: Episode number within its given season
- `title`: Title of the episode
- `topic`: Topic the episode aimed to teach
- `air_date`: Date on which the episode aired
- `production_code`: Unique ID used by PBS to refer to each episode internally

## Specifications

The project provides a set of specifications to guide the writing of SQL queries. Each query focuses on different aspects of the Cyberchase episodes, such as listing episode titles, finding production codes, or counting episodes within specific timeframes.

## Usage

To execute SQL queries, use the following command:

```bash
sqlite3 cyberchase.db
```

Then, within the SQLite shell, run:

```bash
.read FILENAME.sql
```

Replace `FILENAME` with the name of the SQL file containing your query.

## How to Test

To test your queries, ensure they produce the expected outputs:

- Executing `1.sql` should result in a table with 1 column and 26 rows.
- Executing `2.sql` should result in a table with 2 columns and 14 rows.
- Executing `3.sql` should result in a table with 1 column and 1 row.
- Executing `4.sql` should result in a table with 1 column and 26 rows.
- Executing `5.sql` should result in a table with 1 column and 1 row.
- Executing `6.sql` should result in a table with 1 column and 2 rows.
- Executing `7.sql` should result in a table with 2 columns and 6 rows.
- Executing `8.sql` should result in a table with 1 column and 1 row.
- Executing `9.sql` should result in a table with 1 column and 1 row.
- Executing `10.sql` should result in a table with 3 columns and 140 rows.
- Executing `11.sql` should result in a table with 1 column and 10 rows.
- Executing `12.sql` should result in a table with 1 column and 1 row.
- `13.sql` is left for exploration.

Note: Row counts do not include header rows showing column names.

## Correctness

You can also check your code using `check50`, a program provided by CS50 to test your code when you submit.

```bash
check50 cs50/problems/2024/sql/cyberchase
```

## How to Submit

To submit your work, execute the following command in your terminal:

```bash
submit50 cs50/problems/2024/sql/cyberchase
```

## Acknowledgements

Data retrieved from [Wikipedia](https://en.wikipedia.org/wiki/List_of_Cyberchase_episodes).

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
```
