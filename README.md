# Classificação de Imagens com Redes Convolucionais

## Objetivo do Projeto
Este projeto tem como objetivo solucionar o problema de classificação de imagens utilizando Redes Neurais Convolucionais (CNN). As imagens são classificadas com base nos rótulos fornecidos no arquivo `labels.csv`. O projeto inclui etapas como preparação de dados, construção e treinamento de um modelo de CNN, além de uma análise detalhada dos resultados. Espera-se alcançar uma alta acurácia na classificação, identificando padrões relevantes nas imagens.

## Instruções para Execução do Código

### Pré-requisitos
Certifique-se de que os seguintes softwares e bibliotecas estão instalados no seu ambiente:
- **Python 3.8+**
- **TensorFlow**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **scikit-learn**

### Instalação de Dependências
As dependências necessárias estão listadas no arquivo `requirements.txt`. Para instalá-las, execute o seguinte comando:

```bash
pip install -r requirements.txt
```

### Estrutura do Projeto
A estrutura do projeto deve ser semelhante a esta:

```
.
├── cnn.ipynb         # Notebook contendo o código principal do projeto
├── labels.csv        # Arquivo CSV com os nomes dos arquivos de imagem e seus rótulos
├── images/           # Diretório contendo as imagens usadas no projeto
├── requirements.txt  # Arquivo de dependências
└── README.md         # Documentação do projeto
```

### Executando o Código

1. Certifique-se de que o diretório `images/` contém as imagens mencionadas no arquivo `labels.csv`.
2. Abra o arquivo `cnn.ipynb` em um ambiente como o Jupyter Notebook ou Google Colab.
3. Execute as células na ordem para:
   - Carregar os dados do `labels.csv`
   - Pré-processar as imagens
   - Treinar o modelo de CNN
   - Avaliar e visualizar os resultados

## Principais Conclusões e Considerações

### Resultados Obtidos
- O modelo apresentou uma boa capacidade de generalização para classificar corretamente as imagens, com métricas como F1-score indicando equilíbrio entre as classes.
- Foi possível identificar padrões importantes relacionados aos rótulos fornecidos.

### Limitações e Melhorias Futuras

#### Limitações Identificadas:
- Desbalanceamento do Dataset: Certos rótulos podem estar sub-representados, o que impacta no desempenho do modelo.
- Qualidade das Imagens: Algumas imagens apresentaram ruído ou baixa resolução, dificultando o aprendizado.

#### Melhorias Sugeridas:
- Aumentar o tamanho do dataset com mais imagens
- Aplicar técnicas de data augmentation para aumentar a robustez do modelo
- Explorar arquiteturas mais avançadas como ResNet ou EfficientNet

Este projeto reforçou a importância das CNNs na solução de problemas de classificação de imagens, destacando também os desafios associados a datasets reais.
