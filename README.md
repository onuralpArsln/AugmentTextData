# Augmenting Your Text Data

Data augmentation is important step for Machine learning. 

When it comes to image processing  rotating image around and cropping pieces really increases capabilities of your model.

But you can not cut random peieces of text and expect it still be the same meaning.

So augmenting text based data is bit more problematic.

In this repo we will look at a  dataset  extracted from medical radiology reports. Our input will be expressions of findings in an x-ray scanning and our output will be the diagnosis from given findings.

This dataset is preapraed for a seq2seq model training similiar to text summarization.

You can find how to prepare similiar dataset from here ->  https://github.com/onuralpArsln/dataPrepWithPandas

If you have a dataset which is already well structured you can augment it directly and start training after.
