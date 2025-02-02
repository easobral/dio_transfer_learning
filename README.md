# Transfer learning project

## Introduction
  This project aims to practice and show the knowledge acquired regarding the topic of "transfer learning" in neural networks.By the end we will have trained two neural networks, one from scratch and another using the transfer learning technique, and compare both of them in order to evaluate the best case. The goal of each network is to classify a set of images to differentiate between dogs, cats and chickens.

  We will be using keras and tensorflow to train and run inferences. We will also be using 484 images for each category extracted from https://www.tensorflow.org/datasets/catalog/cats_vs_dogs (for cats and dogs). and https://github.com/gunthercox/chicken-photos/tree/master (for chickens)

## Run
  To execute this project can just run the file "transfer_learning copy.ipynb" as a jupyter notebook.

  the lines:
    tf.config.threading.set_intra_op_parallelism_threads(2)
    tf.config.threading.set_inter_op_parallelism_threads(2)
  can be removed. They were included because tensorflow was running in local setting and 
