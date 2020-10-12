# COVID-19 Country Comparison

A simple tool that allows comparison of two countries' COVID-19 cases. It produces number of confirmed cases, total deaths, total recovered, and total active cases for both countries.

## Instructions

Select both desired countries from dropdown menus and click "Submit".

## Built With

* [COVID19API](https://covid19api.com/) - The API used for COVID19 data
* [chart.js](https://www.chartjs.org/) - Charting library
* [Bootstrap](https://getbootstrap.com/) - CSS framework

## Known Issues

It is possible to select a country which may not return data from COVID19API.  In this case the chart will not generate and it is required to select a different country.  If you believe this is an error, it is possible to verify data using COVID19API.  To verify up-to-date data, please visit:

```
https://api.covid19api.com/total/country/<country-name>
```