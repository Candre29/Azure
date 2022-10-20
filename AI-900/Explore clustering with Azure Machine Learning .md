# Explore clustering with Azure Machine Learning Designer

[https://microsoftlearning.github.io/AI-900-AIFundamentals/instructions/02c-create-clustering-model.html](https://microsoftlearning.github.io/AI-900-AIFundamentals/instructions/02c-create-clustering-model.html)

1. Create a compute cluster

![Untitled](Explore%20clustering%20with%20Azure%20Machine%20Learning%20Des%200c3eb400a67749a685a5a46ca9e1aa1d/Untitled.png)

![Untitled](Explore%20clustering%20with%20Azure%20Machine%20Learning%20Des%200c3eb400a67749a685a5a46ca9e1aa1d/Untitled%201.png)

1. Create and configure a pipeline 

![Untitled](Explore%20clustering%20with%20Azure%20Machine%20Learning%20Des%200c3eb400a67749a685a5a46ca9e1aa1d/Untitled%202.png)

1. Create a dataset 
    1. create a dataset from web files 
    
    ![Untitled](Explore%20clustering%20with%20Azure%20Machine%20Learning%20Des%200c3eb400a67749a685a5a46ca9e1aa1d/Untitled%203.png)
    
    ![Untitled](Explore%20clustering%20with%20Azure%20Machine%20Learning%20Des%200c3eb400a67749a685a5a46ca9e1aa1d/Untitled%204.png)
    
    ![Untitled](Explore%20clustering%20with%20Azure%20Machine%20Learning%20Des%200c3eb400a67749a685a5a46ca9e1aa1d/Untitled%205.png)
    
    ![Untitled](Explore%20clustering%20with%20Azure%20Machine%20Learning%20Des%200c3eb400a67749a685a5a46ca9e1aa1d/Untitled%206.png)
    
    ![Untitled](Explore%20clustering%20with%20Azure%20Machine%20Learning%20Des%200c3eb400a67749a685a5a46ca9e1aa1d/Untitled%207.png)
    
2. Configure the canvas
    1. select columns → all except specie
    2. clean missing data —> all columns 
        1. 0 Minimum, 1 maximum. remove entire row 
    3. normalize data 
        1. MinMax
        2. all columns 

![Untitled](Explore%20clustering%20with%20Azure%20Machine%20Learning%20Des%200c3eb400a67749a685a5a46ca9e1aa1d/Untitled%208.png)

1. Submit

![Untitled](Explore%20clustering%20with%20Azure%20Machine%20Learning%20Des%200c3eb400a67749a685a5a46ca9e1aa1d/Untitled%209.png)

![Untitled](Explore%20clustering%20with%20Azure%20Machine%20Learning%20Des%200c3eb400a67749a685a5a46ca9e1aa1d/Untitled%2010.png)

# Add training modules

1. Split data
    1. 
    
    [https://www.notion.so](https://www.notion.so)
    
2. train clustering_model 
    1. all columns
3. K-means clustering → 3 centroids
4. assign data to clusters
5. Evaluate model

![Untitled](Explore%20clustering%20with%20Azure%20Machine%20Learning%20Des%200c3eb400a67749a685a5a46ca9e1aa1d/Untitled%2011.png)

# create inference pipeline

1. Create an inference pipeline 

![Untitled](Explore%20clustering%20with%20Azure%20Machine%20Learning%20Des%200c3eb400a67749a685a5a46ca9e1aa1d/Untitled%2012.png)

![Untitled](Explore%20clustering%20with%20Azure%20Machine%20Learning%20Des%200c3eb400a67749a685a5a46ca9e1aa1d/Untitled%2013.png)

# deploy

1. new real-time endpoint:
    1. 
    - **Name**: predict-penguin-clusters
    - **Description**: Cluster penguins.
    - **Compute type**: Azure Container Instance

test on the endpoint page

![Untitled](Explore%20clustering%20with%20Azure%20Machine%20Learning%20Des%200c3eb400a67749a685a5a46ca9e1aa1d/Untitled%2014.png)

![Untitled](Explore%20clustering%20with%20Azure%20Machine%20Learning%20Des%200c3eb400a67749a685a5a46ca9e1aa1d/Untitled%2015.png)

![Untitled](Explore%20clustering%20with%20Azure%20Machine%20Learning%20Des%200c3eb400a67749a685a5a46ca9e1aa1d/Untitled%2016.png)

![Untitled](Explore%20clustering%20with%20Azure%20Machine%20Learning%20Des%200c3eb400a67749a685a5a46ca9e1aa1d/Untitled%2017.png)