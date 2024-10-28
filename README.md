[![MIT License on GitHub](https://img.shields.io/github/license/seankelliher/mt-washington-temps?style=flat-square)](/LICENSE.md)
## Mt. Washington Temperatures

Chart of average monthly temperatures at the Mt. Washington Observatory. Built with Vue.js and Chart.js. [View working component](https://sean-kelliher-mt-washington-temps.netlify.app).

## Project Status

Project meets general accessibility (WACG) and cross-browser requirements. More testing with a dedicated services (e.g., Sauce Labs) would be helpful if deploying to production.

## Project Screen Shot

* Intro page.
![screen shot of project](/screenshots/mt-washington-temps-screenshot1.png?s=600)

* Chart.
![screen shot of project](/screenshots/mt-washington-temps-screenshot2.png?s=600)

## Installation and Setup Instructions

Clone down this repository. You will need `node` and `npm` installed globally on your machine.

Installation:

`npm install`  

To Run Vue:

`npm run dev`    

To Visit App:

Visit the localhost port displayed in the terminal after running `npm run dev`.

## Reflection

The Mt. Washington Observatory does not have an API to draw data from. Instead, I downloaded the available data in a spreadsheet and store it locally.

While building this chart I experimented with how to make the data easy to consume. Displaying multiple charts with a few months each seemed repetitive. Displaying one chart with 12 lines seemed confusing. I chose to display one chart, but with the ability to toggle each month on/off. The first six months (Jan, Feb, Mar, Apr, May, Jun) are displayed by default.

## Acknowledgments

* Temperature data from the [Mt. Washington Observatory](https://mountwashington.org/weather/mount-washington-weather-archives/monthly-f6/).
* Photo of summit [Andrew Weitzel](https://commons.wikimedia.org/wiki/File:View_from_the_top_of_Mt._Washington_(49675348518).jpg).
* Chart built with [Chart.js](https://www.chartjs.org/docs/latest/).
* Readme guidance from [Brenna Martenson](https://gist.github.com/martensonbj/6bf2ec2ed55f5be723415ea73c4557c4).
* Linting guidance from [ESLint](https://eslint.org) and [Stylelint](https://stylelint.io).
* Design guidance from Google's [Material Design](https://material.io/design).
* Shields from [Shields](https://shields.io).