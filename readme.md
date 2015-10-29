# db-truncate

db-truncate truncates MySql database tables to specified number of rows. It's useful for 
developing purposes when you want to reduce database size and preserve its structure.

### Installation

db-truncate requires PHP >= 5.3

```
composer global require idealogica/db-truncate:~1.0.0
```

### Usage

```
db-truncate [-u username (root)] [-p password] [-h host (localhost)] [-P port] [-S unix socket] [-e comma-separated tables to exclude (changelog)] database [records to keep (500)]
```

### License

db-truncate is licensed under a [MIT License](https://opensource.org/licenses/MIT).