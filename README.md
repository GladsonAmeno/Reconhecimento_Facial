# Facial Recognition
Este é um projeto simples de reconhecimento facial que utiliza o OpenCV para detectar rostos em imagens. Há duas versões disponíveis: uma que utiliza a webcam como entrada e outra que utiliza uma imagem estática.

## Versão com Webcam

## Pré-requisitos

- Python 3.x
- Biblioteca OpenCV (opencv-python) - pip install opencv-python

### Executando o código

1. Certifique-se de ter o arquivo XML do classificador frontal de rostos ("haarcascade_frontalface_default.xml") no mesmo diretório do script Python.

2. Execute o seguinte **reconhecimento-foto.py**
3. O programa abrirá uma janela mostrando a captura da webcam com retângulos desenhados ao redor das faces detectadas. Pressione a tecla 'q' para encerrar o programa.

## Versão com Imagem Estática

### Pré-requisitos
Certifique-se de ter instalado o OpenCV no seu ambiente Python. Você pode instalar o OpenCV utilizando o seguinte comando:
pip install opencv-python

### Executando o código
1. Certifique-se de ter o arquivo XML do classificador frontal de rostos ("haarcascade_frontalface_default.xml") no mesmo diretório do script Python.
2. Substitua o caminho da imagem pela imagem que você deseja utilizar:
3. Execute o seguinte **reconhecimento.py**

## Contribuição

Contribuições são bem-vindas! Se você deseja adicionar novas funcionalidades, corrigir bugs ou melhorar este projeto de alguma forma, fique à vontade para abrir um pull request.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).
