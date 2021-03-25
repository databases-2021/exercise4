# Exercise 4

Name:

---

## Getting started

1. Accept the assignment in GitHub classroom
1. Clone this repository
1. Commit & push your answers to GitHub

*Before committing check the [checklist](https://github.com/databases-2021/exercise-checklist)*

Remove this section before committing your answers.

---

## Goals

1. Create a table.
1. Seed the table.
1. Write specific `SELECT` queries.

## Import the Database

Import the [`gamereviews_example.sql`](gamereviews_example.sql) file in your database to get access to the tables for this exercise.

Execute the following command in this project directory with the `mysql` client:

```sql
source gamereviews_example.sql
```

Answer every question with:

1. The query that answers the question.
1. The results of that query.

Every query that returns more than 10 row must be reduced to the first 10 rows. (HINT you can do this in you query).

## Exercise

1. Give a list of names of all tables in the `gamereview_example` database.

    Query:

    ```sql

    ```

    Result:

    ```text

    ```

1. Give all column names and types for the tables `games`.

    ```sql

    ```

    ```text

    ```

1. Answer short but complete on the next questions about the `users` table. Don't answer with a query for these questions.

   1. Do you need to provide a `name`? **ANSWER HERE**
   1. Do you need to provide a `lastname`? **ANSWER HERE**
   1. Do you need to provide an `email`? **ANSWER HERE**
   1. What is the maximal length of a password? **ANSWER HERE**

1. Give a list of all names of the `games`.

    ```sql

    ```

    ```text

    ```

1. Give a list of all names of the `users` in alphabetical order.

    ```sql

    ```

    ```text

    ```

1. Give a list of the 10th until the 20th `publishers` that are ranked alphabetically.

    ```sql

    ```

    ```text

    ```

1. What is the amount of `games` that are stored in the database?

    ```sql

    ```

    ```text

    ```

1. What is the amount of `games` in the database that are a multiplayer game?

    ```sql

    ```

    ```text

    ```

1. Give a single query that show the amount of users, amount of games and the amount of reviews in the database.

    ```sql

    ```

    ```text

    ```

1. How many `reviews` have a score less than 2?

    ```sql

    ```

    ```text

    ```

1. Give a top 3 of the best `reviews`.

    ```sql

    ```

    ```text

    ```

1. How many `reviews` has the `game` with id: `20626`?

    ```sql

    ```

    ```text

    ```

1. What is the `id` of the `game` with the most amount of reviews?

    ```sql

    ```

    ```text

    ```

1. What is the `name` of the `game` with the most amount of reviews?

    ```sql

    ```

    ```text

    ```

1. What is the average score for the `game` with `id`: `20991`

    ```sql

    ```

    ```text

    ```

1. What is the average score for the `game` with `name` "Halo 3"

    ```sql

    ```

    ```text

    ```

1. Give a list of games that contain the text `battle`.

    ```sql

    ```

    ```text

    ```

1. What is the `name` of the `user` that wrote the most reviews?

    ```sql

    ```

    ```text

    ```

1. Give a list of names and average scores for the 10 best `games`.

    ```sql

    ```

    ```text

    ```

1. Give the names of the `users`, and the amount of games they own.

    ```sql

    ```

    ```text

    ```

1. Give the names of the 3 most expensive `games`. Also give the `name` of the `publisher` of those `games`.

    ```sql

    ```

    ```text

    ```

1. Give the top 3 of the total amount of money that the `users` spent on `games`, and the name of those `users`.

    ```sql

    ```

    ```text

    ```

1. Give a top 3 of the names and the average score of the `publishers` of which the `games` have the best `reviews`.

    ```sql

    ```

    ```text

    ```

1. Return a JSON object that contains the `id`, `name` and `price` of the 5 last added `games` in the database.

    ```sql

    ```

    ```text

    ```
