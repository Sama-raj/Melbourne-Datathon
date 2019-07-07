1. melbourne_vehicle_traffic.csv data is used in the split_carspeeds.rmd file
   to split the mean speeds and standard deviations by day and hour. The output is then stored in clean_carspeeds.csv

2. The clean_carspeeds.csv is used in the reverse_geocode(1).ipynb to perform reverse geocoding and the resulting data is stored 
   in reverse_geocoded_data.csv

3. From the reverse_geocoded_data.csv I split the formatted address in suburb and postal code but I lost the file in which I did that.
   I used that file to create data1_carspeeds.csv which has only the mean speeds and postal codes.

4. I used data1_carspeeds in carspeeds.twb to create time series visualizations in tableau.

5. I retreived a transformed dataset of the data1_carspeeds.csv from tableau and stored it as carspeeds_tab which is used in the
   carspeeds_analysis.rmd file for suburb ranking.

6. I did the suburb ranking and stored it in summary_data.csv and used it in suburb_ranking.twb to get the heat map.

Final result:

Top 10 Busiest Suburbs:

3001 - Melbourne
3000 - Melbourne CBD
3050 - Parkville
3053 - Carlton
3010 - Uiversity of Melbourne
3065 - Fitzroy
3066 - Collingwood
3051 - North Melbourne
3181 - Prahran
3056 - Brunswick

and the traffic_congestion_melbourne.png has the visualisation. This is also embedded in the carspeeds_analysis.rmd file.