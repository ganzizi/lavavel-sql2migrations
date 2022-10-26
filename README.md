# lavavel-sql2migrations

A script to genenerate Laravel migrations from existing MySQL database.

It isn't super comprehensive and is meant to quicken the setting up of Laravel migrations on an existing database.

# Specs

PHP 8

# Set Up

1. fill database connection details in ./config.json

# Run

## config.json

only_include_tables - takes precedence if tables are specified

exclude_tables - tables will be excluded

## terminal

```

### php

```
php -e start.php
```

or

```
php -e start.php (config file)
```

# Output

Files will be in output folder

# Contribution

Feel free to report any bugs or contribute!
