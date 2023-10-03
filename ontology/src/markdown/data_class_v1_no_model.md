DataClass
- SklearnObject
    - Transformer
        - Imputer
            - SimpleImputer
            - IterativeImputer
            - KNNImputer
        - DecompositionTransformer
            - PCA
            - TrunctuatedSVD
- BasicObject
    - Str
    - Number
        - Bool
        - Int
        - Float
    - DateTime
- PandasObject
    - Series
        - StrSeries
        - NumberSeries
            - BoolSeries
            - IntSeries
            - FloatSeries
        - DateTimeSeries
        - DescribeSeries
        - MixedSeries
    - DataFrame
        - DescribeDataFrame
        - ClassificationReport
        - MixedDataFrame
        - NumberDataFrame
            - BoolDataFrame
            - IntDataFrame
            - FloatDataFrame
    - Column
        - StrColumn
        - NumberColumn
            - BoolColumn
            - IntColumn
            - FloatColumn
        - DateTimeColumn
        - MixedColumn
- MatplotlibObject
    - Axes
    - Figure
- NumpyObject
    - FlatArray
        - StrFlatArray
        - IntFlatArray
        - FloatFlatArray
        - BoolArray
        - DateTimeArray
    - NDArray
        - StrNDArray
        - IntNDArray
        - FloatNDArray
        - BoolNDArray
        - DateTimeNDArray
        - EmbeddingMatrix
- TextEmbeddingObject
    - Gensim
        - Word2Vec
    - SklearnText
        - TfidfVectorizer
        - CountVectorizer