# Athletic Events scheduling Database and Its Entity Relationship Diagram (ERD)

### Introduction

This is an anthletics events database consisting of 8 tables and their ERD. The PostgreSQL pgAdmin was used to create tables, insert data into tables, and process the data. Visual Paradigm was used to create ERD. In summary, the ERD descibeed the database where `Customer` can request an `EventRequest`, the `EvenPlan` for which is managed by an `Employee` (can manage zero or multiple `EventPlan`(s)). Each `EventPlan` has an `EventPlanLine` or a time line (weak entity: identifying relationship). Zero or one resource are provided for each `EventPlanLine`. Each `EventPlanLine` has a `Location` , which is in a `Facility` and `Facility` number is referenced in the `Event`.


### Events Entity Relationship Diagram

<img src="/ERD/ERD.png" width="400">