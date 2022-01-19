
## Info


main.py loads the config.txt file. The main program takes a stream of instructions from config.txt and then terminates.

The functions of the program are:
- dataset generation
- model training
- model testing
- model outputting


The instructions are to batch each step of the ML workflow. 


A config workflow from start to finish is


generate dataset -> train -> output (->test) 


This program generates files in the current directory of the project.

modeltrainingoutput.txt, this contains the loss from the ml training organized by model

files in use:
- main.py
- models.py (holds model classes)
- data_generator.py (generates input/output BS option data)
- neural_network.py (contains the code for dataloading, training, testing, outputting the model)

## Instruction Format






## Libraries used


1. Volib
    - https://vollib.org/license.html
    - Free to use without any restrictions
