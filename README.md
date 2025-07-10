# music-composer-classifier
Classifies classical pieces by composer using ML.

This project applies machine learning to identify the composer of a Western Classical music piece based on its MIDI file. It focuses on compositions by J.S. Bach, Ludwig van Beethoven, and Frédéric Chopin, representing the Baroque, Classical, and Romantic eras respectively. I used the MAESTRO dataset, and I extracted 57 meaningful features from each composition, including pitch patterns, note intervals, and rhythm, using the music21 library.

I trained a Random Forest classifier on 435 pieces and achieved 96.5% accuracy on the test set, with F1-scores above 0.96 for all three composers. The model also helped us understand how musical styles differ across eras by analyzing which features were the most important.

The dataset used is [MAESTRO v3.0.0](https://magenta.tensorflow.org/datasets/maestro), introduced in a 2019 ICLR paper by Hawthorne et al.
