# JOGO DO GENIO
👨‍🏫PROJETO CRIADO PARA O CURSO DE JAVA DO CURSO EM VIDEO.

<img src="./IMAGENS/FOTO_1.png" align="center" width="500"> <br>
<img src="./IMAGENS/FOTO_2.png" align="center" width="500"> <br>

## DESCRIÇÃO:
- O aplicativo "Jogo do Gênio" é uma pequena aplicação gráfica desenvolvida em Java utilizando Swing. Ele simula um jogo simples onde o usuário tenta adivinhar um número aleatório escolhido pelo programa entre 1 e 10.

- Este aplicativo exemplifica o uso básico de componentes gráficos Swing para criar uma pequena aplicação interativa em Java, onde o usuário pode interagir através da interface gráfica para tentar adivinhar um número escolhido aleatoriamente pelo programa.

## FUNCIONALIDADES:
1. **Interface Gráfica (GUI)**:
   - A interface gráfica é construída utilizando componentes Swing do Java, como `JFrame`, `JLabel`, `JSpinner`, e `JButton`.
   - Imagens são utilizadas para decorar a interface, como as imagens do gênio e da mensagem.

2. **Inicialização e Mensagem Inicial**:
   - Quando o programa é iniciado (`main` method), uma instância da classe `JanelaGenio` é criada e tornada visível.
   - A mensagem inicial é exibida no `JLabel lblFrase` indicando que o gênio está pensando em um número entre 1 e 10.

3. **Adivinhação do Número**:
   - O usuário seleciona um número utilizando o `JSpinner txtVal` e clica no botão "ADVINHAR" (`btnPalpite`).
   - Um número aleatório é gerado pelo programa (`n = 1 + Math.random() * (11-1)`).
   - O valor selecionado pelo usuário (`num`) é comparado com o número aleatório gerado (`valor`).
   - Se o número selecionado pelo usuário corresponder ao número aleatório, a mensagem "ACERTOU!" é exibida.
   - Caso contrário, a mensagem informa qual era o número que o gênio tinha em mente.

4. **Manipulação de Texto HTML em JLabel**:
   - Para formatar e exibir mensagens multi-linha, o texto na `JLabel lblFrase` é configurado usando HTML (`<html>` e `</html>`).
   - Isso permite exibir mensagens formatadas com quebras de linha e estilização de texto.

5. **Encerramento da Aplicação**:
   - A aplicação pode ser encerrada clicando no botão de fechar da janela ou fechando a janela pelo sistema operacional.

## EXECUTANDO O PROJETO:
1. **Certifique-se de que o projeto esteja compilado:**
   Antes de executar o projeto, você deve garantir que ele foi compilado corretamente. Navegue até o diretório `./CODIGO`, e use o seguinte comando para compilar:

   ```bash
   mvn clean install
   ```

2. **Executar o projeto:**
   Para executar a aplicação Swing com o Maven, usando a classe principal definida no seu `pom.xml`, use o comando:

   ```bash
   mvn exec:java
   ```

## TECNOLOGIAS USADAS:
- [LINGUAGEM JAVA:](https://github.com/VILHALVA/CURSO-DE-JAVA) A linguagem de programação Java é amplamente utilizada para o desenvolvimento de aplicativos devido à sua portabilidade, segurança e robustez. Ela é uma escolha popular para desenvolver aplicativos desktop, web e móveis.

- [JAVA SWING:](https://github.com/VILHALVA/CURSO-DE-JAVA-SWING) Java Swing é um conjunto de bibliotecas gráficas para a criação de interfaces de usuário (UI) em Java. Ele fornece componentes gráficos avançados, como botões, caixas de texto, tabelas e muito mais, permitindo que os desenvolvedores criem aplicativos desktop com uma interface de usuário rica e interativa.

- [NETBEANS IDE](https://netbeans.apache.org/download/index.html) O NetBeans IDE é um ambiente de desenvolvimento integrado gratuito e de código aberto para o desenvolvimento de aplicativos Java, bem como para várias outras linguagens de programação, como PHP, C/C++, e HTML5. Ele oferece uma série de recursos poderosos, como edição de código avançada, depuração, controle de versão e integração com servidores de aplicativos, facilitando o desenvolvimento de software em Java e outras plataformas.

## CREDITOS:
- [PROJETO CRIADO PARA O CURSO DE JAVA](https://github.com/VILHALVA/CURSO-DE-JAVA)
- [PROJETO FEITO PELO VILHALVA](https://github.com/VILHALVA)


