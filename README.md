<h1 align="center">
<br>
  <img src=https://github.com/ViniciusRubens/Shalow-Neural-Network/blob/main/images/SHALOW%20NEURAL%20NETWORK%20Logotipo.png alt="SHALOW NEURAL NETWORK" width="200">
<br>
<br>
SHALOW NEURAL NETWORK
</h1>

<p align="justify">
My project is based on the development of a machine learning using the concepts of Shalow Neural Network. 

As Redes Neurais Rasas são representações simplificadas e didáticas das Redes Neurais Profundas que são mais complexas. Neste projeto, as características de entradas que são tiradas das imagens processadas tanto para teste quanto para treino são empilhadas verticalmente na Camada de Entrada, de índice 0. Cada uma dessas características estarão ligadas por neurônios responsáveis pelos cálculos para reconhecimento de padrões, que denominaremos de Camada Oculta, de índice 1. Por fim, o resultado da nossa predição é obtida na Camada de Saída, de índice 2, que possui um único nó, podendo ser 0 ou 1.
</p>

<h1 align="center">
<br>
  <img src=https://github.com/ViniciusRubens/Shalow-Neural-Network/blob/main/images/model_example.png alt="SHALOW NEURAL NETWORK" width="200">
<br>
</h1>

<p align="justify">
Os valores que as diferentes camadas estão transmitindo são denominados de Valores de Ativação, que serão armazenados em matrizes chamadas de A neste projeto. Neste caso, as ativações da Camada Oculta são os valores armazenados em A1, enquanto que os resultados da Camada de Saída estão armazenados em A2.

Cada uma das camadas está associada à parâmetros W e b, que serão atualizados de acordo com os cálculos da Forward e Backward propagation, diminuindo assim a Função de Custo, melhorando a precisão e acurácia do projeto.
</P>

<h1 align="center">
<br>
  <img src=https://github.com/ViniciusRubens/Shalow-Neural-Network/blob/main/images/Calculus.png alt="SHALOW NEURAL NETWORK" width="200">
<br>
</h1>

Moreover, it is important to note that this project is a Shalow Neural Network model for study and knowledge of how machine learning works for simple situations, without using mechanisms and frameworks, which would have a more significant efficiency, but which is not the goal in this work. This can be seen, by the uses of various functions of calculations such as Sigmoide, Cost Function, Forward Propagation and Backward Propagation.

Thanks, and enjoy.

</p>

<p align="center">
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License MIT">
  </a>
</p>

## Features
[//]: # (Add the features of your project here:)
The programming language used was Python 3 in Jupyter environment, using the libraries highlighted below whose documentation is in the links just by clicking on them. In the next topic you will have a description of how you can install the libraries and test the code.

- 📁 [Numpy](https://numpy.org/) — Python library used for the calculations of multidimensional matrices.
- 📁 [Matplotlib](https://matplotlib.org/3.3.3/contents.html) — Library used to check the tests.
- 📁 [Os](https://docs.python.org/3/library/os.html) — Library used to browse directories from our PC.
- 📁 [OpenCV](https://opencv.org/) — Library used to modify and load our images.

## Getting started

To use this project, we need to do some library installations. Let's see below how to do this step:

👉 To install the Numpy library, if we use the Windows Command Prompt we can run the command:

`pip install numpy`

If you want to install directly by Jupyter through Conda, we can execute the command:

`conda install numpy`

If you are having problems during installation, a good alternative is to check your version of pip and Python, when we run the command below in the Command Prompt both information are provided: 

`pip --version`

👉 To install the Matplotlib library, the process is similar. By Command Prompt we will do: 

`pip install matplotlib`

👉 By default the Os library is a package already installed together with the Python installation.

👉 Finally, the OpenCV library can be installed through the following command in the Command Prompt:

`pip install opencv-python`

⚠️ This project works with a database of images available free of charge on the [Kaggle](https://www.kaggle.com/) platform . In this project the volume of images was reduced due to the hardware limitations of the computer that performed the training.

## License

This project is licensed under the MIT License - see the [LICENSE](https://opensource.org/licenses/MIT) page for details.