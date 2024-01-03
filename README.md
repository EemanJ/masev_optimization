# MAS EV Optimization

Multi-Agent Based Systems simulation to simulate an electric vehicle charging network in the city of Montreal.
This project aims to optimize the positioning of the SuperChargers but also the number required for a given number of electric vehicles for the most optimized return on investment. An iterative approach is taken, from a singular base scenario, changing the locations and number of chargers with each iteration.

It must be noted that several assumptions were made for the purposes of this project, owing to time limitations. Hence this is a proof-of-concept model and is to be used as such. The results are accurate based on the assumptions made, but will change as real values are used.

A full video of the project simulation description, as well as scenarios is available at this [link]([url](https://drive.google.com/file/d/1Chhf0A1400qCOFxB3iUmxyvtuYOeOlb-/view?usp=sharing)).

This project covers a total of 4 sceanrios:
1- Base scenario-this has a total of five superchargers located in different parts of the city, of which two are adjacent to one another.
2- Scenario 1-this scenario still uses five superchargers but the charger generating the least amount of revenue is moved to a busier location.
3- Scenario 2-One of the two adjacent superchargers is removed, reducing the total number of superchargers to four. This yielded much better results than the previous two.
4- Scenario 3-Further reduced the number of superchargers to three to see which are the best results.

Further description and details are provided in the PDF file part of this repository.

This project can be cloned and the .alp extension file can be run on AnyLogic.

AnyLogic Personal Learning Edition 8.6.6 was used for the purposes of this project.
