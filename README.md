# Steles_kws_database


## Source:

https://vietnamica.hypotheses.org


## Contents:

- images_150.0/collection1/*.png

Character images extracted from the stele images used in the VIETNAMICA project, rescaled to a width of 150 pixels.

- graphs_s150.0_d5/collection1/*.gxl 

Graphs extracted from the character images using a node distance of 5 pixels.

- split/kws/kws_freq_collection1.txt

Keywords and their frequency in the train, valid, and test set. They appear at least 5 times in the train set, once in the valid set, and once in the test set.

- split/kws/kws_collection1.txt

For each keyword, the five first graphs in the training set. They can be used for template-based keyword spotting.

- split/train/chars_collection1_train.txt

Graphs of the training set. The ID "0x213e2_collection1_00565_319_1294_355_1331" contains the unicode of the character (0x213e2), the page (00565), and the original coordinates x1, y1, x2, y2 (319, 1294, 355, 1331) before rescaling.

Character frequencies are also indicated in a separate file. Same for the valid and test sets.
