<a href="https://github.com/ZappyMan/MorphoMetriX-V2/tree/master/demo">This is the old MorphoMetriX repository and no longer recieved updates. Click here to visit new repo.</a>
<br/>
<p align="center">
  <a href="https://github.com/ZappyMan/MorphoMetriX">
    <img src="https://raw.githubusercontent.com/ZappyMan/MorphoMetriX-V2/master/morphometrix/icon.png" alt="Logo" width="80" height="80">
  </a>

  <h1 align="center">MorphoMetriX 2.0</h1>

  <p align="center">
    A GUI for photogrammetry and morphometry
    <br/>
    <br/>
    <a href="https://github.com/ZappyMan/MorphoMetriX/blob/master/MorphoMetriX_v2_manual.pdf"><strong>Read the Manual »</strong></a>
    <br/>
    <br/>
    <a href="https://github.com/ZappyMan/MorphoMetriX-V2/tree/master/demo">See Demo Annotations</a>
    .
    <a href="https://github.com/ZappyMan/MorphoMetriX/issues">Report Bug</a>
    .
    <a href="https://github.com/ZappyMan/MorphoMetriX/issues">Request Feature</a>
  </p>
</p>
<div align="center">

[![DOI](https://joss.theoj.org/papers/10.21105/joss.01825/status.svg)](https://doi.org/10.21105/joss.01825)
[![DOI](https://zenodo.org/badge/202208604.svg)](https://zenodo.org/badge/latestdoi/202208604)
![Downloads](https://img.shields.io/github/downloads/ZappyMan/MorphoMetriX/total) 
![Contributors](https://img.shields.io/github/contributors/ZappyMan/MorphoMetriX?color=dark-green) 
![Stargazers](https://img.shields.io/github/stars/ZappyMan/MorphoMetriX?style=social) 
![Issues](https://img.shields.io/github/issues/ZappyMan/MorphoMetriX) 
![License](https://img.shields.io/github/license/ZappyMan/MorphoMetriX) 

</div>

## Table Of Contents

* [About the Project](#about-the-project)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing)
* [License](#license)
* [Authors](#authors)
* [Acknowledgements](#acknowledgements)

## About The Project

![Screen Shot](https://raw.githubusercontent.com/ZappyMan/MorphoMetriX-V2/master/images/Screenshot%202024-04-08%20at%205.34.38%E2%80%AFPM.png)

Let MorphoMetriX streamline the often tedious process of making photogrammetric measurements for you, offering a quick intuitive GUI to calculate piecewise/arc lengths and width profiles along segments/curves and areas for polygons. 
    
Also check out [CollatriX](https://github.com/cbirdferrer/collatrix)<sup>1</sup>, a GUI to collate multiple MorphoMetriX outputs into a single datafile with add-on functions for correcting altitude error from UAS (drone) flights and calculating animal body condition.

1. Bird, C.N., and Bierlich, K.C. (2020). CollatriX: A GUI to collate MorphoMetriX outputs. Journal of Open Source Software, 5(51), 2328. [https://doi:10.21105/joss.02328](https://joss.theoj.org/papers/10.21105/joss.02328) 


## Getting Started

To install MorphoMetrix go to our [releases page](https://github.com/ZappyMan/morphometrix/releases) and download either the dmg (for macs) or exe (for windows). For further detail, please see our [manual pdf](https://github.com/ZappyMan/MorphoMetriX/blob/master/MorphoMetriX_v2_manual.pdf). Continue reading if you prefer to run the source code locally.

### Prerequisites

To run MorphoMetrix you need to install:

* python 3.10

Optionally, we recommend using anaconda for better control over your python environment.

### Installation

1. Open your terminal and clone the repo

```sh
git clone https://github.com/ZappyMan/MorphoMetriX-V2.git
```

2. Install Python packages

```sh
pip install -r requirements.txt
```

3. Launch MorphoMetriX GUI

```sh
python3 morphometrix/__main__.py
```

## Usage

For further detail, please see our [manual pdf](https://github.com/ZappyMan/MorphoMetriX/blob/master/MorphoMetriX_v2_manual.pdf)

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.
* If you have suggestions for adding or removing projects, feel free to [open an issue](https://github.com/ZappyMan/MorphoMetriX/issues/new) to discuss it, or directly create a pull request after you edit the *README.md* file with necessary changes.
* Please make sure you check your spelling and grammar.
* Create individual PR for each suggestion.
* Please also read through the [Code Of Conduct](https://github.com/ZappyMan/MorphoMetriX/blob/main/CODE_OF_CONDUCT.md) before posting your first idea as well.

### Creating A Pull Request

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See [LICENSE](https://github.com/ZappyMan/MorphoMetriX/blob/main/LICENSE.md) for more information.

## Authors

* **Elliott Chimienti** - *OSU Computer Science Graduate Student* - [Elliott Chimienti](https://github.com/ZappyMan/) - *Maintainer*
* **KC Bierlich** - *Postdoctoral Scholar, PhD Marine Science and Conservation* - [KC Bierlich](https://mmi.oregonstate.edu/people/kevin-bierlich)
* **Clara Bird** - *PhD Candidate, Department of Fisheries, Wildlife & Conservation Sciences* - [Clara Bird](https://mmi.oregonstate.edu/people/clara-bird)
* **Walter Torres** - *Postdoctoral Researcher, PhD, Marine Science & Conservation*
