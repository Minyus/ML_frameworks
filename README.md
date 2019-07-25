# ML_frameworks
Summary of Python frameworks for Machine Learning projects

| Python frameworks for Machine Learning projects      | Airflow            | Luigi     | Kedro                   | MLflow                | TensorFlow + TensorBoard |
|------------------------------------------------------|--------------------|-----------|-------------------------|-----------------------|--------------------------|
| Primary developer                                    | AirBnB             | Spotify   | QuantumBlack (McKinsey) | Databricks            | Google                   |
| pipeline execution                                   | Yes                | Yes       | Yes                     | No                    | Yes                      |
| parallel pipeline execution                          | Yes                | Yes       | Yes                     | No                    | Yes                      |
| task graph is called:                                | DAG                | workflows | pipeline                | NA                    | graph                    |
| task is called:                                      | task, operator     | task      | node                    | NA                    | (function)               |
| io is called:                                        | ?                  | target    | dataset                 | NA                    | tensor                   |
| dependency specified by                              | task               | io        | io                      | NA                    | io                       |
| IO wrapper                                           | No                 | Yes       | Yes                     | Yes (model)           | Yes (model and image)    |
| visualization of ML/DL model training through epochs | No                 | No        | No                      | Yes                   | Yes (by TensorBoard)        |
| training neural network                              | No                 | No        | No                      | No                    | Yes                      |
| Spark support                                        | Yes                | Yes       | Yes                     | Yes                   | No                       |
| Email support                                        | Yes                | Yes       | No                      | No                    | No                       |


Pull requests to correct mistakes, clarify, or add feature items are welcome!