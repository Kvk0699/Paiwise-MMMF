Final Year Thesis Project :- Pair Wise Maximum Margin Matrix Factorization

ABSTRACT
Maximum Margin Matrix Factorization (MMMF) has been a successful learning method in collaborative filtering research. For a partially observed ordinal rating matrix, the focus is on determining low-norm latent factor matrices U (of users) and V (of items) so as to simultaneously approximate the observed entries under some loss measure and predict the unobserved entries. When the rating matrix contains only two levels (±1), rows of V can be viewed as points in k-dimensional space and rows of U as decision hyperplanes in this space separating +1 entries from −1 entries. When hinge/smooth hinge loss is the loss function, the hyperplanes act as maximum-margin separators. In MMMF, rating matrix with multiple discrete values is treated by specially extending hinge loss function to suit multiple levels. We view this process as analogous to extending a two-class classifier to a unified multi-class classifier. Alternatively, multi-class classifiers can be built by arranging multiple two-class classifiers in a hierarchical manner.
In this paper, we investigate this aspect of collaborative filtering and propose a framework of multiple bi-level MMMFs in a hierarchical manner. The previous approach was based on dividing points by line. We want to consider only the distance between every pair of points, maximizing distance ( not considering line division ).
Then we compare our proposed method with HMF ,IB, SVD, PMF, MCoC, DsRec , PMMMF , Hern, SCC and TyCo with a benchmark 100k movielen dataset on measures on MAE.

Implemented the code in MATLAB
