# CONSTRAINT

0. This repository contains submodules. To install them together with the repository, run

    `git clone --recursive [repo]`

    If the repository is already cloned, run

    `git submodule update --init --recursive`

1. Install the dependencies required by <https://github.com/rycolab/aclpub2>: Python dependencies, Java, LaTeX dependencies.

2. Make sure that the aclpub2 submodule is in your path by running
`` export PYTHONPATH=$(pwd)/aclpub2:$PYTHONPATH. ``

3. To build the proceedings, please run `` aclpub2/bin/generate . --proceedings  --overwrite``. Then inspect ``build/proceedings.pdf`` to make sure the output is valid.
