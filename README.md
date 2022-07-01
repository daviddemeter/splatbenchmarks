# splatbenchmarks

## Introduction

This repository contains the SPLAT datasets and code for the analyses presented in Who’s on First?: Probing the Learning and Representation Capabilities of Language Models on Deterministic Closed Domains.

## Datasets

SimPlified Language Activity Traces (SPLAT) datasets are provided for chess and baseball domains, and are derived from game traces available at lichess.org and Major League Baseball Gameday files, respectively.  Each dataset contains two sets of files:

•	Pre-training files such as chess.train400K.txt which contain full game traces and are used to train a model with background knowledge of gameplay, and
•	Fine-tuning files such as chess.finetune50K.txt where contain partial game traces up to time t at which point a probing question is posed (details on probing tasks are provided in the paper).

The numerical part of each filename indicates the number of games contained in the file.  The chess data set contain the additional file chess.legal.txt, which like the fine-tuning files contain partial game traces up to time t, followed by an enumeration of all legal moves for the current board configuration.

## Model and Checkpoints

Soon.

## Training and Usage Scripts

Soon.

## Acknowledgements

If you use this code or these models, please cite the following paper:

> @inproceedings{Demeter2021WhosOF, title={Who’s on First?: Probing the Learning and Representation Capabilities of Language Models on Deterministic Closed Domains}, author={David Demeter and Doug Downey}, booktitle={CONLL}, year={2021}}
