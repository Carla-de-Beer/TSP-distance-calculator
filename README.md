# Travelling Salesman Distance Calculator
[![GitHub issues](https://img.shields.io/github/issues/Carla-de-Beer/JavaScript.svg?style=flat-square)](https://github.com/Carla-de-Beer/TSP-Distance-Calculator/issues)

This project demonstrates the use of a genetic algorithm to find an optimised solution to the Travelling Salesman Problem. The program dynamically reads in city data from a file and calculates the shortest distance it can find, linking all cities. The actual physical distance on the route, calculated as the [Haversine](https://en.wikipedia.org/wiki/Haversine_formula) distance, is also shown. Specifiable genetic algorithm parameters include the crossover rate, mutation rate, population size, max. no. iterations and elitism generation gap.

## Development Notes
* Built with P5.js.
* Linting is provided by ESLint. To run the linter, install npm via `npm install`, followed by `npm install eslint --save-dev`. To run the lint tests, type in the command `npm run lint`.

## Resources
* City data obtained from: https://gist.github.com/Miserlou/c5cd8364bf9b2420bb29
* The crossover strategy makes use of Modified Order Crossover (MOX), as described in:
http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.91.9167&rep=rep1&type=pdf
* Haversine distance formula:
http://stackoverflow.com/questions/27928/calculate-distance-between-two-latitude-longitude-points-haversine-formula
* Map from MapBox; https://www.mapbox.com/api-documentation/#retrieve-a-sprite-image-or-json

## Links
* The website can be viewed via the following URL: https://carla-de-beer.github.io/TSP-Distance-Calculator/
* View the project video here: https://vimeo.com/206750609

</br>
<p align="center">
  <img src="gif/TSP Distance Calculator.gif"/>
</p>
