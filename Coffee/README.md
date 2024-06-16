MySQL said: Identifier name 'How do you brew coffee at home? (Coffee brewing machine (e.g. Mr. Coffee))' is too long

> Renamed some columns

MySQL said: Row size too large. The maximum row size for the used table type, not counting BLOBs, is 65535. This includes storage overhead, check the manual. You have to change some columns to TEXT or BLOBs

> Change column types to TEXT

MySQL said: The storage engine for the table doesn't support nullable columns

> https://groups.google.com/g/sequel-pro/c/PZVrYyEXrJc/m/647e_PBQBbcJ

found out that mysql stores boolean columns as `TINYINT(1)` instead of `BOOLEAN`. interesting!