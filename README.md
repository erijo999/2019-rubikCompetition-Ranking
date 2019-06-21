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
    * raw: ranking of the countries with best average at solving Cubes
    * withCount: also has the info of the numbers of Competitors of each country
    * withoutSmallCountries: it excludes countries with less than 10 persons.

2. orderByAmount: rank of countries with most competitors
3. competitiveAverageResults: rank of the countries with best Average excluding solving times grower than 30 sec.
4. pabloScoreResults --> here we use a Score that was created to give bonus to countries by its competitors and time
    * First attempt, initial Score formula
    * Second attempt, better formula
    * Third attempt, and better...
    * Fourth attempt, and so forth ...

5. finalPabloScoreResults: here we use the final formula that got the most reasonable results of all according to us
6. finalErickScoreResults: here is an alternative of another formula to get the best countries at solving cubes

