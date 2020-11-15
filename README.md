## A.I. Duet

A piano that responds to you.

## About

This experiment lets you make music through machine learning.To make this project, we trained a neural netword on many MIDI (Musical Instrument Digital Interface) files and the computer was able to learn a lot about some of the key components of music, like notes, timings, keys, and tempo. On the user side, all you have to do is play a few notes or a melody, and the neural net will respond with a continuation of that, fit to what you played! 

## OVERVIEW
A.I. Duet is composed of two parts, the front-end which is in the `static` folder and the back-end which is in the `server` folder. The front-end client creates short MIDI files using the players's input which is sent to a Flask server. The server takes that MIDI input and "continues" it using [Magenta](https://github.com/tensorflow/magenta) and [TensorFlow](https://www.tensorflow.org/) which is then returned back to the user and shown as notes on the piano!
