# Used Cars

### Context:

Data Table for one car.

| name                | type          | null | default | attribute               | key     | note                                                                            |
| ------------------- | ------------- | ---- | ------- | ----------------------- | ------- | ------------------------------------------------------------------------------- |
| id                  | BIGINT(20)    | no   | none    | UNIQUE - AUTO-INCREMENT | PRIMARY | Unique identifier for each car record                                           |
| vin                 | CHAR(17)      | no   | none    | UNIQUE                  |         | Vehicle Identification Number, a globally unique identifier for the car         |
|color      | CHAR()      | no   | none    |                         |         | The color of the car as it was originally painted by the manufacturer           | 