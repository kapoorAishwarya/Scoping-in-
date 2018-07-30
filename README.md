# Scoping-in-
Programming Assignment 2

 Vector <- function(x = numeric()) {
         m <- NULL
         set <- function(y) {
                x <<- y
                m <<- NULL
        }
        get <- function() x
        set<- function(mean) m <<- mean
        get <- function() m
        list(set = set, get = get,
             setmean = setmean,
             getmean = getmean)
 }
