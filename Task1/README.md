Firstly, there is a baseline script, which serves as the baseline model script for this experiment.

Then, there is a hard negative mining script, that once run generates a .pkl file which contains a hard negative (semantically similar, but different paper) for each query in our dataset. Run it first to obtain the hard negatives.

After the hard negative file(s) are generated, the stageA files should be run. In them, the lang parameter can be changed so the model is run targeting tweets of a specific language. For now, models being trained seperately for each language to get the score per language.