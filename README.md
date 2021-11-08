# FEDERETED LEARNING AND DIFFERENTIAL PRIVACY EXAMPLES
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://github.com/judithspd/security_MDS/blob/master/LICENSE) 

- In *ExampleNotes.ipynb* the need to introduce the concept of Differential Privacy (DP) is presented with an specific use case . 
- In *Example_DP.ipynb* it is proposed to apply Differential Privacy to find the total and average cases of Covid-19 each month of 2021 in all the CCAA of Spain. For this purpose, we propose to use [PyDP](https://github.com/OpenMined/PyDP), study the results as a function of the privacy budget and compare with the real values.
- At *Example_FL_MNIST.ipynb* we propose to create a Federated Learning (FL) algorithm and apply it to a specific use case using the famous [MNIST](https://keras.io/api/datasets/mnist/) dataset. Specifically, given this dataset, the train set should be divided into 3 clients, and Federated Learning should be applied to each of them, and an aggregation function (such as weighted average) should be implemented. Once the process is done the first time, the obtained model (model1.h5) will be saved and the test set will be evaluated with it. We will repeat this after training 2 times (model2.h5) and 3 times (model3.h5).

## Recommendations for installation:
1. Clone the repository
```
git clone https://github.com/judithspd/security_MDS.git
```
2. Create a Python or conda virtual environment:
  - **LINUX:**
  ```
  virtualenv venv -p python3
  ```
  - **WINDOWS:**
  ```
  python3.8 -m venv .venv
  ```
3. Activate virtual environment:
  - **LINUX:**
  ```
  source venv/bin/activate
  ```
  - **WINDOWS:**
  ```
  source .venv/Scripts/activate.bat
  ```
4. Install requirements.txt
```
pip install -r requirements.txt
```
