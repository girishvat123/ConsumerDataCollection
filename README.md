# Consumer Data Collection 

This simple software extracts the data from mutliple `metrics.json` files corresponding to the consumers and 
outputs the metrics data to a single csv file. It can run on both the versions of ***Python(2 as well as 3)***
## Steps for running it in your own local machine with the cloned repository(Running the executable)

1. Clone the repository:
  ```git clone git://github.com/girishvat123/ConsumerDataCollection``` 

2. ```cd ConsumerDataCollection```

3. Run the following command:
    ```./dist/runnable <nameOfTheOutputFile> /path/to/jsonfilesfolder/```

4. You can see the outputfile with the name you mentioned created in your directory. 

## Steps for running the python script directly 

1. Clone the repository as mentioned in step 1 above section.

2. ```cd ConsumerDataCollection```

3. Run ```pip install -r requirements.txt```

4. Run below command:

   ```python runnable.py <nameOfTheOutputFile> /path/to/jsonfilesfolder/```

5. You can see the outputfile with the name you mentioned created in your directory.    
