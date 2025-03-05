# **Overview**

This project is a machine learning-based application designed to predict diseases based on a user's selected symptoms. The prediction is made using four different algorithms: **Decision Tree, Random Forest, K-Nearest Neighbour, and Naive Bayes**. The user interacts with the application through a simple Tkinter GUI, and the prediction results are stored in an **SQLite database**.

## **Features**

**Multiple ML algorithms:** Uses Decision Tree, Random Forest, K-Nearest Neighbour, and Naive Bayes to provide diverse predictions.<br>
**User-friendly GUI:** Built with Tkinter, the interface allows users to select symptoms and view predictions easily.<br>
**Final prediction:** After viewing results from all algorithms, users can click the "Final Prediction" button to get a consolidated prediction.<br>
**Database storage:** All user data, including patient names and symptoms, is stored in an SQLite database.<br>

## **Tech Stack**

**Programming Language:** Python<br>
**GUI:** Tkinter<br>
**Machine Learning Algorithms:**<br>
<ul>
  <li>Decision Tree</li>
  <li>Random Forest</li>
  <li>K-Nearest Neighbour</li>
  <li>Naive Bayes</li>
</ul>

**Database:** SQLite<br>
**Development Environment:** Jupyter Notebook<br>

## **How It Works**

**Input:** The user provides their name and selects five symptoms from a predefined list.<br>
**Prediction:** Upon clicking the "Predict All" button, the application uses four machine learning models to predict potential diseases based on the symptoms.<br>
**Final Outcome:** The user can then click the "Final Prediction" button to see a consolidated prediction based on the results of the four algorithms.<br>
**Database Storage:** The patient's details and predictions are saved in an SQLite database, which can be accessed through the SQLite browser for further analysis.<br>


| Algorithm            | Accuracy |
|----------------------|----------|
| Decision Tree        | 93%      |
| Random Forest        | 95%      |
| K-Nearest Neighbour  | 92%      |
| Naive Bayes          | 93%      |


## **Setup Instructions**

Ensure you have one of the **Jupyter Notebook or VS Code**.

Download the code file, testing and training dataset.

Upload them on any development environment and run it.

## **Future Improvements**

1. Adding more symptoms and diseases to enhance the prediction model.
2. Incorporating more sophisticated ML models like SVM or Neural Networks for better accuracy.
3. Implementing a web-based interface using Django/Flask for broader accessibility.

## **Conclusion**

This project demonstrates the integration of machine learning with a user-friendly interface for disease prediction. The use of multiple algorithms offers varied insights, making the final outcome more reliable.

### **License**
MIT License

Copyright (c) 2025 shubhanshu Singh

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


![pic project](https://github.com/user-attachments/assets/1beab0a6-692b-4f67-9449-5bf620a8da39)
