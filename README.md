# Embirdding View 

You can find an online example of Embirdding View in this link http://203.101.225.95

This repository is in development and will contain the script and an example of the embeddings visualisation technique for bioacoustic sounds called Embirdding View as presented in "*Improved analysis of deep bioacoustic embeddings through dimensionality reduction and interactive visualisation*". 

To run your own embeddings and dataset you need to generate a csv file that contains the following columns for each  sound frame:
+ **umap_0, umap_1** and **umap_2**; the 2 or 3-dimensional UMAP coordinates, exclude umap_2 when only displaying two dimensions
+ **path**; the complete path to the source sound file including folder, subfolders and full file name
+ **start** and **end**; the start and end time markers in seconds of the frame in the sound file
+ **text**; the species name or any other label for each frame to use in the markers. 

Please refer to our paper for techniques on generating embeddings and dimensionality reduction.

After running the script open the viewer on a browser, typically at http://127.0.0.1:8080/

## Requirements

The code requires the libraries [plotly](https://plotly.com/) and [dash](https://plotly.com/dash/) as well as other common libraries.

## References and Sources

Bravo Sanchez, F., English, N., Hossain, R., Moore, S. *Improved analysis of deep bioacoustic embeddings through dimensionality reduction and interactive visualisation*. 
