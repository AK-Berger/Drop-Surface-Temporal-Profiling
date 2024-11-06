# Drop-Surface-Temporal-Profiling
Drop-Surface Temporal Profiling: A method for analyzing dynamic drop-surface interactions by capturing time-series data of drop width, length, and contact angles on a moving surface. Suitable for surface science and fluid dynamics research.



## Citation

This GitHub repository is based on research presented in the article "Deep Learning to Analyze Sliding Drops," with enhancements and improvements applied for practical implementation. If you use this repository or its contents in your research or project, please make sure to cite our work as follows:

- **DOI**: [10.1021/acs.langmuir.2c02847](https://doi.org/10.1021/acs.langmuir.2c02847)  
- **Authors**: Sajjad Shumaly, Fahimeh Darvish, Xiaomei Li, Alexander Saal, Chirag Hinduja, Werner Steffen, Oleksandra Kukharenko, Hans-Jürgen Butt, Rüdiger Berger  
- **Title**: *Deep Learning to Analyze Sliding Drops*  
- **Journal**: Langmuir  
- **Year**: 2023

### Citation Format (BibTeX)
If you are using LaTeX, you can use the following BibTeX entry for citation:

```bibtex
@article{shumaly2023deep,
  title={Deep learning to analyze sliding drops},
  author={Shumaly, Sajjad and Darvish, Fahimeh and Li, Xiaomei and Saal, Alexander and Hinduja, Chirag and Steffen, Werner and Kukharenko, Oleksandra and Butt, Hans-Jürgen and Berger, Rüdiger},
  journal={Langmuir},
  volume={39},
  number={3},
  pages={1111--1122},
  year={2023},
  publisher={ACS Publications}
}
```




## Dependencies

This project requires the following Python libraries:

- `matplotlib==3.8.0`
- `opencv-python==4.9.0`
- `numpy==1.26.2`
- `scipy==1.11.4`
- `pandas==2.1.4`
- `natsort==8.4.0`

Built-in libraries (`glob`, `os`, and `shutil`) are also used but do not require installation.

### Installation

You can install the dependencies using `requirements.txt` by running:

```bash
pip install -r requirements.txt
