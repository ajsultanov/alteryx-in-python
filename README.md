## Working through Alteryx Weekly Challenges in Python/pandas

> Use the Output Tool to export CSVs from the yxmd files attached to the posts.

- ✅ [🟡 Challenge #1: Join to Range](https://community.alteryx.com/discussion/comment/1227047)
- ✅ [💚 Challenge #2: Preparing Delimited Data](https://community.alteryx.com/discussion/comment/1228000)
- ✅ [🟡 Challenge #3: Running Averages](https://community.alteryx.com/discussion/comment/1234483)
- ✅ [🟥 Challenge #4: Date Parsing](https://community.alteryx.com/discussion/comment/1227055)
  - [pandas anti-patterns](https://www.aidancooper.co.uk/pandas-anti-patterns/)
- [Challenge #5: HR Position Finder Application](https://community.alteryx.com/discussion/comment/1227064)
- [🟡 Challenge #6: Spatial Route](https://community.alteryx.com/discussion/comment/1227094)
- [🟥 Challenge #7: Download Data and Parse JSON](https://community.alteryx.com/discussion/36734/challenge-7-download-data-and-parse-json)
- [💚 Challenge #8: Aggregate Consumer Purchases](https://community.alteryx.com/discussion/36735/challenge-8-aggregate-consumer-purchases)
- [💚 Challenge #9: Analytics Ranking](https://community.alteryx.com/discussion/36736/challenge-9-analytics-ranking)
- [🟡 Challenge #10: Date Time Calculations](https://community.alteryx.com/discussion/36737/challenge-10-date-time-calculations)

#### Steps for using SQLite

- Open project folder in VSCode
- Open terminal
- `> sqlite3 [database name].db`
  - creates database file
- `> .mode csv`
- `> .mode`
  - to check it's been changed from list
- `> .import [file name].csv [file name in database]`
  - imports table
  - ex: `.import sales.csv sales`
- `> .schema`
  - to check table
- `> .exit`
  - to close sqlite
- Can close terminal
- Click on database icon on left side panel
- Create new connection
- Enter name and group (optional)
- Select SQLite server type
- Use menu to enter path to database file
- Connection should be open
- Create [file name].sql in project folder
- Can write queries here and execute them against the SQLite database
  - Will not work if connection is closed

> [SQLite functions reference](https://sqlite.org/lang_corefunc.html)
