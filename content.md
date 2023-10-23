# Ideas Tool

Here is our Ideas tool for generating data models:

[ideas.firstdraft.com](https://ideas.firstdraft.com/)

Sign in with GitHub to create an account.

## Getting started

Once you login you can create a new "Idea" by clicking the green plus icon near the top right of the screen.

---

![](/assets/new-idea.png)

---

Once you click that you should see a form where you can choose a name for your project.

---

![](/assets/new-idea-2.png)

---

Once, you've named it click "create" to proceed.

## Adding tables

You can add tables to the canvas by clicking on and dragging the green plus icon onto the canvas.

If the table represents a "user" or someone who will sign up and sign in, check the "User Accounts?" checkbox to get an email and password column.

![](/assets/new-table.gif)
{: .bleed-full }

## Adding columns

You can add columns to a table by clicking the green plus icon in the header of a table.

A dialogue should popup and prompt you to choose a column name. You're also required to choose a data type for the column.

![](/assets/adding-columns.gif)
{: .bleed-full }

## Editing columns

If you made a mistake selecting a column's data type or if want to rename that column you can click on the pencil icon next to the column, and the same form will popup and allow to make changes.

![](/assets/editing-columns.gif)
{: .bleed-full }

## Direct associations

To draw a direct association line between two tables and establish a one-to-many relationship, one table needs to have a foreign key column.

<div class="bg-red-100 py-1 px-5" markdown="1">

This foreign key column must be an `Integer` type.
</div>

Once you have your two tables created with the foreign key column click and drag the id column of the table and drop it onto the foreign key column in the other table.

If everything was successful, a dialogue will popup and the first two questions will prompt you to choose a name for each side of the association.

![](/assets/direct-associations.gif)
{: .bleed-full }

## Indirect associations

In order to draw the dashed indirect association line between two tables and establish a many-to-many relationship, you need to first draw the two direct associations between each table and the connecting join table.

![](/assets/indirect-associations-1.png)
{: .bleed-full }

Once those direct associations have been built, click and drag the blue double-headed arrow from one of the two tables in the many-to-many and drop it anywhere on the other table.

A dialogue should pop up and ask you to pick which two associations make up the larger many-to-many relationship that you're trying to draw.

Once you select the two associations, you can choose more specific names for each side of the many-to-many.

![](/assets/indirect-associations-2.gif)
{: .bleed-full }

---
