# UVT Model with RoBERTa and ResNetAE

Este repositório contém a implementação de um modelo de codificação automática multi-ramo usando transformadores, especificamente integrando RoBERTa e ResNetAE, para a análise de vídeos de ultrassom.

## Estrutura do Projeto

- `models/`: Contém as definições das classes de modelo, incluindo `UVT`, `Inception`, `Reduce` e funções auxiliares.
- `ResNetAE/`: Contém a implementação do ResNetAE.
- `train.py`: Script para treinamento do modelo.
- `data/`: Diretório onde os dados do conjunto de vídeos e arquivos CSV são armazenados.

Codigo baseado no UVIT de Reynald: https://arxiv.org/abs/2107.00977
