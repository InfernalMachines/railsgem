#Chart Kick Gem

##To Install<h2>

NOTE:* Does not work with SQL Lite. Switch over to Postgresql

To use PostgreSQL in your environment:

=> Goto: the Config folder in your rails project
=> Open the Database.yml file
=> Edit Development Line: Delete or comment out // *default database: db/development.sqlite3 //
=> Add PostGreSql Adaptor: 
==> development:
==> adapter: postgresql
==> encoding: unicode
==> database: chartkick_db
==> pool: 5
=> Save

Install the following Dependencies

GroupDate:
HighTop
Active_Median
Add the following to your Gem file:

==> gem 'groupdate'
==> gem 'chartkick'
==> gem 'hightop'
==> gem 'active_median'
Bundle Install in terminal

Add the following links to the head of you page

< %= javascript_include_tag "//www.google.com/jsapi" %>
< %= javascript_include_tag "application", "chartkick" %>

For more information on working with ChartKick go to GitHub: ChartKick Site

