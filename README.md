# fine_drums

Welcome to **fine_drums**, a cutting-edge project focused on fine-tuning LLM models (Babbage and Davinci for now) to continue drum sequences using a Seq2Seq approach with the Groove MIDI Dataset.

## Project Overview

**fine_drums** leverages the power of advanced LLM models, specifically tailored towards generating musical content. By using a sophisticated Seq2Seq aproach, this project is capable of extending drum sequences in a coherent and musically pleasing manner. The core of this innovation lies in transforming MIDI files into a string representation, which serves as a prompt for the fine-tuned GPT models. These models, in turn, generate a continuation of the drum sequence in the same string-encoded format. Finally, this generated string is decoded back into a MIDI file, creating a seamless extension of the original drum sequence.

## How It Works

1. **Input Processing**: A MIDI file is encoded into a string representation. This step transforms the musical information contained in the MIDI file into a format that can be understood by the LLM models.

2. **Model Generation**: The string representation is used as a prompt for the fine-tuned Babbage or Davinci models. These models have been specifically trained to understand and generate musical sequences, ensuring that the output is both relevant and creative.

3. **Output Decoding**: The generated string from the LLM model is then decoded back into a MIDI file. This file represents the continuation of the original drum sequence, effectively extending the musical piece with new, AI-generated content.

## Technologies Used

- **LLM Models (Babbage and Davinci)**: State-of-the-art language models fine-tuned for musical generation tasks.
- **Seq2Seq**: A sequence-to-sequence input/output designed to handle the encoding and decoding processes of MIDI file transformations.
- **Groove MIDI Dataset**: A comprehensive dataset used for training our models, ensuring a wide variety of drum patterns and styles are represented.


