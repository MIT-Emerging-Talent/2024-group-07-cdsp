# Data Description
We include below a detailed definition of all variables contained in our dataset
## Geographical Variables
- from_to: the index consists in uniquely identified pairs of countries, built as follows: ISO2 code of origin country—ISO2 code of destination country.

- country_country, country_name, country_alpha_3, country_official_name: ISO-3166 standards nomenclatures for country identification, retrieved from PyCountry Python module 13 and ISAN (International Standard Audiovisual Number).

- from_to_cont: consists of the pair code of origin continent—code of destination continent.

- country_latitude, country_longitude, country_coordinate: indicate the position of the centroids of both origin and destination countries in a classic geographic coordinate system.

- geodesic_distance_km: the measure of distance between origin and destination, computed starting from the tuple in variable 13 of both countries and using the geodesic formulation.

- country_neighbors: consists in the list of countries that share a border with the given country.

- country_area: is the measure of the area extension of the country in squared kilometers.

## Interdisciplinary Indicators
- country_gdp_year: is an indicator that provides per capita 20 annual values for gross domestic product (GDP) of a country, expressed in current international dollars and converted by purchasing power parity (PPP) 21 conversion factor.

- country_religion, country_languages: contain, respectively, the most practiced religion, and the list of the most spoken languages in the country (including both official and minority languages).

- country_PDI: is the Power distance indicator (PDI) which is defined as “the extent to which the less powerful members of organisations and institutions (like the family) accept and expect that power is distributed unequally”.

- country_IDV:the Individualism indicator (IDV) 22 (as opposed to collectivism) explores the “degree to which people in a society are integrated into groups"
- country_MAS: is the Masculinity indicator (MAS), defined as “a preference in society for achievement, heroism, assertiveness and material rewards for success”.
- country_UAI: is the Uncertainty avoidance indicator (UAI) defined as “a society’s tolerance for ambiguity", in which people embrace or avert an event of something unexpected, unknown, or away from the status quo
- country_LTO: the Long-term orientation indicator (LTO) associates the connection of the past with the current and future actions/challenges.

## Demographic Variables
- source_country_pop_year1: annual population stocks, defined as the number of persons having their usual residence in a country in a given year.

- source_country_pop_dens_year: represents annual population density, defined as the ratio between the annual average population and the land area.

- source_country_total_imm_by_year, source_country_total_em_by_year: absolute number of migrants (respectively, immigrants and emigrants) per country.

- source_country_net_migr_start-end2, source_country_net_migr_rate_start-end: ndicate quinquennial NET migration and NET migration rate of each country. The former is the difference between the number of immigrants and the number of emigrants in a given area during the reference year, while the latter is defined as the NET migration per 1000 persons and so it indicates the contribution of migration to the overall level of population change.

- source_year_sex_age_by3: yearly migration flows for each pair of countries are defined as the number of people that have moved country (i.e., that changed residence).

- source_migr_stocks_year_sex_age4: quinquennial migration stocks for each pair of countries consist in the absolute number of migrants residing in the destination country at a given time.
