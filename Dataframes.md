This file is for keeping track of the various versions of dataframes in the notebook.

## df_market_data
The data straight from the csv

## scaled_market_data
The scaled data in array form

## df_scaled_market_data
The scaled data in dataframe form

## elbow_dict and elbow_df
For using the elbow method on the scaled data

## clusters
The list of cluster predictions for df_scaled_market_data

## df_scaled_preds
A copy of the scaled dataframe with model_k4 predictions added

## pca_results
The list form data from running principal component analysis on df_scaled_preds

## df_pca_data
The dataframe of pca_results

## elbow_dict_pca and elbow_df_pca
For using the elbow method on the pca results

## clusters_pca
The list of cluster predictions for df_pca_data

## df_pca_preds
df_pca_data plus predictions

## elbow_compare_df
Data from both elbow curve dataframes to compare