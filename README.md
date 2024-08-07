# VAE-GNA: Variational Autoencoder using Gaussian Neurons and Attention Layer

_**Springer Paper:**_ \
**Title:** VAE-GNA: a variational autoencoder with Gaussian neurons in the latent space and attention mechanisms (Language: English) \
Link to the paper: [https://link.springer.com/article/10.1007/s10115-024-02169-5](https://link.springer.com/article/10.1007/s10115-024-02169-5)

_**MSc. Dissertation:**_ \
**Title:** Autoencoder Variacional com Neurônios Gaussianos e Mecanismos de Atenção para Detecção de Câncer Usando Dados Espectrais (Language: Portuguese - Brazil) \
Link to the Dissertation: [https://informatica.ufes.br/en/pos-graduacao/PPGI/thesis-details?id=14992](https://informatica.ufes.br/pt-br/pos-graduacao/PPGI/detalhes-da-tese?id=21269)

## Supplementary Code

This repository contains the code developed for my master's dissertation and my VAE-GNA paper. Below are the instructions on how to use it. If you find any bugs or have any observations, please let me know. Don't hesitate to get in touch with me.

## Dependencies

The code is developed in a Python environment, specifically using Jupyter Notebook. The deep learning models are implemented using PyTorch and Scikit-Learn.

To install all dependencies, ensure you have Python set up on your Linux/Windows machine, then run the following command:

```
pip install -r requirements.txt
```

## Project Structure

Project structure for the VAE-GNA repository:

```
VAE-GNA/
├── Confusion_Matrix/
├── Loss_Plot/
│ └── pkls/
├── data/
├── imgs/
├── model/
│ └── Kfold_results/
├── results/
├── results_per_fold/
├── LICENCE
├── README.md
├── requirements.txt
└── vaegna_jpyt.ipynb
```

## Usage

How to use the code in this repository?

1. Clone the repository:

```
git clone https://github.com/MatheusBecali/VAE-GNA/
cd VAE-GNA
```

2. Install the required dependencies:

```
pip install -r requirements.txt
```

3. Run the Jupyter Notebooks:

```
jupyter notebook
```
or open the jupyter notebook extension in Visual Studio Code (Works on Linux and Windows)

4. Open and run the desired notebook, such as `notebooks/vaegna_jpyt.ipynb`.

## Features

- Variational Autoencoder implementation with Gaussian neurons.
- Incorporates an attention layer to improve model performance.
- Detailed analysis and visualization of results.

## Contributing

If you wish to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## Contact

If you have any questions or feedback, feel free to reach out to me at [matheusbecali@gmail.com](matheusbecali@gmail.com).
