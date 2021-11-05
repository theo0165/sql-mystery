# SQL Airport Mystery

![](https://i.giphy.com/media/Yiw4aLjpxldhC/giphy.webp)

To get started, download the [`sql-mystery.sqlite`](sql-mystery.sqlite) file.

#### Instructions

You have found out that there has been a high level security observation in the morning of the 27 October 2021. Check the security observations for further clues and find out what happend.

#### Solution

If you think you found the solution to the airport mystery, run the following query in the sqlite database.

```sql
INSERT INTO solution (user, value) VALUES (1, "Name of the person");
SELECT * FROM solution;
```