# GCC_2024_Advanced_Tool_Training

Welcome to the the advanced tool training! This repository showcases the development stages of [Sylph](https://github.com/bluenote-1577/sylph), a bioinformatic tool focuse on metagenomic profiling, and provides a look at several stages in its development that highlight some of the more advanced features when wrapping a tool.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [License](#license)
- [Contact](#contact)

## Introduction

Sylph is a program that performs ultrafast (1) ANI querying or (2) metagenomic profiling for metagenomic shotgun samples and is often being used in metagenomic sequencing. As a result the tool was recently wrapped and added to galaxy to allow for users to have access to this new methodology. This repository contains several directoires that show the tool wrapping development of Sylph in different stages and are intended to emphasis the addition of certain advanced tool wrapping concepts. We will explore thse different concepts in our Adavanced Tool training. Below is additional information about this project and how to run it locally. 

## Installation

### Prerequisites

- Python 3.x
- Git
- Planemo 

### Clone the Repository

```bash
git clone https://github.com/tcollins2011/GCC_2024_Advanced_Tools_Training.git
cd GCC_2024_Advanced_Tools_Training
```

### Installing Planemo

```bash
python3 -m venv venv
source venv/bin/activate 

pip install planemo
```


## License 
This project is licensed under the MIT License. See the [LICENSE](LICENSE.txt) file for details.

## Contact 
For questions or suggestions, please open an issue or contact the project maintainer at tcolli32@jhu.edu.