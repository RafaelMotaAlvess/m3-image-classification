# Projeto: Classificação de Imagens

## Informações Gerais

- **Alunos:** Rafael Mota Alves, Daniel Sansão Araldi e Kauan Adami
- **Professor:** Felipe Viel
- **Disciplina:** Processamento de Imagens

## Descrição

Este projeto tem como objetivo desenvolver um modelo de classificação binária de imagens utilizando redes neurais convolucionais (CNNs). O modelo foi treinado para distinguir entre duas categorias: **Positive** e **Negative**, a partir de um dataset com aproximadamente 40.000 imagens.

## Como Executar

⚠️ Importante:
Devido às limitações de memória RAM do Google Colab, o código não foi executado na plataforma Colab, pois não era possível processar o dataset completo (com 40.000 imagens). Por isso, foi utilizada uma instância local do Jupyter Notebook, onde o código pôde ser executado sem restrições.

1. **Baixe o dataset:** <a href="https://data.mendeley.com/datasets/5y9wdsg2zt/2">Concrete Crack Images for Classification</a>.
2. **Extraia do dataset e substitua as pastas `Positive` e `Negative`** no caminho:

```
src/dataset/
├── Positive/
└── Negative/
```

> Certifique-se de manter exatamente essa estrutura de pastas para que o código funcione corretamente.

3. Execute o notebook `main.ipynb`
