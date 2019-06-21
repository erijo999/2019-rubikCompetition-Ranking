# 2019-rubikCompetition-Ranking
## Finding the best country at solving Rubik's Cube 3x3x3!

Members:

* Pablo Aliaga
* Eric Jonsson
* Erick Lemus

For our project we wanted to rank countries according to how good they are at solving rubik Cubes.
To achieve that we use a data-set from [World Cube Association data sets](https://www.worldcubeassociation.org/results/misc/export.html)

In this project a lot of results were obtained, here's an explanation:

  
1. averageResults
... 1. raw: ranking of the countries with best average at solving Cubes
... 2. withCount: also has the info of the numbers of Competitors of each country
... 3. withoutSmallCountries: it excludes countries with less than 10 persons.

2. orderByAmount: rank of countries with most competitors
3. competitiveAverageResults: rank of the countries with best Average excluding solving times grower than 30 sec.
4. pabloScoreResults --> here we use a Score that was created to give bonus to countries by its competitors and time
  1. First attempt, initial Score formula
  2. Second attempt, better formula
  3. Third attempt, and better...
  4. Fourth attempt, and so forth ...

5. finalPabloScoreResults: here we use the final formula that got the most reasonable results of all according to us
6. finalErickScoreResults: here is an alternative of another formula to get the best countries at solving cubes

