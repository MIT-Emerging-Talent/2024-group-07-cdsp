# Data Cleaning Description

## First Iteration

1. In the `First_iteration` folder, we cleaned the original dataset **"Original_mimi_dataset_v2.csv"**. We ordered it in a way that is readable for the reader and dropped columns that weren't related to our project, as well as those with missing data. The following are the names of the columns that we dropped:
   - 'origin_PDI',
   - 'origin_IDV',
   - 'origin_MAS',
   - 'origin_UAI',
   - 'origin_LTO',
   - 'origin_area',
   - 'destination_area',
   - 'origin_cont_code',
   - 'destination_cont_code',
   - 'origin_coordinate',
   - 'origin_latitude',
   - 'origin_longitude',
   - 'destination_coordinate',
   - 'destination_latitude',
   - 'destination_longitude',
   - 'destination_PDI',
   - 'destination_IDV',
   - 'destination_MAS',
   - 'destination_UAI',
   - 'destination_LTO',
   - 'sci_2021',
   - 'sci_2020',
   - 'destination_fb_users',
   - 'destination_fb_users_perc'

2. After cleaning the original dataset, we created a new file **ordered_mimi.csv**. We selected only the countries of interest and created a new file named **countries_of_interest_data.csv**.

## Second Iteration

The GDP data in our dataset wasn't up to date. So, we obtained a new dataset from the World Bank, merged it with our dataset, and created a new file **merged_Dataset.csv** in the **New** folder.



