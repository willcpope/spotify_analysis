# Using the Spotify API for Songwriting Inspiration
Using the Spotify API, I analyzed various song features as inspiration to write a chord progression in Logic Pro. The chord progression can then be saved as a MIDI file and used to train Magenta's (TensorFlow) Transformer machine learning model to generate a long-form piece of music.

## API Notebook
The api notebook pulls specific artist data from the Spotify API and saves the information as a .csv.

## Analysis Notebook
The analysis notebook converts the artist data to a dataframe. The information I was primarily interested in was:

* Key (converted from numeric identifier to standard letter scale)
* Mode (converted from numeric identifier to Major and Minor)
* Time Signature
* Tempo
* Duration

## Next Steps
Knowing select features of a song can inspire a chord progression that can be performed in Logic Pro using Logic Remote. The chord progression can then be saved as a MIDI file and used to train Magenta's Transormer machine learning model to generate a unique piece of music. The unique song can then be saved as a MIDI file and edited in Logic Pro.
