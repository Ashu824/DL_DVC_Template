# Deep Learning Project Template

This repository serves as a template for organizing your deep learning projects using a standardized structure. The template includes a `template.py` script that can be used to create the necessary project structure. The basic structure of this template is outlined below:

## Project Structure

1. **src**: This folder contains all Python scripts for your deep learning project.
   - **project_name**: A folder specific to your project, containing the following subfolders:
     - **components**: Store your model components (e.g., layers, loss functions) here.
     - **utils**: Utility scripts/functions for data preprocessing, visualization, etc.
     - **config**: Configuration files for your project (e.g., hyperparameters, paths).
     - **pipeline**: Scripts for data loading, preprocessing, training, and evaluation.
     - **entity**: Define custom data structures or classes relevant to your project.
     - **constants**: Store any constant values or enumerations here.

2. **config**: Configuration files for your project. The main configuration file is `config.yaml`, which can be used to update project-specific settings.

3. **DVC.yaml**: Data Version Control (DVC) configuration file. Use DVC to manage and orchestrate your data pipeline stages.

4. **tox.ini**: Configuration for creating different environments. This file is useful for setting up GitHub Actions or other CI/CD workflows.

5. **pyproject.toml**: Specifies build-tool dependencies. It helps pip read the project's dependencies and versions, such as setuptools or wheel.

6. **setup.py** and **setup.cfg**: Files for packaging your project for distribution via pip or other Python packaging tools.

## Getting Started

To create a new project based on this template, follow these steps:

1. Run the `template.py` script to create a new project structure:
   ```bash
   python template.py 
   ```
   
2. Customize the project structure, add your deep learning code, and modify the configuration files as needed.

## Usage

Here are some common tasks and tips for using this project template:

- Use the `src` folder to organize your Python scripts, and create modular components to improve code maintainability.

- Update the `config.yaml` file in the `config` folder with your project-specific configuration settings.

- Utilize DVC to manage data versioning and pipeline orchestration. Refer to `DVC.yaml` for defining your data pipeline stages.

- Modify the `tox.ini` file for setting up different environments, especially if you plan to use GitHub Actions for automated testing and deployment.

- Define your project dependencies and versions in the `pyproject.toml` file.

- Customize the `setup.py` and `setup.cfg` files to package and distribute your project if necessary.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

I would like to express my gratitude to the following individuals and organizations for their contributions and inspiration:

- [Ineuron](https://ineuron.ai)

- [SUNNY BHAVEEN CHANDRA (GitHub: c17hawke)](https://github.com/c17hawke)

For their open-source contributions, FSDS course, and for sharing their knowledge on GitHub, which has been a source of inspiration for this project template.

Happy deep learning coding! 🚀

