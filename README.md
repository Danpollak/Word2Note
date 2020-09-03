# Word2Note - Lyrics to MIDI Generator

## [Project Structure](/Documents/README.md)  
## [Results](/MIDI_Results/README.md)

## About This Project

In this project we aim to try and implement a generative recurrent model with the goal of generating a genre
appropriate and fitting melody for a given song lyrics. We choose this subject due to our interests in music
and because we believe that solving a sophisticated task in one domain could lead to discovery of solution
and better understanding of tasks in other domain

The project is the Final Project submission for NLP course for Spring semester 2020 at IDC Herzliya by Dr. Kfir Bar.

## How to use

*You will need the [DALI Dataset](https://github.com/gabolsgabs/DALI) In order to reproduce this project.

The DALI_Preprocessing notebook will allow you to convert the DALI dataset into tuples of (_character_,_note_,_word_), divided into sentences.

The Model Notebook is the model itself. You should change the path of the dataset before using.

The Midi_Generator is used to convert the output of the model into MIDI files. You can change the tempo and other technical musical parameters in order to refine the output.  
The sentences provided to the Midi_Generator must be gramatically correct, and therefore has post-processing methods included (First note and Majority note).

