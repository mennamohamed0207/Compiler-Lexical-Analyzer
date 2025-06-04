# Compiler Lexical Analyzer

This repository contains a Python-based implementation of a compiler lexical analyzer, focusing on the process of converting regular expressions into finite automata (NFA, DFA, and Minimized DFA). The codebase is organized primarily in Jupyter notebooks, demonstrating the theoretical and practical steps of lexical analysis as part of a compiler's front-end.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributors](#contributors)
- [License](#license)

## Overview

The goal of this project is to:
- Convert a regular expression (regex) into an NFA (Non-deterministic Finite Automaton).
- Transform the NFA into a DFA (Deterministic Finite Automaton).
- Minimize the resulting DFA.
- Visualize each stage and export automata structures to JSON files.

This process demonstrates foundational compiler theory and is useful for students and educators working with lexical analyzers.

## Features

- **Regex to NFA**: Uses the Shunting Yard Algorithm to parse infix regex into postfix, and then constructs an NFA.
- **NFA to DFA**: Converts the NFA into an equivalent DFA.
- **DFA Minimization**: Reduces the DFA to its minimal form.
- **Visualization**: Automata visualizations are generated using Graphviz.
- **Export**: Automata structures can be exported to JSON for further processing.

## Getting Started

### Prerequisites

- Python 3.9 or newer
- Jupyter Notebook
- `graphviz` Python package

You can install the required Python package with:
```bash
pip install graphviz
```

You must also have [Graphviz](https://graphviz.gitlab.io/download/) installed on your system.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mennamohamed0207/Compiler-Lexical-Analyzer.git
   cd Compiler-Lexical-Analyzer
   ```

2. Open the Jupyter notebooks (`regex_to_NFA.ipynb`, `NFA_to_Min_DFA.ipynb`) in Jupyter Lab or Notebook.

## Usage

- **regex_to_NFA.ipynb**: Main notebook for entering a regex, generating the NFA, converting to DFA, minimizing, and visualizing/exporting automata.
- **NFA_to_Min_DFA.ipynb**: Supplemental notebook for in-depth DFA minimization and visualization.

Typical workflow:
1. Input your regular expression in the designated cell.
2. Run the notebook cells to process the regex through NFA, DFA, and Min DFA stages.
3. Visual outputs and JSON representations will be generated in the working directory.

## Project Structure

```
.
├── NFA_to_Min_DFA.ipynb        # DFA minimization and visualization
├── README.md                   # Project documentation
├── regex_to_NFA.ipynb          # Main notebook: regex → NFA → DFA → minDFA
```

## Contributors

- Sara Bisheer Fekry 
- Menna Mohamed Abdelbaset

Colab Link: [Google Colab](https://colab.research.google.com/drive/1yzHmrIeb2ECwYaF3IvXnmAlxYrX1JbrL?usp=sharing)

