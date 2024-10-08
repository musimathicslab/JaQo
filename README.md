# JaQo - Just Another Quantum Orchestra 🎸

JaQo is a quantum-inspired music generation tool that uses Partitioned Quantum Cellular Automata (PQCA) to create unique MIDI compositions.\
The project is being realized for the Algorithmic Music and Sound Computing course taught by Prof. R. Zaccagnino and Prof. R. De Prisco at Computer Science Master's Degree at University of Salerno.

TODO: add report PDF file;\
TODO: cite the original repository


## Table of Contents 📕

1. [Overview](#overview)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Project Structure](#project-structure)
7. [Contributing](#contributing)
8. [License](#license)

## Overview 👓

JaQo combines quantum computing concepts with music theory to generate MIDI files. It uses PQCA to create patterns that are then translated into musical elements such as pitch, rhythm, and instrumentation.\
The repository also feats some demo music scores generated by the tool. These are the same music pieces that have been proposed in a survey to assest the creative aspect of the algorithm.

## Features 🥁

- Quantum-inspired music generation
- Interactive Jupyter notebook interface
- Customizable parameters (tempo, time signature, instruments, etc.)
- MIDI file output

## Requirements ⚙

- Python 3.9+
- Jupyter Notebook
- Dependencies listed in `requirements.txt`

## Installation 🧠

1. Clone the repository:
```sh
git clone https://github.com/your-username/jaqo.git
```
```sh
cd jaqo
```

2. Install the required packages:
```sh
pip install -r requirements.txt
```

## Usage 🎮

1. Start Jupyter Notebook
```sh
jupyter notebook
```

2. Open the `pqca_2D.ipynb` notebook.

3. Run all cells in the notebook.

4. Use the interactive widgets to set your desired parameters:
- Octave
- Tempo (BPM)
- Time Signature
- Possible Instruments (keep in mind that your score instrument rack will be chosen randomly amongst the ones you chose here!)

5. Click the "Generate" button to create a new MIDI file.

6. The generated MIDI file will be saved in the `output` directory as `pqca_2D.midi`.

## Project Structure 🌲
```
jaqo/
├── pqca_2D.ipynb    # Main Jupyter notebook
├── requirements.txt # Project dependencies
├── README.md        # This file
└── output/          # Directory for generated MIDI files
    └──demo          # Contains some demo scores' MIDI files
```

## Contributing

Contributions are welcome. Please feel free to submit a Pull Request.


## Credits

The project is partially based on the [PQCA repository](https://github.com/iccmr-quantum/PQCA_Tutorial/tree/main) created by the [Interdisciplinary Centre for Computer Music Research (ICCMR)](https://www.plymouth.ac.uk/research/iccmr) at University of Plymouth (UK).

## License

This project is open source and available under the [MIT License](LICENSE).
