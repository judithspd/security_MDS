# FEDERETED LEARNING AND DIFFERENTIAL PRIVACY EXAMPLES
### Master in Data Science - Safety, Privacy and Legal Aspects
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://github.com/judithspd/security_MDS/blob/master/LICENSE) 

- In *ExampleNotes.ipynb* the need to introduce the concept of Differential Privacy (DP) is presented with an specific use case . 
- In *Example_DP.ipynb* it is proposed to apply Differential Privacy to find the total and average cases of Covid-19 each month of 2021 in all the CCAA of Spain. For this purpose, we propose to use [PyDP](https://github.com/OpenMined/PyDP), study the results as a function of the privacy budget and compare with the real values.
- At *Example_FL_MNIST.ipynb* we propose to create a Federated Learning (FL) algorithm and apply it to a specific use case using the famous [MNIST](https://keras.io/api/datasets/mnist/) dataset. Specifically, given this dataset, the train set should be divided into 3 clients, and Federated Learning should be applied to each of them, and an aggregation function (such as weighted average) should be implemented. Once the process is done the first time, the obtained model (*model1.h5*) will be saved and the test set will be evaluated with it. We will repeat this after training 2 times (*model2.h5*) and 3 times (*model3.h5*).

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

## More learning resources:
- Rodríguez-Barroso, N., Stipcich, G., Jiménez-López, D., Ruiz-Millán, J. A., Martínez-Cámara, E., González-Seco, G., ... & Herrera, F. (2020). Federated Learning and Differential Privacy: Software tools analysis, the Sherpa. ai FL framework and methodological guidelines for preserving data privacy. Information Fusion, 64, 270-292. https://www.sciencedirect.com/science/article/pii/S1566253520303213.
- Li, T., Sahu, A. K., Talwalkar, A., & Smith, V. (2020). Federated learning: Challenges, methods, and future directions. IEEE Signal Processing Magazine, 37(3), 50-60. https://ieeexplore.ieee.org/abstract/document/9084352. 
- Federated Learning: Collaborative Machine Learning without Centralized Training Data. Google AI Blog. https://ai.googleblog.com/2017/04/federated-learning-collaborative.html.
- Tensorflow Federated (TFF). https://www.tensorflow.org/federated/federated_learning.
- Friedman, A., & Schuster, A. (2010, July). Data mining with differential privacy. In Proceedings of the 16th ACM SIGKDD international conference on Knowledge discovery and data mining (pp. 493-502). https://dl.acm.org/doi/abs/10.1145/1835804.1835868
- Abadi, M., Chu, A., Goodfellow, I., McMahan, H. B., Mironov, I., Talwar, K., & Zhang, L. (2016, October). Deep learning with differential privacy. In Proceedings of the 2016 ACM SIGSAC conference on computer and communications security (pp. 308-318). https://dl.acm.org/doi/abs/10.1145/2976749.2978318. 
- Harvard University Privacy Tools Project. Differential Privacy. https://privacytools.seas.harvard.edu/differential-privacy.

