# Geospatial_Data_Analysis_Python
*Extended Abstract

A geospatial data analysis is discussed in this repository. 

The data has been imported from the local disk and stored in a postgresql database using the psycopg2 library in python. The data was then read directly from the postgresql database and maped to their respective column headers. No null value was observed in the data.

The distribution of the data have plotted with the aid of matplotlib and ggplot. It is observed from the graph that about 9 rows have 0 polling units. This means that there are some locations without polling units. Therefore whatever data obtained from such places should be discared for now, for the sake of this analysis. The only null values observed in the data are from the ra and lga columns where the polling unit values are zero. This makes it safe to drop all rows containing null values.

The voting population have been plotted against the electoral wards. It is observed that ABULE OJA has the highest number of voters, followed by ALAGOMEJI. ABULE IJESHA has the lowest number of voters.

The number of polling units have also been plotted against the electoral wards. It is observed that ADERUPOKO/IJEBU QTRS has the highest number of polling units, closely followed by ADEKUNLE/AIYETORO. MAKOKO has the lowest number of polling units. 

*Conclusion

In this work, geospatial data on voting population, polling units, and electoral wards have been analyzed and visualized. It was observed that ABULE OJA had the highest number of voters, followed by ALAGOMEJI, and ABULE IJESHA had the lowest number of voters. ADERUPOKO/IJEBU QTRS had the highest number of polling units, closely followed by ADEKUNLE/AIYETORO, and Makoko had the lowest number of polling units. Makoko having the lowest number of polling unit and still managed to have the fourth highest number of voters, proves that if more polling units are established in Makoko electoral ward, the voting poplulation is likely to increase significantly.
