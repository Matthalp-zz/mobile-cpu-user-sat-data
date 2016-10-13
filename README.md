## Mobile CPU User Satisfaction Data

## Conditions of Use

Cite the [paper](http://ieeexplore.ieee.org/document/7446054/) whenever you use this data in any publication or presentation.

The BiBTex is provided below for convenience:

```
@inproceedings{halpern2016mobile,
  title={Mobile CPU’s Rise to Power: Quantifying the Impact of
         Generational Mobile CPU Design Trends on Performance,
         Energy, and User Satisfaction},
  author={Halpern, Matthew and
          Zhu, Yuhao and
          Janapa Reddi, Vijay},
  booktitle={High Performance Computer Architecture (HPCA),
             2016 IEEE 22nd International Symposium on},
  year={2016}
}
```

### Introduction

The data in this spreadsheet is a companion to the paper:

M. Halpern, Y. Zhu, V. J. Reddi, **"Mobile CPU's Rise to Power: Quantifying the Impact of Generational Mobile CPU Design Trends on Performance, Energy, and User Satisfaction"**, in the 22nd
Symposium on High Performance Computer Architecture (HPCA), March, 2016.

The data is presented as a CSV with the following columns:

| Column      | Description                                  |
|-------------|----------------------------------------------|
| id          | MTurk worker unique identifier (anonymized)  |
| url         | URL to YouTube video worker rated            |
| rating      | Satisfaction rating 1 - 5 (higher is better) |
| accept_time | Time worker completed survey                 |
| ip          | Worker IP address (anonymized)               |
| benchmark   | The application rated                        |
| cpu_cores   | CPU cores enabled (1, 2, 3, 4)               |
| cpu_freq    | CPU frequency in MHz <br/> (422.4, 729.6, 1036.8, 1497.6, 1958.4, 2457.6) |   
| gpu_freq    | GPU frequency in MHz <br/> (200, 320, 389, 462.4, 578) |

## Methodology

Additional methodology can be found in Section 3.1 within the [paper](http://ieeexplore.ieee.org/document/7446054/).

Equipment Specifications

| Component      | Value                       |
| -------------- |-----------------------------|
| Smartphone     | Samsung Galaxy S5 GT-I9505  |
| System-on-Chip | Qualcomm Snapdragon 8930AB  |
| CPU            | Quad-core 2.5 GHz Krait 400 |
| GPU            | 578 MHz Adreno 330          |

## Research Using this Dataset

```
Probabilistic Modeling for Crowdsourcing Partially-Subjective Ratings
An T. Nguyen, Matthew Halpern, Byron C. Wallace and Matthew Lease
AAAI HCOMP 2016
```

Source code for this work can be found at: https://github.com/thanhan/subjective-crowd-hcomp16.git

