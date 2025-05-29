# Model Quality Report

- This lab uses the [`DelayedFlights`](https://www.kaggle.com/datasets/giovamata/airlinedelaycauses) dataset, as specified in the assignment.  
- The objective of the model trained in this lab is to predict whether a flight will be **on time** or **delayed**, given only the information available before the flight begins (e.g., excluding actual departure time, taxi time, etc.).  
- A detailed discussion can be found in the final section of the [`Model and Report.ipynb`](Model%20and%20Report.ipynb) notebook or in the [discussion section](##Discussion) of this README.

## Discussion

- The model quality report is hosted [here](https://ronlug.github.io/Evidently/).  
- As shown in the report, there appears to be a **slight data shift**. The model’s performance has decreased marginally across all evaluation metrics. While the differences in performance between the reference dataset and the current dataset are not substantial, this may serve as an early warning sign. The model appears to be less confident in its predictions, which could indicate the need for future updates, retraining, or data pipeline improvements to maintain optimal performance.
