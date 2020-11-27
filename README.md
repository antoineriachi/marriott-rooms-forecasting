# Marriott Rooms Forecasting case

The notebook `marriott-rooms-forecasting.ipynb` is a suggested solution to the case [Marriott Rooms Forecasting](http://store.darden.virginia.edu/marriott-rooms-forecasting).

## Workflow Stages

1. Case background
2. Problem definition
3. Data preparation
4. Data analysis
5. Validation of forecasting methods
6. Results assessment
7. Recommendation & action plan

## Background Information

* `WHO?`:  
    - Ms. Snow, manager at Hamilton Hotel.

* `WHAT?`:  
    - Currently, there are `1839` rooms booked out of a total `1877` available. Snow received a request for `60` additional rooms from a tour company and wants to evaluate the feasibility of accepting said request.
    
* `WHY?`:  
    - There is uncertainty in customer behavior , namely no shows/cancellations, customers extending their stays and new requests coming in. This combined with the costs of over and under booking creates a situation where it is difficult to make the right decision without a numerical analysis.

* `WHEN?`:  
    - Snow must produce a forecast by mid afternoon as the tour agency needs an answer ASAP and multiple departments use said forecast to properly run operations.

## Forecasting Models

The following forecasting methods will be studied:

* `Linear Regression`
* `Isotonic Regression`
* `Linear SVR`
* `ARIMA`
* `Holt Winters`
