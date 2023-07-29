# Hyperspectral_Image_Analysis_Learning



## Warning in "Data_Analysis_of_the_Indian_Pines_hyperspectral_image_dataset.ipynb"
  The warning is saying that the `distplot` function is deprecated, which means that it will be removed in a future version of Seaborn. You can fix the warning by using either the `displot` or `histplot` function instead. Here is an example of how to use the `displot` function:

      sns.displot(df['band-' + str(n)], bins=25, kde=True)
  
  This function takes the same arguments as the `distplot` function, but it also has an additional argument called `kde`, which controls whether or not a kernel density estimate is plotted.




## Warning in "Basics.ipynb"
  When importing the datasets using the commands:
  
      !wget "http://www.ehu.eus/ccwintco/uploads/6/67/Indian_pines_corrected.mat"
      !wget "http://www.ehu.eus/ccwintco/uploads/c/c4/Indian_pines_gt.mat"
       
      
  at times they may display errors like:
  ```
      "Resolving www.ehu.eus (www.ehu.eus)... 158.227.0.65, 2001:720:1410::65
Connecting to www.ehu.eus (www.ehu.eus)|158.227.0.65|:80... connected.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: https://www.ehu.eus/ccwintco/uploads/6/67/Indian_pines_corrected.mat [following]
--2023-07-29 13:30:20--  https://www.ehu.eus/ccwintco/uploads/6/67/Indian_pines_corrected.mat
Connecting to www.ehu.eus (www.ehu.eus)|158.227.0.65|:443... connected.
OpenSSL: error:0A000152:SSL routines::unsafe legacy renegotiation disabled
Unable to establish SSL connection.
--2023-07-29 13:30:21--  http://www.ehu.eus/ccwintco/uploads/c/c4/Indian_pines_gt.mat
Resolving www.ehu.eus (www.ehu.eus)... 158.227.0.65, 2001:720:1410::65
Connecting to www.ehu.eus (www.ehu.eus)|158.227.0.65|:80... connected.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: https://www.ehu.eus/ccwintco/uploads/c/c4/Indian_pines_gt.mat [following]
--2023-07-29 13:30:21--  https://www.ehu.eus/ccwintco/uploads/c/c4/Indian_pines_gt.mat
Connecting to www.ehu.eus (www.ehu.eus)|158.227.0.65|:443... connected.
OpenSSL: error:0A000152:SSL routines::unsafe legacy renegotiation disabled
Unable to establish SSL connection."
```

In this case, Download the .mat files and add them manually. This will work fine.
