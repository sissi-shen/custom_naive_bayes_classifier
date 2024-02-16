In this project, I built a multinomial naive bayes classifier to predict whether a movie review is positive or negative. I also implemented k-fold cross validation testing.

Functions I implemented include:
• load_docs(docs_dirname)
• vocab(neg, pos)
• vectorize(V, docwords)
• vectorize_docs(docs, V)
• kfold_CV(model, X, y, k=4) (You must implement manually; don’t use sklearn’s version but you can use KFold as part of your function) and implement class NaiveBayes621 with these methods
• fit(self, X, y) • predict(self, X)

I also implemented class NaiveBayes621 with these methods
• fit(self, X, y) 
• predict(self, X)