# Cars Database

## Table name

- cars

## Table comumns

- id | PRIMARY KEY, AUTO_INCREMENT, BIGINT, UNIQUE, NOT NULL
- brand | CHAR(20), NULL
- model | CHAR(20), NULL
- year | YEAR, NULL
- plate | TINYINT, UNSIGNED, NULL, UNIQUE
- km | MEDIUMINT, UNSIGNED, NULL
- fuel | CHAR(20), NULL
- price | DECIMAL(9, 2), NULL
- type | CHAR(20, NULL)
- color | CHAR(20, NULL)
- lateral_photo | VARCHAR(255), NULL
- frontal_photo | VARCHAR(255), NULL
- internal-photo | VARCHAR(255), NULL
- note | TEXT, NULL
- is_avaible | BOOLEAN, NULL
- location | VARCHAR(50), NULL
- contact | VARCHAR(255), NULL