This notebook is used to analyze performance of a network of stores. Its primary objectives are to determine the best way to measure store or market based tests in a store network, and to identify performance outliers that contribute to measurement noise.

It includes functions to import data, visualize the data, pair test and control sites, measure tests, conduct nulltest simulations, and remove outliers. Throughout, I'll provide markdown comments to discuss code that may need explanation, and interpretation of the results.

If you are charged with making measurements in a store retail environment, this functionality can greatly help you identify optimal ways to measure both store and market level tests.

Here is the measurement optimization analysis writeup: https://docs.google.com/document/d/1E7silq4jqjVkWMxf5i3Wn0UZ9X7hqsW9QXa7vditlOA/

Here is the outlier detection analysis writeup: https://docs.google.com/document/d/1Tf8VRuq_GCPr1bXcGkLMT9a-594VI1IMyXoBThxyzkU/

To run this notebook in your own environment, I recommend the following steps:

Install the pathlib, pandas, numpy, datetime, scipy, matplotlib, and random modules. These modules are used by the functionality in
Get the dataset at Kaggle: https://www.kaggle.com/datasets/manjeetsingh/retaildataset
Download this notebook
Update the file import path in step #2 below: It currently points to the filepath on my machine
