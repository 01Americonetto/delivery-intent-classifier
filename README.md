# Delivery Intent Classifier

Sistema de roteamento e triagem automatizada de chamados de suporte utilizando **Zero-Shot Classification** para otimização de fluxo operacional em logistica e delivery.

## Arquitetura do Sistema

1. **Modelo de Linguagem (NLI):** Utilizacao do modelo multilíngue `MoritzLaurer/mDeBERTa-v3-base-mnli-xnli` ajustado para Inferência de Linguagem Natural.
2. **Abordagem Zero-Shot:** Classificação de intenções de negócio sem necessidade de um dataset prévio de treinamento supervisionado, utilizando templates de hipótese dinâmicos.
3. **Infraestrutura de Motor:** Processamento de tensores e inferência em lote gerenciados via **PyTorch** e **Hugging Face Transformers**.

## Categorias Operacionais Monitoradas

- `atraso na entrega`
- `item faltando`
- `problema de pagamento`
- `cancelamento`
- `duvida geral`

## Stack Tecnológica

- **Python 3**
- **PyTorch**
- **Hugging Face (`transformers`)**

## Como Executar

Clique no botão abaixo para abrir e executar o pipeline diretamente no Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1yJBxwZTaclx_U-uUOIEbgcPTupbapzzS?usp=sharing)
