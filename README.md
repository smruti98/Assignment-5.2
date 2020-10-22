# Assignment-5.2

3.1 Enter in the data
60 85 72 59 37 75 93 7 98 63 41 90 5 17 97
6
Make a stem and leaf plot

data=c(60, 85 ,72 ,59 ,37 ,75 ,93 ,7 ,98 ,63,41,90,5,17,97)
> stem(data)


#############################################################



3.2 Read this stem and leaf plot, enter in the data and make a histogram:
  The decimal point is 1 digit(s) to the right of the |
  8 | 028
9 | 115578
10 | 1669
11 | 01


a=c(8028,9115578,101669,1101)
> hist(a)




3.3 One can generate random data with the “r”-commands. For example
> x = rnorm(100)
produces 100 random numbers with a normal distribution. Create two different histograms for two different
times of defining x as above. Do you get the same histogram?
  
  x=rnorm(100)
> hist(x)
> hist(x,breaks = 10)
> hist(x)
> hist(x,15) 


  
  



3.6 The number of O-ring failures for the first 23 flights of the US space shuttle Challenger were
0 1 0 NA 0 0 0 0 0 1 1 1 0 0 3 0 0 0 0 0 2 0 1f
(NA means not available – the equipment was lost). Make a table of the possible categories. Try to find the
mean. (You might need to try mean(x,na.rm=TRUE) to avoid the value NA, or look at x[!is.na(x)].)
x=c("0" ,"1","0","NA" ,"0","0","0","0","0","1","1","1","0","0","3","0","0","0", "0","0","2" ,"0" ,"1")
> table(x)







