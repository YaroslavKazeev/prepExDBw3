# Prep exercise week 3

As a preparation step for the upcoming Q&A, you need to work on the following exercise, which is based on the prep
exercise of the previous week.

## Exercise

Last week you created an ERD for the database for storing food recipes.
How can you normalize your database based on what you learned this week?
In particular, try answering following questions and provide table definitions from the last week
and this week to explain the changes.

- Was your database already in 2NF / 3 NF?

My database was not previously in 1NF, because the
The recipe_steps table contained the text content of each step, which may lead to duplicate values with different PKs.

- What changes did you have to do to normalize your database?

I split the recipe_steps table into recipe_steps and steps tables.

## Discussion

- If you want to add thousands of recipes to your database, what challenges do you foresee?

At this point, the structure is sound, and it will not be more difficult to control the DB.

- Try to write answers to these questions in text, provide queries and commands when necessary.
