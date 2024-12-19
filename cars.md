# Used Cars

### Context:

Data Table for one car.

| name                | type          | null | default | attribute               | key     | note                                                                            |
| ------------------- | ------------- | ---- | ------- | ----------------------- | ------- | ------------------------------------------------------------------------------- |
| id                  | BIGINT(20)    | no   | none    | UNIQUE - AUTO-INCREMENT | PRIMARY | Unique identifier for each car record                                           |
| vin                 | CHAR(17)      | no   | none    | UNIQUE                  |         | Vehicle Identification Number, a globally unique identifier for the car         |