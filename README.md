babynames
=========

The following website contains a list of all the birth names given to babies between 1880 and 2013, and provides options to select a birth year and number of results between the top 20 and top 1000 most popular given names each year.
http://www.socialsecurity.gov/OACT/babynames/#ht=1
Your task will be to construct a command line script that returns the total number of male children within the top 1000 results that were given the following names during the date period specified:
● Billy between 1892 and 2001
● Jamie between 1901 and 1987
● Daniel between 1996 and 1999
● Neil between 1957 and 1983
● Jordan between 1880 and 2010
The script should accept a name and a start and end year as input parameters, e.g.
● ./babyNameStat [name] [start year] [end year]
● ./babyNameStat Billy 1892 2001
So expected behaviour might be:
$ ./babyNameStat Jacob 2008 2010
Between 2008 and 2010 the total number of male children named Jacob was 65767

To Run
=======
$ ./babyNameStat Billy 1892 2001
