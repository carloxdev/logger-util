# LoggerUtil

Library for a faster logger implementation

## Requirements

+ Python >= 3.6

## Getting Started

You can install the library with the following command:

    $ pip install logger-util

Create a logger:

    from logger_util.log_admin import LogEnvironment
    from logger_util.log_admin import LogAdmin

    logger = LogAdmin.create_Logger(LogEnvironment.PRODUCTION, "app")

By default the entry log will show the timestamp. If you don't need it just set in false the variable "_timestamp":

    logger = LogAdmin.create_Logger(LogEnvironment.PRODUCTION, "app", _timestamp=False)
