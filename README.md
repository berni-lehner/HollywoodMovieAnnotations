# Improving Voice Activity Detection in Movies
This page hosts supplementary material for
Bernhard Lehner, Gerhard Widmer, Reinhard Sonnleitner: **Improving Voice Activity Detection in Movies.** In *INTERSPEECH 2015*, 2015, Dresden, Germany.

**Abstract**
Voice Activity Detection in movies is a non-trivial and challenging task. The different emotional states of the speakers, as well as the variety of soundscapes and noises contribute to the complexity of the task. In this paper, we propose a set of lightweight features that are specifically designed to perform under such conditions, while at the same time preventing confusions of singing voice with speech. For evaluation, we use four fulllength movies, previously unseen to the system and painstakingly annotated. We compare our detector to a state-of-the-art reference system. The new approach performs better, yielding just about half the Equal Error Rate (EER). Furthermore, since the ground truth annotation task is extremely tedious, and to help with advancing in this topic, we release the annotations of all four movies to the research community.

## Content Description
This dataset contains the ground truth annotations of four full-length hollywood movies:
- The Bourne Identity (2002)
- I Am Legend (2007)
- Kill Bill – Volume 1 (2003)
- Saving Private Ryan (1998)


In the respective folders, there are remarks of specifically interesting or challenging situations faced while annotating.
The .csv files contain the original annotation done with Sonic Visualizer (https://www.sonicvisualiser.org/) and are the most precise.
The subfolders 20, 50, and 200 contain converted .arff files, where the folder name indicates the corresponding window length.
That is, the folder named *200* contains annotations for 200 ms each instance in Weka format (https://www.cs.waikato.ac.nz/ml/weka/).

For more information and examples, please visit
http://www.cp.jku.at/misc/is2015vad/

