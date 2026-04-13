# Used Vehicle Retail Database Structure

### Table Name
```vehicles```

### Structure
- id | INT NOT NULL UNIQUE AUTO_INCREMENT PRIMARY KEY
- name | VARCHAR(100) NOT NULL INDEX
- brand | VARCHAR(50) NOT NULL INDEX
- body_type | VARCHAR(100) NOT NULL INDEX
- power | INT NOT NULL
- gearbox | VARCHAR(50) NOT NULL
- engine_size | INT NOT NULL
- gears | TINYINT NOT NULL
- cylinders | TINYINT NOT NULL
- empty_weight | INT NOT NULL
- emission_class | VARCHAR(20) NOT NULL
- drive_train | VARCHAR(50) NOT NULL
- seats | TINYINT NOT NULL
- doors | TINYINT NOT NULL
- warranty | TINYINT NOT NULL
- mileage | INT NOT NULL
- first_registration | DATE NOT NULL
- last_inspection | DATE NOT NULL
- previous_owner | TINYINT NOT NULL
- colour | VARCHAR(20) NULL
- paint | VARCHAR(20) NULL
- price | DECIMAL(8, 2) NOT NULL

## Examples

| id | name | brand | body_type | power | gearbox | engine_size | gears | cylinders | empty_weight | emission_class | drive_train | seats | doors | warranty | mileage | first_registration | last_inspection | previous_owner | colour | paint | price |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| 1 | Golf 1.4 TSI | Volkswagen | Compact | 110 | Manual | 1395 | 6 | 4 | 1205 | Euro 6 | Front | 5 | 5 | 12 | 45000 | 2019-05-15 | 2023-06-10 | 1 | Silver | Metallic | 15450.00 |
| 2 | Civic 1.5 VTEC Turbo | Honda | Compact | 182 | Automatic | 1498 | 7 | 4 | 1250 | Euro 6d-TEMP | Front | 5 | 4 | 24 | 30000 | 2020-03-20 | 2023-05-01 | 1 | Red | Solid | 18900.00 |
