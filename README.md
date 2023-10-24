
# Car Detection using Haar Cascade

![Video de funcionamento](videos/result.gif)


Este projeto é uma implementação simples de detecção de carros usando um classificador Haar Cascade em OpenCV. A detecção de objetos, neste caso, carros, é uma tarefa importante em visão computacional e pode ser usada em várias aplicações, como sistemas de segurança, rastreamento de tráfego, estacionamento automatizado e muito mais.

## Como Funciona

O projeto utiliza a biblioteca OpenCV para capturar e processar um vídeo de uma câmera ou arquivo de vídeo. A detecção de carros é realizada da seguinte maneira:

1. Capturamos cada quadro do vídeo.
2. Convertemos o quadro em escala de cinza.
3. Aplicamos um desfoque gaussiano para suavizar o quadro.
4. Realizamos uma dilatação para realçar as características.
5. Usamos um classificador Haar Cascade treinado para detectar carros no quadro.
6. Desenhamos retângulos em torno dos carros detectados.
7. Mantemos uma contagem de carros detectados e exibimos no canto da tela.

## Limitações

É importante observar que essa abordagem de detecção de carros usando Haar Cascade tem suas limitações:

- **Falsos Positivos**: Pode detectar objetos que não são carros, como placas de trânsito, árvores ou outros objetos com características semelhantes.

- **Eficiência**: Embora seja uma abordagem eficaz para detecção de objetos, é menos robusta do que soluções baseadas em deep learning, que podem lidar com uma variedade mais ampla de condições e cenários.

## Onde Pode Ser Usada

Essa detecção de carros usando Haar Cascade pode ser útil em cenários simples e limitados, como:

- **Sistemas de Vigilância**: Monitoramento de áreas restritas onde a detecção de carros específicos é necessária.

- **Contagem de Carros**: Contagem de carros em uma faixa específica de uma estrada ou em um estacionamento.

- **Detecção de Veículos em Estacionamentos**: Para detectar carros em um estacionamento e indicar vagas disponíveis.

## Onde Soluções com Deep Learning Ficariam Melhores

Para aplicações mais avançadas e desafiadoras, como a condução autônoma, rastreamento em tempo real em ambientes complexos, reconhecimento de veículos em diferentes ângulos e condições de iluminação, soluções baseadas em deep learning (por exemplo, redes neurais convolucionais) são mais adequadas. Essas soluções têm maior flexibilidade e desempenho em ambientes variados e podem lidar com uma variedade mais ampla de objetos.

Este projeto é um exemplo introdutório de detecção de carros e pode ser usado como ponto de partida para desenvolver soluções mais avançadas, dependendo dos requisitos específicos da sua aplicação.


