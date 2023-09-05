# Orientação a Objetos e UML: Diagramação de Classes do iPhone

![terraform](https://img.shields.io/badge/-UML-white?style=for-the-badge&logo=UML&color=FABD14&logoColor=white)

Este é um diagrama UML que representa a estrutura de classes e interfaces para um sistema que inclui a modelagem do iPhone, um dispositivo que incorpora funcionalidades de um reprodutor de música, um telefone e um navegador de internet. Este diagrama foi criado como parte do desafio de projeto do **Santander Bootcamp 2023 - Fullstack Java+Angular** na DIO.me.

![iphone](https://raw.githubusercontent.com/SilvioCavalcantiBonfim/Diagramacao-de-Classes-do-iPhone/0.1.0/iphone.png)


## Descrição das Interfaces e Classes

### Reprodutor Musical (ReprodutorMusical)

A interface `Reprodutor Musical` é responsável por implementar a funcionalidade de reprodução de arquivos de áudio. Ela possui métodos como `tocar()`, `pausar()`, e `selecionarMusica()`. A classe `Musica` armazena informações sobre as músicas.

### Aparelho Telefônico (AparelhoTelefonico)

A interface `Aparelho Telefônico` é responsável por implementar a funcionalidade de um telefone. Ela possui métodos como `ligar()`, `atender()`, e `iniciarCorreioVoz()`. A classe `Contato` armazena informações de contatos.

### Navegador de Internet (NavegadorInternet)

A interface `Navegador de Internet` é responsável por implementar a funcionalidade de um navegador web. Ela possui métodos como `exibirPagina()`, `adicionarNovaAba()`, e `atualizarPagina()`.

## Entidades

Existem algumas entidades representadas no diagrama, como `IPhone`, `FireFox`, `Chrome`, `Nokia 3310`, `Motorola Razr V3`, `Walkman` e `Discman`, que representam diferentes dispositivos ou aplicativos que podem usar as interfaces e classes mencionadas acima.

## Como Visualizar o Diagrama

Para visualizar o diagrama UML, você pode copiar o código PlantUML e colá-lo em um editor compatível com PlantUML ou usar uma ferramenta online de renderização de PlantUML.

Exemplo de uso com a ferramenta PlantUML Online:
1. Acesse o site https://www.planttext.com/.
2. Cole o código PlantUML na área de texto.
3. Clique no botão "Refresh" para gerar o diagrama.

Lembre-se de que este é apenas um diagrama de classe de exemplo e pode ser personalizado e estendido para atender às necessidades específicas do seu projeto.
