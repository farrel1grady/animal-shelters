# Animal Shelters Cost to Run

-- Project Status : [Completed]

Postgre SQL

## Project Description
Calculate the cost of running animal shelters based on animal size, age, and location. These calculations should not include animals that private charities have sponsored.
For visualization purposes, I will add a percentage column that reflects the fraction of total cost to each animal and size combination.

## Tables Used
1. animals
2. sponsored_animals
3. location_costs
4. age_costs
5. size_costs

## Outcome
| animaltype        | size           | Total  | Percentage|
| :---------------: |:--------------:|:------:| :--------:|
| Bird              | Small          | 1615   | 0.05      |
| Bird              | Medium         | 3130   | 0.09      |
| ...               | ...            | ...    | ...       |
| Dog               | Medium         | 941895 | 27.09     |
| Dog               | Large          | 977665 | 28.12     |
