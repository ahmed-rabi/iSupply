# iSupply
A deep-learning model that has the ability to classify 500 Arabic medicine with some misspelling errors with accuracy 93% 

steps to run
---
1. run the first cell that contains the librarys
2. run the cell with label encoder and pass the needed column to be labeled
3. run spacy and yield tokens cells
4. run cell with SimpleTransformerClassifier class
5. then run cells classify_text and classify_excel
6. you can then pass the parameters (file_path, text_column, lookup_file, lookup_column, output_path)
     1. file_path: input file path
     2. text_column: the target input column
     3. lookup_file: master file path
     4. output_path: output file path

**Note**: you should download the simple_transformer_arabic.pth and label_encoder.pkl
