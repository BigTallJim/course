## Creating Your First Table

[Back to the Challenge Map](00_challenge_map.md)

Now that we have a database set up we would like to be able to interact with it, and persist data in it.  There are a number of ways to do this.  A simple method is to do that through the `psql` command line tool.  In the long run we shouldn't rely on this approach but it's important to practice with it as a backup in order to sanity check how the database is set up.

## Learning Objectives covered

* Use the `psql` command to interact with Postgres
* Know that 'SQL' means 'Structured Query Language'
* Explain how SQL is used to query databases
* Use SQL query terms like `SELECT`, `FROM`, `WHERE`, and `*`

## To complete this challenge, you will need to

- [ ] List the existing database via `psql`
- [ ] Connect `psql` to an existing database
- [ ] List the tables in that database
- [ ] Create a basic table called 'students' with a single primary key (id) and name field
- [ ] List the existing tables again to check 'students' shows up

## Resources

* [PostgreSQL Command Line Cheat Sheet](http://blog.jasonmeridth.com/posts/postgresql-command-line-cheat-sheet/)
* [SQL in One Page](http://www.cheat-sheets.org/sites/sql.su/)

## [Solution](solutions/04.md)