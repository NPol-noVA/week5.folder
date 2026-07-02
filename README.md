# week5.folder
# Pandas Project


  This project demonstrates basic data loading and analysis using pandas.

  this is new task for improving my structure and organizing work, and using relative paths in my next submitions because my previous ones were using absolute paths that were only accebile using my laptop
  basic learning: 
  Absolute paths: only work on the original computer..
  relative paths: make a project portable so anyone can run it from the project folder.
  then briefly: Absolute paths are a problem because they only work on the original computer where the file is stored. If someone else runs the project, the path will not exist, causing the code to fail.
  generaly: clear and organized work are very important for improving the readability of this work and helps in figure out information from the study or analysis
  
 Project Structure:

                    ```
                    project_folder/
                    ├── _data/
                    │   └── insurance (4).csv
                    ├── notebook.ipynb
                    └── README.md
                    ```

 Dataset

  The dataset is stored in the `_data` folder.

 File Loading:

  The dataset is loaded using a relative path:

  python:   
  
                  ```
                   import pandas as pd
                    
                   rf = pd.read_csv("_data/insurance (4).csv")
                  ```
                   

This project uses relative paths so it can run on any computer without changing the file location 
