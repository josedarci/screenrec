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

## Descri��o

Esta aplica��o web permite gravar a tela do usu�rio juntamente com o �udio do sistema e do microfone. As grava��es podem ser salvas no `localStorage` do navegador, visualizadas e baixadas posteriormente.

## Funcionalidades

- Iniciar e parar grava��o da tela com �udio.
- Salvar grava��es no `localStorage`.
- Carregar e visualizar grava��es salvas.
- Baixar grava��es salvas.
- Excluir grava��es salvas.
- Exibir o tamanho total das grava��es armazenadas.

## Tecnologias Utilizadas

- HTML5
- JavaScript
- Bootstrap 5

## Como Usar

1. Abra o arquivo `screenrec.html` em um navegador compat�vel.
2. Clique no bot�o "Iniciar Grava��o" para come�ar a gravar a tela.
3. Clique no bot�o "Parar Grava��o" para finalizar a grava��o.
4. A grava��o ser� salva automaticamente no `localStorage` e aparecer� na tabela de grava��es salvas.
5. Utilize os bot�es na tabela para visualizar, baixar ou excluir as grava��es.

## Estrutura do Projeto

- `screenrec.html`: Arquivo principal da aplica��o contendo o HTML, CSS e JavaScript.
- `screenrec/README.md`: Arquivo de documenta��o da aplica��o.

## Observa��es

- Certifique-se de permitir o acesso � tela e ao microfone quando solicitado pelo navegador.
- As grava��es s�o armazenadas no `localStorage` do navegador, portanto, ser�o perdidas se o cache do navegador for limpo.

## Licen�a

Este projeto est� licenciado sob a [MIT License](LICENSE).