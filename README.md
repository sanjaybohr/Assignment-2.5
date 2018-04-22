# Assignment-2.5

1.States = rownames(US Arrests)

            Get states names with ‘w’.
            States[grep("^w",rownames(USArrests))]
            Get states names with ‘W’.
            States[grep("^W",rownames(USArrests))]
	
2.	 Prepare a Histogram of the number of characters in each US state.

                Hist(States$rowames)
                hist(nchar(States), main = "Histogram",
                xlab = "number of characters in US State names")
