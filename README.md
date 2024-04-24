# Generating Expressive Performance

This study is a part of the DH-401 Digital musicology course at EPFL.

In this work, our objective is to analyze the elements contributing to the expressiveness of a musical performance and subsequently generate an artificial rendition of a piece based on our observations.


## Dataset

The data utilized is sourced from the [Aligned Scores and Performances (ASAP) dataset](https://github.com/fosfrancesco/asap-dataset), which comprises aligned musical scores in both MIDI and MusicXML formats, alongside corresponding performances in audio and MIDI formats. Each entry in the dataset is annotated with downbeat, beat, time signature, and key signature information.

For our analysis, we choose to focus on the [Mozart's Piano Sonatas No. 8](https://github.com/fosfrancesco/asap-dataset/tree/master/Mozart/Piano_Sonatas/8-1) subcorpus.

## Instructions
### Task A (Listening and analyzing)
Listen to a raw midi performance of the piece, and then compare it with a human performance (of your choice) of the same piece. In what ways do they differ? Analyze the recorded performance (e.g. using dynamic markings, accents, and etc.) and write a short paragraph (about 300 words) of your reflections. This should be part of the introduction in your report.

For instance, you may think about: is there a general pattern on how these performance attributes relate to the symbolic aspects of the score? Do you hear clear phrasings in the performance? What does the ending of a typical phrase sound like? But note that don't be constrained by these questions. They are here just to inspire you to explore the performance.

### Task B (Generating expressive MIDI)
From your analysis in task A, think about how to model these aspects computationally. In this task, choose one or more aspect(s) in your analysis you would like to model.

You should write an algorithm that outputs a MIDI file from an musicXML or the unperformed MIDI. In your report, please clearly describe your model.

### Task C (Reflecting on the generated MIDI)
Compare your generated MIDI with both the unperformed MIDI and the human performace recording. Discuss their differences and potentially what and how you can further improve. This should be part of your discussion section in the report.



## Credits
Authors: Romane Clerc - Octavio Profeta - Cindy Tang - Shu Yang

Professor: Martin Rohrmeier

Course: DH-401 Digital musicology, EPFL

Date: 24.04.2024
