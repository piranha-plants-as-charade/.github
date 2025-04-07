<picture>
  <source media="(prefers-color-scheme: dark)" srcset="../branding/logo-light.svg" />
  <img src="../branding/logo-dark.svg" alt="logo" height="250px" />
</picture>

# Piranha Plants as Charade

The premise of this project is to transform an input melody into a full-fledged song in the style of [&ldquo;Piranha Plants on Parade&rdquo;](https://www.youtube.com/watch?v=3EkzTUPoWMU) from _Super Mario Bros. Wonder_.

Record or upload a melody and we'll transform it into a masterpiece that sparks joy ✨

## How it works

**Melody input**: a melody is uploaded in the form of a `.wav` file to be processed by our program.

**Melody extraction**: the uploaded `.wav` file is processed using various audio processing techniques such as PYIN and Harmonic-Percussive Source Separation to simplify it into a sequence of discrete midi notes.

**Chord generation**: a sequence of chords is generated to complement the melody following the style of "Piranha Plants on Parade" using Hidden Markov Models and a modified version of the Viterbi algorithm.

**Accompaniment generation**: accompanying parts are generated based on the melody and chords.

**Audio export**: audio is generated for each part using either a MIDI library or a custom audio sample library.

Et violà! Any melody in the style of your favorite Mario tune.
