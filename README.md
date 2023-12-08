# gnn-gui

A visualization tool for graph neural networks in materials science

Created for Purdue CS 501

- Nethra Balachandar^[balachn@purdue.edu]

- Satarupa Gupta^[gupta872@purdue.edu]

- Ethan Holbrook^[holbrooe@purdue.edu]

- Kat Nykiel^[knykiel@purdue.edu]

## Installation

TODO: get OS-independent installation. This only seems to work on OS X.

### Using Conda

Build the conda environment from the environment file:

```conda env create -f environment.yml```

Load the new environment

``` conda activate gnn-gui ```

And test the GUI

```python main.py```

Congratulations!

## TODOs

### GUI (Nethra)

- [x] fix the scaling of the GUI
- [x] clean up GUI (remove extra buttons)
- [x] add place to show property predictions in the GUI

### GNNs (Satarupa)

- [ ] connect GNNs other than MatGL (ALIGN, etc)
- [X] determine which properties we want to predict

### Inputs (Ethan)

- [X] let users query materials project
- [ ] ensure vis is working

### Visualization (Kat)

- [ ] add structure vis to GUI
- [ ] add embedding vis to GUI
- [X] add neural network vis?

### Other

- [X] get stable, reproducible python env
- [ ] structure paper
- [ ] Everyone update sections based on work they have completed
- [ ] Presentation slides on work completed
- [X] set up on overleaf
