# Course Data Analysis in Python

Welcome to the Course "Data Analysis in Python" repository! This repository contains all the materials and resources for the course.

## Organization

The repository is organized as follows:

- `Course`: This folder contains the presentations and exercises for the course. Each topic has its own jupyter notebook with the corresponding materials.

- `Filled_Course`: This folder contains the already completed notebooks and the solutions to the exercises in the `Course` folder. It is meant for reference purposes for teaching the course and as a fallback if something is missing from the notes students made during the course.

- `Data`: This folder contains the data used during the presentation and the exercises

- `mplstyles`: Some matplotlib styles to use as examples during the course.

## Getting Started as student

To get started with the course, follow these steps:

1. Clone the repository to your local machine using the following command or you can download this repo as zip file:

    ```
    git clone https://github.com/DurhamARC-Training/DataAnalysisPython
    ```

2. If you want to set up a new conda environment for the course you can use the environment.yml provided in this folder.

3. Navigate to the `Course` folder to access the presentations and exercises to use during the course.

4. If you need assistance, refer to the `Filled_Course` folder for the solutions.

5. There is also a python script which downloads everything (including the filled notebook) as a ZIP archive and extracts it a folder if GIT isn't available:

      a. Download the `pull_files_from_repo.py` file and put it into your environment

      b. Execute `python pull_files_from_repo.py` in the folder.

## Getting Started for Teaching

To get started with teaching the course, follow these steps:

1. Install the requirements including JupyterLab Deck by running the following command:

    ```
    conda env create -f environment.yml
    ```

2. Launch JupyterLab by running the following command:

    ```
    conda activate teaching_data_analysis
    jupyter lab
    ```

3. Navigate to the `Course` folder to access the presentations and exercises to use during the course. If needed use the notebooks in the `Filled_Course` as lecture notes

4. Click on the little card styles JupyterLab-Deck icon for running a notebook as a presentation.

## Contributing

If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request. Contributions are welcome!

You can add the files of the `common-tools-for-teaching` github submodule by typing in `git submodule update --init`. Consult the README in the then filled `common-tools` directory for further instructions.
In general you should never edit the files contained within the `Course` folder, but work on `Filled_Course` and have the tool generate the student notebook  versions automatically.
