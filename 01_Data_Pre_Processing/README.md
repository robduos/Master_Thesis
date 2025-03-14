## Table of the python scripts used to create the final merged dataset

| Script Name | Description | Link |
|------------|------------|-------------|
| 01_01_Filter_EC_Tower_Data  | Read the CSV Files of the EC Towers, filter only the relevant columns for all the locations. Export the filtered dataframes as CSV Files. | [View Script](https://github.com/robduos/Master_Thesis/blob/main/01_Data_Pre_Processing/01_01_Filter_EC_Tower_Data.R) |
| 01_02_Selected_EC_Tower_Data  | Import all the filtered CSV files, Compute the daily mean for all variables, merge them into one dataframe. | [View Script](https://github.com/robduos/Master_Thesis/blob/main/01_Data_Pre_Processing/01_02_Selected_EC_Tower_Data.R) |
| 01_03_Extract_OWASIS_Data | Extract the parameter 'Available Soil Storage [mm]' from the OWASIS | [View Script](https://github.com/robduos/Master_Thesis/blob/main/01_Data_Pre_Processing/01_03_Extract_OWASIS_Data.R) |
| 01_04_Extract_Planet_Data | Read and Filter the received Planet Inc data. Use the coordinated of the EC Towers to Identify the appropriate Pixel to extract all the SWC values from | [View Script](https://github.com/robduos/Master_Thesis/blob/main/01_Data_Pre_Processing/01_04_Read_Filter_Planet_Data.R) |
| 01_05_Merging_LST_LAI_S2_Data | Import all the S2, MODIS & L8_9 csv files | [View Script](https://github.com/robduos/Master_Thesis/blob/main/01_Data_Pre_Processing/01_05_Merging_LST_LAI_S2_Data.R) |
| 01_06_Merging_ALL_Data | Merging individual datasets (S1 VSM CSV, S1 Backscatter, S2 OPTRAM, Planet Inc.) | [View Script](https://github.com/robduos/Master_Thesis/blob/main/01_Data_Pre_Processing/01_06_Merging_All_Data.R) |
| 01_07_Extract_BIS_4D_Data | Extract data from BIS-4D TIFF files | [View Script](https://github.com/robduos/Master_Thesis/blob/main/01_Data_Pre_Processing/01_07_Extract_BIS_4D_Data.R) |
| 01_08_Compute_Evapotranspiration | Compute and export the Evapotranspiration| [View Script](https://github.com/robduos/Master_Thesis/blob/main/01_Data_Pre_Processing/01_08_Compute_Evapotranspiration.ipynb) |
| 01_09_Merging_ALL_Data_V2 | Merge additional datasets (PET & ET0, BIS-4D, BOFEK to the final dataset) | [View Script](https://github.com/robduos/Master_Thesis/blob/main/01_Data_Pre_Processing/01_09_Merging_ALL_Data_V2.ipynb) |
| 01_10_Computing_nighttime_NEE | Split the merged datasets to two seasonal datasets | [View Script](https://github.com/robduos/Master_Thesis/blob/main/01_Data_Pre_Processing/01_10_Computing_nighttime_NEE.ipynb) |
| 01_11_Splitting_Merged_Dataset_by Season | Divide the merged dataset into seasonal datasets  | [View Script](https://github.com/robduos/Master_Thesis/blob/main/01_Data_Pre_Processing/01_11_Splitting_Merged_Dataset_by%20Season.ipynb) |