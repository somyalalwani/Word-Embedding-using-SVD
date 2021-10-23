## Question1_SVD
- filename : 2020201092_NLP_Q1
- embeddings : weight_matrix_q1.pkl- https://drive.google.com/file/d/1QZWKZrN2r9Ey78pSm4LPhQSOgAPBKyI1/view?usp=sharing

## Question2_CBOW
- filename : 2020201092_NLP_Q2
- embeddings : weight_matrix_q2(1).pkl : https://drive.google.com/file/d/1-08IGnNHVA8mRgxjbKcZQZ4-bnf96pZl/view?usp=sharing
- model : nlpq2(1).h5 : https://drive.google.com/file/d/1ganWxOOn8AG_8rfQrovt3BQ6JI_XX6QZ/view?usp=sharing

## README.md


## C0-Occurance Matrix and SVD Implementation

to get the embeddings for my model we need to get it from the link mentioned above under the name `embeddings_q1.pkl` and to load it into a variable 
Instead of using co-occurence matrix, I have used DOK matrix..it is an implementation of co-occurence matrix but with faster computations and less memory.

run the command -> 
`import pickle`

`data = open ('path_to_folder/weight_matrix_q1.pkl', "rb")`
`embeddings = pickle.load(data)`
and then we can use the embeddings to further work

## Part 2
Top 10 words and closest words to `camera` and the `tsne` and `scatter plot` and `comparison with the embeddings of gensim` are in both the `ipynb` file for both `svd` model.
