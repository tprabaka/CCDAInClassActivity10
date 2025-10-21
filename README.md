# Handson-L10-Spark-Streaming-MachineLearning-MLlib
---
## **Prerequisites**

I used the same prerequisites from the previous In-class activity.

Before starting the assignment, ensure you have the following software installed and properly configured on your machine:
1. **Python 3.x**:
   - [Download and Install Python](https://www.python.org/downloads/)
   - Verify installation:
     ```bash
     python3 --version
     ```

2. **PySpark**:
   - Install using `pip`:
     ```bash
     pip install pyspark
     ```

3. **Faker**:
   - Install using `pip`:
     ```bash
     pip install faker
     ```

---

## **Setup Instructions**

### **1. Project Structure**

```
CCDAInClassActivity10/
├── outputs/
│   ├── Screenshot 1 - Output of Task 4
|   └── Screenshot 2 - Output of Task 5
├── task4.py
├── task5.py
├── data_generator.py
└── README.md
```

- **data_generator.py/**: generates a constant stream of input data of the schema  
- **outputs/**: Screenshot of output we get from spark after runnning the model on stream data
- **README.md**: Assignment instructions and guidelines.
  
---

### **2. Running the Analysis Tasks**

We can run the analysis tasks either locally or codesapce.

1. **Execute Each Task** : The data_generator.py should be continuosly running on a terminal. open a new terminal to execute each of the tasks.
   ```bash
     python data_generator.py
     python task4.py
     python task5.py
   ```
2. The final resulting dataframes based on the predciton by the linear regression model will be show in in the terminal console.

---

## **Overview**

In this assignment, we will build and predict the fare_amount using a linear regression model using Apache Spark Structured Streaming and MLib. we will process streaming data, perform real-time aggregations, and predict the fare amount.

## **Objectives**

By the end of this assignment, we should be able to:

1. Train an Linear regression model
2. Save and load the trained model
3. Ingest and parse real-time ride data.
4. Perform real-time aggregations on driver earnings
5. Analyze trends over time using a sliding time window.

---

## **Outputs**

I took screenshots of the console outputs of the respective tasks and stored in the outputs folder.

1. Task 4 - Screenshot 1

2. Task 5 - Screenshot 2

---
## **Errors and Resolutions**

I did not get new any errors which I got compared to last in class assignment