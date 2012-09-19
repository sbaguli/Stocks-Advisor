#Stock Advisor
Reads through stocks data (in txt file) to look for greatest gains; reports month/yeah of beginning and end of peak, as well as percentage gain.

##Usage
    ruby future.rb stocks.txt | less
    
##Stocks File Format

Company Name | SYMBOL | [Array of Monthly Dollar Values Separated by Commas]

Repeat line-by-line for additional stocks.

####Example:

    NYC Software Startup | NYCS | [17.47, 24.6, 23.77, 22.03, 27.29, 27.87, 29.41, 26.66, 22.98, 20.61, 23.42, 25.86, 26.69, 25.66, 23.5, 24.29, 21.05, 20.51, 22.03, 19.33, 19.77, 17.62, 21.54, 23.23, 20.83, 19.12, 19.15, 19.57, 20.67, 19.89, 20.72, 21.34, 21.43, 22.47, 21.25, 20.9, 22.24, 22.47, 21.56, 20.26, 21.24, 21.32, 23.21, 23.16, 22.25, 22.54, 22.8, 24.36, 24.28, 23.88, 22.93, 22.03, 23.06, 23.59, 22.71, 23.41, 25.11, 23.59, 23.56, 25.45, 24.05, 25.89, 24.79, 25.11, 22.28, 20.98, 21.58, 22.29, 23.89, 25.43, 26.69, 27.39, 27.86, 28.79, 26.37, 26.09, 28.03, 28.82, 27.68, 27.23, 27.08, 27.77, 34.69, 31.77, 33.66, 30.83, 25.82, 26.94, 27.07, 26.98, 26.21, 24.5, 26.1, 25.53, 21.36, 19.47, 18.72, 16.47, 15.66, 17.81, 19.64, 20.38, 23.19, 22.95, 24.19, 25.24, 27.21, 28.99, 30.04, 27.77, 28.39, 29.0, 30.24, 25.66, 22.89, 25.67, 23.47, 24.49, 26.67, 26.95]