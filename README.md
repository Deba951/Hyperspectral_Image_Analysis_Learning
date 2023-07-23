# Hyperspectral_Image_Analysis_Learning


## Warning in "Data_Analysis_of_the_Indian_Pines_hyperspectral_image_dataset.ipynb"
  The warning is saying that the `distplot` function is deprecated, which means that it will be removed in a future version of Seaborn. You can fix the warning by using either the `displot` or `histplot` function instead. Here is an example of how to use the `displot` function:
    ```
      sns.displot(df['band-' + str(n)], bins=25, kde=True)
    ```
  This function takes the same arguments as the `distplot` function, but it also has an additional argument called `kde`, which controls whether or not a kernel density estimate is plotted.
