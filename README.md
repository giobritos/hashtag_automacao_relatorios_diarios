# Projeto de Automação de Envio de Relatórios

Este é um projeto de automação desenvolvido utilizando a biblioteca PyAutoGUI para Python. O objetivo deste projeto é automatizar o processo de geração e envio de relatórios para um destinatário pré-definido com base no projeto idealizado pelo Professor João Paulo Rodrigues de Lira da Hashtag Treinamentos.

## Instalação das Bibliotecas

Antes de executar o código, é necessário garantir que as bibliotecas `pyautogui` e `pyperclip` estejam instaladas no Python. Para fazer isso, você pode utilizar os seguintes comandos:

```bash
! pip install pyautogui
! pip install pyperclip
```

## Descrição do Funcionamento

1. O projeto utiliza a biblioteca `pyautogui` para automatizar tarefas de interação com a interface gráfica do computador, como clicar em botões e preencher campos.

2. O programa inicia com a importação das bibliotecas necessárias e a definição de um tempo de pausa para aguardar o carregamento de elementos na tela.

3. O usuário é apresentado com uma mensagem de alerta para iniciar o processo. O programa abrirá uma nova guia no navegador para acessar o Google Drive.

4. O link do Google Drive é copiado para a área de transferência e colado na barra de endereços do navegador. O programa pressiona "Enter" para acessar o Google Drive.

5. Após aguardar o carregamento da página, o programa realiza cliques em botões específicos para navegar até a pasta desejada e fazer o download da planilha de vendas.

6. Em seguida, o programa utiliza a biblioteca `pandas` para ler a planilha de vendas baixada e calcula o faturamento total e a quantidade de produtos vendidos.

7. Por fim, o programa abre uma nova guia no Gmail, preenche os campos do e-mail (destinatário, assunto e corpo) com os valores calculados anteriormente e envia o e-mail com os relatórios.

## Como Usar

1. Certifique-se de ter instalado as bibliotecas `pyautogui` e `pyperclip`.

2. Copie o código Python para um ambiente onde você pode executá-lo, como o Jupyter Notebook.

3. Execute o código.

4. O programa iniciará o processo de automação, navegando até o Google Drive, fazendo o download da planilha de vendas, lendo os dados e enviando o e-mail com os relatórios.

**Observação:** É importante estar ciente de que a automação de interações com interfaces gráficas pode variar dependendo do sistema operacional e das resoluções de tela. Algumas coordenadas e tempos de pausa podem precisar ser ajustados para funcionar corretamente em diferentes ambientes.

## Limitações

- O programa foi desenvolvido com base em uma interface gráfica específica, e pode não funcionar corretamente em outras resoluções de tela ou interfaces diferentes.

- A automação pode ser sensível a mudanças no layout da página do Google Drive ou do Gmail, o que pode exigir ajustes no código.

- O programa não inclui tratamento de erros para situações em que a página não carrega corretamente ou ocorrem problemas de conexão.

## Contribuição

Contribuições são bem-vindas! Se você encontrar problemas ou tiver sugestões para melhorias, sinta-se à vontade para abrir uma issue neste repositório. Caso queira contribuir com código, por favor, abra um pull request para revisão.

## Agradecimentos

Agradecemos ao Professor João Paulo Rodrigues de Lira da Hashtag Treinamentos pelo projeto idealizado e à comunidade de código aberto por tornar disponíveis as bibliotecas utilizadas neste projeto. 

**Desenvolvido com :heart: e Python.**
