pollutantmean <- function (directory, pollutant, id=1:332) {
        file <- list.files (directory, full.names=TRUE)
        alldata <- data.frame()
                for (i in id){
                        open <- read.csv (file[i])
                        alldata <- rbind (alldata, open)
                }
        mean (alldata [,pollutant], na.rm=TRUE)
}
