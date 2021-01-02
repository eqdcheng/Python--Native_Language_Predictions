## Group Project part of MDS 

Our goal was to take in thousands of webpages of journal entries, and correctly predict whether the user's native language is European, or Asian. 

We manually created the reading function, all the features, and the ablation (feature selection).

Final score: 0.71 accuracy

The program is capable of reading html input files either in the zip file or as uncompressed files in the lang-8 directory. This is controlled by the optional parameter mode in the get_raw_data function.
