# Detecção de Tumores Cerebrais com CNN

## Descrição do Projeto
Este projeto utiliza Redes Neurais Convolucionais (CNN) para detectar a presença de tumores cerebrais em imagens de ressonância magnética (MRI). O objetivo é auxiliar profissionais de saúde a diagnosticar tumores de forma mais rápida e precisa, utilizando a tecnologia de aprendizado de máquina.

## Funcionalidades
Detecção Automatizada: Identifica automaticamente a presença de tumores em imagens de MRI.
Alto Desempenho: Utiliza a arquitetura MobileNetV2 para garantir um processamento eficiente e resultados precisos.
Fácil de Usar: Interface simples para carregar imagens e obter diagnósticos.

## Tecnologias Utilizadas
- TensorFlow
- Keras
- Python
- NumPy
- Matplotlib
  
## Requisitos
- Python 3.x
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib

## Instalação e Configuração
### Obs.: Caso for rodar novamente os testes, lembre-se de atualizar os paths para os datasets

Clone o Repositório:
git clone https://github.com/Ideraldo/Analise-de-Tumores-Cerebrais.git

OU

Baixe o arquivo .ipynb para executa-lo no google colab

Instale as Dependências (caso for rodar localmente):
pip install tensorflow keras numpy matplotlib

## Arquivos utilizados para teste e treino
- Dados de treino: https://drive.google.com/drive/folders/1maO0Lb4Sa2a9dNH6INYKdgAO-X1tYApU?usp=sharing 
- Dados de teste: https://drive.google.com/drive/folders/1rjAhuk8adObaYdRtHouIWE9GTKTe-3XV?usp=sharing

Imagens para o teste final:
- Com tumor: https://drive.google.com/drive/folders/121VjmZi54Dr3_dXT0OZbmpC7K_pbOEmV?usp=sharing
- Sem tumor: https://drive.google.com/drive/folders/1Bl3aY-tED1RX1OONiLstHkszaGkGtp8g?usp=sharing

Dataset base:
- https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset/

## Uso
Para usar o modelo de detecção de tumores, siga estes passos:

- Carregue a imagem de ressonância magnética cerebral usando a função de carregamento disponível no script (ultima parte).
- Execute o modelo para fazer a predição.
- O modelo indicará se a imagem apresenta indícios de tumor cerebral.

## Video de apresentação do projeto
- https://youtu.be/gl9iJfCAKXo

