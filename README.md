# screenrec

```plaintext
  /$$$$$$                                                    /$$$$$$$                     
 /$$__  $$                                                  | $$__  $$                    
| $$  \__/  /$$$$$$$  /$$$$$$   /$$$$$$   /$$$$$$  /$$$$$$$ | $$  \ $$  /$$$$$$   /$$$$$$$
|  $$$$$$  /$$_____/ /$$__  $$ /$$__  $$ /$$__  $$| $$__  $$| $$$$$$$/ /$$__  $$ /$$_____/
 \____  $$| $$      | $$  \__/| $$$$$$$$| $$$$$$$$| $$  \ $$| $$__  $$| $$$$$$$$| $$      
 /$$  \ $$| $$      | $$      | $$_____/| $$_____/| $$  | $$| $$  \ $$| $$_____/| $$      
|  $$$$$$/|  $$$$$$$| $$      |  $$$$$$$|  $$$$$$$| $$  | $$| $$  | $$|  $$$$$$$|  $$$$$$$
 \______/  \_______/|__/       \_______/ \_______/|__/  |__/|__/  |__/ \_______/ \_______/
Gravador de Tela

## Descrição

Esta aplicação web permite gravar a tela do usuário juntamente com o áudio do sistema e do microfone. As gravações podem ser salvas no `localStorage` do navegador, visualizadas e baixadas posteriormente.

## Funcionalidades

- Iniciar e parar gravação da tela com áudio.
- Salvar gravações no `localStorage`.
- Carregar e visualizar gravações salvas.
- Baixar gravações salvas.
- Excluir gravações salvas.
- Exibir o tamanho total das gravações armazenadas.

## Tecnologias Utilizadas

- HTML5
- JavaScript
- Bootstrap 5

## Como Usar

1. Abra o arquivo `screenrec.html` em um navegador compatível.
2. Clique no botão "Iniciar Gravação" para começar a gravar a tela.
3. Clique no botão "Parar Gravação" para finalizar a gravação.
4. A gravação será salva automaticamente no `localStorage` e aparecerá na tabela de gravações salvas.
5. Utilize os botões na tabela para visualizar, baixar ou excluir as gravações.

## Estrutura do Projeto

- `screenrec.html`: Arquivo principal da aplicação contendo o HTML, CSS e JavaScript.
- `screenrec/README.md`: Arquivo de documentação da aplicação.

## Observações

- Certifique-se de permitir o acesso à tela e ao microfone quando solicitado pelo navegador.
- As gravações são armazenadas no `localStorage` do navegador, portanto, serão perdidas se o cache do navegador for limpo.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).