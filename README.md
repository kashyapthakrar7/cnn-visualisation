# Setting Up

## Getting this Repo

1. (Option 1) You can download this repo [by clicking on this line](https://github.com/soumendra/cnn-visualisation/archive/master.zip)
    - After downloading it, extract and rename the extracted folder to `cnn-visualisation`
2. (Option 2) You can clone this repo and change into it
    - (if you have set-up your SSH key) run `git clone git@github.com:soumendra/cnn-visualisation.git; cd cnn-visualisation`
    - (if you have not set-up your SSH key) run `git clone https://github.com/soumendra/cnn-visualisation.git; cd cnn-visualisation`

## Linux (Ubuntu)

Assuming you are inside the `cnn-visualisation` folder:

1. Make the scripts executable: run `chmod +x *.sh`
2. Install Miniconda (skip if you have miniconda or anaconda installed): `./conda.sh` (run in terminal)
3. Close your terminal application. Start it again.
4. Create the *cnn* environment: `conda env create -f cnn.yml` (run in terminal)

To start using this environment:

1. `source activate cnn` (run in terminal)

Note: You can also install [using the official guide](https://conda.io/docs/user-guide/install/linux.html), but using the `conda.sh` script is likely to be more painless.

## Windows

1. Install Anaconda using this guide: https://conda.io/docs/user-guide/install/windows.html
2. Start `Anaconda Prompt` (you can search for it). This will open a terminal.
3. In the terminal, navigate to the folder where you unzipped this repo (covered in *Getting this Repo* section).
4. Create the *cnn* environment: `conda env create -f cnn.yml`

For more on using Anaconda on Windows: https://docs.anaconda.com/anaconda/user-guide/getting-started/#open-nav-win .

## Mac

1. Install miniconda using the official guide: https://conda.io/docs/user-guide/install/macos.html
    - Alternatively, install using homebrew
        * Install homebrew: https://brew.sh/
        * Install miniconda: `brew install miniconda` (run in terminal)
2. Close your terminal application. Start it again.
3. Assuming you are inside the `cnn-visualisation` folder:
    - Create the *cnn* environment: `conda env create -f cnn.yml`

To start using this environment:

1. Close your terminal application. Start it again
2. `source activate cnn` (run in terminal)
