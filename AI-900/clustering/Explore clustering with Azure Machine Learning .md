# Explore clustering with Azure Machine Learning Designer

[https://microsoftlearning.github.io/AI-900-AIFundamentals/instructions/02c-create-clustering-model.html](https://microsoftlearning.github.io/AI-900-AIFundamentals/instructions/02c-create-clustering-model.html)

1. Create a compute cluster

![Untitled](clustering_images/Untitled.png)

![Untitled](clustering_images/Untitled%201.png)

1. Create and configure a pipeline 

![Untitled](clustering_images/Untitled%202.png)

1. Create a dataset 
    1. create a dataset from web files 
    
    ![Untitled](clustering_images/Untitled%203.png)
    
    ![Untitled](clustering_images/Untitled%204.png)
    
    ![Untitled](clustering_images/Untitled%205.png)
    
    ![Untitled](clustering_images/Untitled%206.png)
    
    ![Untitled](clustering_images/Untitled%207.png)
    
2. Configure the canvas
    1. select columns → all except specie
    2. clean missing data —> all columns 
        1. 0 Minimum, 1 maximum. remove entire row 
    3. normalize data 
        1. MinMax
        2. all columns 

![Untitled](clustering_images/Untitled%208.png)

1. Submit

![Untitled](clustering_images/Untitled%209.png)

![Untitled](clustering_images/Untitled%2010.png)

# Add training modules

1. Split data
    
    
2. train clustering_model 
    1. all columns
3. K-means clustering → 3 centroids
4. assign data to clusters
5. Evaluate model

![Untitled](clustering_images/Untitled%2011.png)

# create inference pipeline

1. Create an inference pipeline 

![Untitled](clustering_images/Untitled%2012.png)

![Untitled](clustering_images/Untitled%2013.png)

# deploy

1. new real-time endpoint:
    1. 
    - **Name**: predict-penguin-clusters
    - **Description**: Cluster penguins.
    - **Compute type**: Azure Container Instance

test on the endpoint page

![Untitled](clustering_images/Untitled%2014.png)

![Untitled](clustering_images/Untitled%2015.png)

![Untitled](clustering_images/Untitled%2016.png)

![Untitled](clustering_images/Untitled%2017.png)