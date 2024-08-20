## SQL Examples

In this SQL repository, I will continue adding new SQL examples that are useful for data analytics. In some documents, the first part contains the fabricated dataset for demonstration and the following part contains the SQL querying examples. In others only SQL querying examples are shown.

The examples contain both standard SQL and PostgreSQL syntax. SQL queries are written and tested using SQLite Studio.

The types of SQL statement include the following:

* `create table`
* `drop table`
* `select` `from`
* `where` `and`
* `order by (asc or desc)`
* `group by`
* `having`  (used below group by)
* `case` `when` `then` `else` `end as`
* `inner join` and `left join`, `on`
* `date()`
* Statement for subquery
* Statistics such as `count`, `max`, `min`, `sum`, `avg`
* `distinct`
* `where` `between` `and`
* `like` with `%` showing the matching scenarios
* **Common Table Expressions (CTEs)** using `with TempName as`
* `'TagName' as tag`
* **Window Functions** to get statistics across a set of rows instead of just one row: `avg(ColName) over (partition by GroupByColName) as "NewColName"` `rank() over (partition by GroupByColName group by RankBasedColName) as "NewColName"` where the rank is within each group

 