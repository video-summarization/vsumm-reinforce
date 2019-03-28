# Multi_VS

## Running tensorboard

from your local machine, run

`ssh -N -f -L localhost:16008:localhost:6008 safa@az002.csl.illinois.edu`

on the remote machine, run:

`tensorboard --logdir /scratch/safa/RL_segmentation/logs --port 6005`

Then, navigate to (in this example) http://localhost:16008 on your local machine.
