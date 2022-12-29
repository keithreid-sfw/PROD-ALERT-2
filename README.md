# PROD-ALERT-2
repo for doing PROD-ALERT again

here is the link for the original paper:

https://www.frontiersin.org/articles/10.3389/fdgth.2022.945635/full

This time KSR is doing it alone and putting it all up in this repo freely in real time.
The files were downloaded to .\raw_download in our Z: directory and names were tidied up.

Then we did:

PS Z:\> cd .\raw_download\                                                                                              
PS Z:\raw_download> Get-Content rstr* | Out-File all_rstr.csv

And we open up another PowerShell and did:

PS Z:\> cd .\raw_download\                                                                                              
PS Z:\raw_download> Get-Content beds* | Out-File all_beds.csv

At the time of writing, Thursday 29th December, all_beds is still being concatenated.
Off to bed while PowerShell puts

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        29/12/2022     21:50        4104902 all_beds.csv
-a----        29/12/2022     21:50              0 all_rstr.csv
-a----        16/12/2022     13:12       44776576 beds01_Sep_2021.csv
-a----        16/12/2022     13:13       48326528 beds02_Oct_2021.csv
-a----        16/12/2022     13:13       47789238 beds03_Nov_2021.csv
-a----        16/12/2022     13:16       52536975 beds04_Dec_2021.csv
-a----        16/12/2022     13:17       52817758 beds05_Jan_2022.csv
-a----        16/12/2022     13:20       53617377 beds06_Feb_2022.csv
-a----        16/12/2022     14:20       53246656 beds07_Mar_2022.csv
-a----        16/12/2022     14:20       55896662 beds08_Apr_2022.csv
-a----        16/12/2022     14:21       61880602 beds09_May_2022.csv
-a----        16/12/2022     14:23       61861874 beds10_Jun_2022.csv
-a----        16/12/2022     14:24       45446999 beds11_Jul_2022.csv
-a----        16/12/2022     14:28       44218658 beds12_Aug_2022.csv
-a----        16/12/2022     13:12       64302867 rstr01_Sep_2021.csv
-a----        16/12/2022     13:14       55198700 rstr02_Oct2021.csv
-a----        16/12/2022     13:14       54764626 rstr03_Nov_2021.csv
-a----        16/12/2022     13:16       53684106 rstr04_Dec_2021.csv
-a----        16/12/2022     13:18       57350842 rstr05_Jan_2022.csv
-a----        16/12/2022     13:20       60309890 rstr06_Feb_2022.csv
-a----        16/12/2022     14:20       70389772 rstr07_Mar_2022.csv
-a----        16/12/2022     14:20       67235758 rstr08_Apr_2022.csv
-a----        16/12/2022     14:22       75725343 rstr09_May_2022.csv
-a----        16/12/2022     14:23       73035725 rstr10_Jun_2022.csv
-a----        16/12/2022     14:27       26397904 rstr11_Jul_2022.csv
-a----        16/12/2022     14:28       25513740 rstr12_Aug_2022.csv
