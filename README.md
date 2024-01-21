
# Predicting Book Categories from Traditional Chinese Classifications

This project focuses on categorizing books using traditional Chinese classification systems. It employs machine learning techniques such as word embedding and gradient boosting trees to predict categories based on book titles. In my validation dataset, the accuracy is approximately 0.9.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/134YHNsURB2FlYXftUM8RtyFHWSe-07oX?usp=sharing)



## How to Use

1. **Preparing Your Data**
   - Create an **input.txt** file containing the titles of the books you want to categorize. 
   - Ensure the file has no header. 
   - Here's an example of what your **input.txt** might look like:
     ```
     进修堂文集诗集
     马书奎稿
     游莱三体诗稿
     鲍觉生诗钞
     赋则
     觉生诗钞
     咏古诗钞
     咏史诗钞
     咏物诗钞
     咏物咏史感应诗
     补竹轩集
     澄怀园诗
     ```

2. **Running the Program**
   - Upload your **input.txt** file to Google Colab.
   - Execute the code by selecting 'Run All' in the Colab environment.

3. **Downloading the Results**
   - After the code has been successfully executed, the program will automatically download the results.
   - The output will be in an Excel file named `book_category_match_output_{time}.xlsx`, where `{time}` represents the time of download.



## License

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa-link]

[cc-by-nc-sa-image]: https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-nc-sa.svg
[cc-by-nc-sa-link]: https://creativecommons.org/licenses/by-nc-sa/4.0/


