This is the data documentation for the file "df_agile.csv", in this same repository. It contains variables' names followed by its description.



cd_mun: Unique identifier for each municipality as defined by IBGE

municipality: Name of the municipality

state_acronym: Acronym (two capital letters) of the Brazilian state where the municipality is located

area_mun: Total area of the municipality in square kilometres (km²)

urban_area: FUA, in square metres (m²), within each municipality.

risk_areas_perc: Percentage of risk area in a FUA per municipality.

n_cemaden_inst: Number of Cemaden Educação partner institutions per municipality.

n_hist_floods: Number of flooding occurrences in municipalities from 2003 to 2015. Estimation considers count of public decrees declaring emergencies and states of public calamity issued by the local authorities and published on the National Civil Defence Secretariat website.

n_wpd_participants: Number of WPD participants per municipality, derived from the project's raw data.

n_stations: Number of official weather stations per municipality.

bins_wpd_participants: Factor variable for n_wpd_participants.

bins_hist_floods: Factor variable for n_hist_floods.

bins_cemaden_inst: Factor variable for n_cemaden_inst.

mapped_cprm: Binary variable indicating which municipalities contain risk areas within FUA.

gdp_per_capita: Per capita GDP per municipality in BRL

longitude: Longitude coordinate for the municipality's centroid, in degrees

latitude: Latitude coordinate for the municipality's centroid, in degrees

idhm: Human Development Index per municipality, developed by UNDP together with other Brazilian institutions using data from the 2010 census. The index ranges from 0 (very low) to 1 (very high), using selected variables to measure health and longevity, access to education and quality of life.

idhm_income: Subdomain of the main IDHm focussing on income, also ranging from 0 to 1
