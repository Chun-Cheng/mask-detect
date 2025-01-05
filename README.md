# mask-detect

Detect whether the people wear masks.

<p align="center">
  <img src="docs/media/demo.jpg" alt="demo" height="400"/>
</p>

## Usage

### Environment setup

1. Install [Python](https://www.python.org/) (>=3.12), [Poetry](https://python-poetry.org/docs/#installation) (>=2.0).

2. Install dependencies.

    ```sh
    poetry sync --no-root
    ```

### Detect

Use [src/detect.ipynb](src/detect.ipynb) to detect the people in the picture and the masks.

### Train model with custom dataset

Follow the instructions in [src/train.ipynb](src/train.ipynb). A label-modification utility is also provided as [src/train_utility.ipynb](src/train_utility.ipynb).
