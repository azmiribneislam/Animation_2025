In ''BD_population'' folder
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%% Bangladesh population fit using Logistic Model 
%% Solved using ode45 in MATLAB
%% Data used from 1960 to 2023 
%% Projection of population up to year 2100

%% Data from: World Bank Open Data
%% Data link: https://data.worldbank.org/indicator/SP.POP.TOTL?locations=BD
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%% Model

Logistic growth ODE: dp/dt = r*P*(1 - P/K)
P(t) = population (or any quantity) at time 𝑡
r = intrinsic growth rate (per unit time)
K = carrying capacity (maximum sustainable population)

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
Data fitting to the model shows 

Estimated r: 0.0418 per year
Estimated K: 208.47 million
