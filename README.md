# _Análise e modelagem de sistemas_
A partir da análise de requisitos funcionais e não funcionais para um sistema de automação de uma empresa pequena, foi feita a criação de diagrama de caso de uso e diagrama de classes utilizando a plataforma <a href=https://www.edrawmax.com/>EdrawMax.

## _Requisitos funcionais e não funcionais_

| Requisitos funcionais      | Requisitos não funcionais |
| ----------- | ----------- |
| [RF001] O sistema deve registrar a voz dos funcionários;     | [RNF001] O sistema funciona sem conexão com a internet.       |
| [RF002] O sistema deve identificar o comando de voz.   | [RNF002] O sistema possui cancelamento de ruído de voz.        |
| [RF003] O sistema deve permitir abrir portas por comando de voz do gerente do RH;     | [RNF003] O sistema utiliza uma inteligência artificial.      |
| [RF004] O sistema deve ligar as lâmpadas da empresa quando há funcionários;  | [RNF004] O sistema possui funciona em dispositivos móveis        |

## _Diagrama de caso de uso_

Esse foi o diagrama de caso de uso com os requisitos estabelecidos no projeto. 
![image](https://user-images.githubusercontent.com/83260908/229879557-341d087c-0cab-4bb5-9879-4f8278c69c21.png)

> O requisito funcional mostra o que o sistema solicitado deve fazer explicitando suas funções. Nesse caso, identificar voz é um dos principais requisitos para fazer o sistema funcionar. Para os RF003 e RF004, fica explícita a função e aplicabilidade do que o sistema deve fazer. Já os requisitos não funcionais especificam características gerais complementares aos requisitos funcionais. A usabilidade do sistema mesmo offline, a aplicação de cancelamento de ruído e o uso de IA para desenvolvimento da aplicação indicam as condições e como a aplicação será executada.

## _Diagrama de Classes_
A partir do diagrama de caso de uso, derivamos o diagrama de classes baseado nos seguintes requisitos: 

| Requisitos funcionais      | Requisitos não funcionais |
| ----------- | ----------- |
| [RF005] O sistema deve desligar o ar-condicionado quando não há funcionários na empresa.    | [RNF004] O sistema funciona apenas em horário comercial de 8h30 às 18h.       |
| [RF006] O sistema identifica a presença dos funcionários por reconhecimento de imagem.  | [RNF005] Os dados dos funcionários são armazenados em um banco de dados.       |
| [RF007] O sistema deve controlar a temperatura do ambiente.     | [RNF006] O sistema captura imagens e aciona a polícia em caso de invasões.     |

### _Diagrama de classes_:

![image](https://user-images.githubusercontent.com/83260908/229881535-caf7eda5-cd9c-4040-bf32-051621b1bb1b.png)
