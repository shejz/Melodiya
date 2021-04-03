# Melodiya
A music web application that generates melodies using AI, based on the musical ideas of the user.


1. Create a form so that users can add the seed notes of the melody the AI will generate.
  - Adding a form and capture the inputs using js.
2. Create a staff using EasyScore from Vexflow
  - EasyScore is the fastest way to get started with VexFlow. You can use it to generate all the basic VexFlow elements necessary for a sequence of musical notation and extend    them with the standard VexFlow API.
  - The EasyScore language supports notes, accidental beams, dot tuplets and other common musical notation elements. [cdnjs](https://cdnjs.com/)
  - Add a staff using Vexflow where users can see, hear and edit the seed notes of the melody
3. Create a parser that takes the notes from the form and convert them into a readable format that Vexflow can understand
4. Add the note from the parser to the staff created in Vexflow
5. integrate Tone.js into the app and create a Sampler using this library
6. Create a class using Tone.js so users can hear the seed notes of the melody
  - Using Tone.js to play the notes of our staff
7. Generate a melody using magenta.js based on the seed melody of the user
  - Generating a melody using MusicRNN. MusicRNN implements Magenta's LSTM-based language models. 
8. Add a midi player so user can hear the generated melody
  - Adding HTML midi player and visualizer
