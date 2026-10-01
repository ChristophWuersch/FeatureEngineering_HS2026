# FeatureEngineering
Repository for data and images for colab

## Group Work: Collaborative Deep Dive – Feature Engineering (FTP_MachLe, HS 2026)

The full assignment is in [04_FeatureEngineering_GroupWork.pdf](04_FeatureEngineering_GroupWork.pdf); the shared notebook starts from [FeatureEngineering_TEMPLATE.ipynb](FeatureEngineering_TEMPLATE.ipynb).

### Goal

Feature engineering is one of the most decisive steps in machine learning: even powerful models depend on how the data is represented. In this group work you explain feature engineering concepts to your peers in your own words, as active contributors rather than passive consumers. The result is high-quality documentation that you can use 1:1 as an exam cheat sheet. There are no grades and no competition. The aim is shared understanding (and having fun while doing serious ML).

### Deliverable

Each group writes one clearly structured section of a joint, blog-style Jupyter notebook:

- ca. 3 pages per section
- clear, compact explanations in simple but precise language
- minimal but non-trivial examples (clarity over complexity)
- diagrams, figures and code snippets where helpful
- a final **Takeaways** section that answers:
  - What should every ML practitioner remember?
  - What are common pitfalls?
  - When does this technique really matter?
- names of all authors
- upload to Moodle (Chapter 4)

If all authors agree, the best submissions are published as blog posts on the course GitHub page.

### Rules of the game

- Everyone is an editor. A volunteer editor-in-chief compiles the contributions into one consistent document.
- Divide tasks early and merge later (*divide et impera*).
- All sources are allowed (web, books, tools, LLMs). Cite sources for figures and diagrams (URLs are enough).
- Be respectful, friendly and inclusive.
- Time is short, so aim for an 80% solution.

### Time schedule

| Duration | Activity |
|---|---|
| 5' | Introduction and task splitting |
| 40' | Group work on topics |
| 5' | Break |
| 25' | Merge, refine, upload |
| 20' | First 3 presentations |
| 15' | Break |
| 30' | Remaining presentations |
| 15' | Discussion and feedback |

### Group topics

**Group 1: Feature Normalization**
1. Why normalization matters
2. Which learners depend on it (kNN, SVM, linear models, neural networks)
3. Standard scaling (z-transform)
4. Min–max scaling
5. Robust scaling (median and IQR)
6. Skewness and power transforms: Box–Cox, Yeo–Johnson
7. Outlook for neural networks: vanishing and exploding gradients

**Group 2: Feature Transformation**
1. Why and when feature transformations make sense
2. Log, square-root and monotonic transforms
3. Categorical features: nominal → one-hot encoding, ordinal → label encoding
4. Problems with one-hot encoding (sparsity, curse of dimensionality)
5. Polynomial features
6. Periodic features: sine/cosine encoding, radial basis functions

**Group 3: Data Cleaning and Integration**
1. Missing values and `np.nan`
2. Filtering and smoothing (moving averages)
3. Binning and discretization
4. Missing value imputation: forward/backward fill, median imputation
5. Outlier detection and removal
6. Data integration: merging pandas DataFrames

**Group 4: Feature Selection I**
1. Why feature selection helps (bias–variance tradeoff)
2. Univariate feature selection: Pearson correlation, F-regression, MIC, χ²

**Group 5: Feature Selection II**
1. Regularization as feature selection
2. Lasso regression
3. Model-based feature selection (random forest)
4. Recursive Feature Elimination (RFE)

**Group 6: Text Standardization and Encoding I**
1. Text cleaning with `re` / regex
2. Word tokenization
3. Normalization: stemming, lemmatization and the difference between them
4. Bag-of-Words model
5. TF–IDF

**Group 7: Text Standardization and Encoding II**
1. Historical view: word vectors
2. Word2Vec: skip-gram, CBOW
3. Byte-Pair Encoding (BPE)
4. Modern encodings using LLMs

**Group 8: Speech and Audio Data**
1. Audio feature extraction with `librosa`
2. Short-Time Fourier Transform (STFT)
3. Mel Frequency Cepstral Coefficients (MFCC)

> *Feature engineering is not about tricks – it is about understanding data. If you can explain these concepts clearly to your peers, you have truly understood them.*
