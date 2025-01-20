# YOLOv5 Object Detection in Google Colab

Este repositório fornece uma implementação simples de detecção de objetos utilizando o modelo YOLOv5 no Google Colab. O código permite que você faça upload de uma imagem e visualize as caixas delimitadoras e os rótulos dos objetos detectados.

## Como Usar

1. **Clonar o Repositório (opcional)**:
   
   Se você deseja clonar este repositório para seu ambiente local, pode usar o comando:

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
   
## Acessar o Google Colab:

Você pode executar este código diretamente no Google Colab. Para isso, siga as etapas abaixo:

## Instalar Dependências:

No início do notebook do Google Colab, execute o seguinte comando para instalar a biblioteca yolov5 e suas dependências:

  ```bash
  !pip install yolov5
  ```

## Carregar o Modelo e Carregar a Imagem:

O código carrega automaticamente o modelo YOLOv5 pré-treinado (yolov5s) e permite que você faça o upload de uma imagem para realizar a detecção.

## Exibir os Resultados:

Após o upload da imagem, o código realiza a detecção de objetos e exibe a imagem com as caixas delimitadoras e os rótulos dos objetos detectados.

## Dependências
Este projeto usa as seguintes dependências:

- yolov5: Biblioteca para carregar e usar o modelo YOLOv5.
- torch: Biblioteca para treinamento e inferência de modelos de deep learning.
- matplotlib: Para exibir as imagens e resultados.
- PIL: Para manipulação de imagens.
- google.colab: Para carregar a imagem diretamente no Google Colab.

Você pode instalar as dependências usando:

  ```bash
  pip install yolov5 torch matplotlib Pillow google-colab
  ```

## Como Funciona

- Carregamento do Modelo: O modelo YOLOv5 pré-treinado (yolov5s) é carregado utilizando o torch.hub.load a partir do repositório oficial do YOLOv5.

- Upload de Imagem: O código permite que você faça upload de uma imagem diretamente no Google Colab.

- Detecção de Objetos: Após o upload, o modelo YOLOv5 realiza a detecção de objetos na imagem e desenha caixas delimitadoras e rótulos sobre os objetos detectados.

- Exibição dos Resultados: O código exibe a imagem com as caixas e rótulos dos objetos detectados.

## Contribuição
Se você tiver sugestões ou melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença
Este projeto está licenciado sob a Licença MIT - consulte o arquivo LICENSE para mais detalhes.
