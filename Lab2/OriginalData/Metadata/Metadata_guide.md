# Metadata Guide


## Info needed to understand our original data:

Header | Definition
---|---------
iso2 | contains information about the city where data were colleted;
year | info about the year when data about tuberculosis were collected;
new_sp_m1524  | new cases of tuberculosis in different groups of people (described below)
m/f | MALE / FEMALE  info about the gender of ill person;
1524 | 15-24 - ages range.


## Additional information
If there is only new_sp without m/f or the numbers I assume that it refers to all people who live in the city. If there is 'u' instead of numbers
it means that all people upper (above) maximum present age range which is 64.
        
There are many empty spaces. It is natural because it is obvious that older people get ill much more often than younger ones so there are empty informations about young people (0-14 age range) becouse this group of people is examinated less often.

## Original Data location
The data was downloaded from [here](https://github.com/KAIR-ISZ/public_lectures/tree/master/Analiza%20i%20Bazy%20Danych%202021/Lab%202).