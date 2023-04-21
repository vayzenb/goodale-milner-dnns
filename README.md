# Goodale Milner DNN simulations

The accompanying code repository for: 
Ayzenberg, V., Blauch, N., and Behrmann, M. (2023). Using deep neural network to address the how of object recognition. PsyArxiv.

Here we examined whether a range of DNNs can discriminate object stimuli that were presented to patients with dorsal or ventral lesions by Goodale, Milner, and colleagues. 

The figures folder contains all figures used in the main-text. The RDMs sub-folder contains similarity matrices for every stimulus and transformation condition from every model layer.

The manipulate_stim notebook renders the stimuli in different orientations and sizes.

The classifier_discrimination notebook uses a Ridge classifier, a supervised linear classifier, to test exemplar classification across orientation and size changes.

The similarity_discrimination notebook uses Pearson correlation similarity to test exemplar classification across orientation and size changes.

