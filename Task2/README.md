The code builds upon the provided baseline and evaluation scripts.

Approaches are separated using sections, with first one for the baseline model, second one uses the LlaMA 3.2 3B model (quantized int4), and the third approach is using Pairwaise Ranking.

To run for any of the three languages (English, Spanish, Arabic), modify the language variable and set the paths accordingly (they are linked to Drive by default).

Too run a specific approach, only run the cells underneath its heading. All headings in the start (Preamble, Preprocessing, Language, etc), need to be run beforehand, with the exception of the Data section, which is only required once to generate data from the given json files, and need not be run each time.
