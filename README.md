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
 ```
Gravador de Tela

## DescriÃ§Ã£o

Esta aplicaÃ§Ã£o web permite gravar a tela do usuÃ¡rio juntamente com o Ã¡udio do sistema e do microfone. As gravaÃ§Ãµes podem ser salvas no `localStorage` do navegador, visualizadas e baixadas posteriormente.

## Funcionalidades

- Iniciar e parar gravaÃ§Ã£o da tela com Ã¡udio.
- Salvar gravaÃ§Ãµes no `IndexedDB`.
- Carregar e visualizar gravaÃ§Ãµes salvas.
- Baixar gravaÃ§Ãµes salvas.
- Excluir gravaÃ§Ãµes salvas.
- Exibir o tamanho total das gravaÃ§Ãµes armazenadas.
- Visualizar um grÃ¡fico de pizza com o espaÃ§o ocupado e livre.

## Tecnologias Utilizadas

- **HTML5**
- **JavaScript**
- **Bootstrap 5**
- **Chart.js**
- **Font Awesome**

## Como Usar

1. Abra o arquivo `screenrec.html` em um navegador compatÃ­vel.
2. Clique no botÃ£o "Iniciar GravaÃ§Ã£o" para comeÃ§ar a gravar a tela.
3. Clique no botÃ£o "Parar GravaÃ§Ã£o" para finalizar a gravaÃ§Ã£o.
4. A gravaÃ§Ã£o serÃ¡ salva automaticamente no `localStorage` e aparecerÃ¡ na tabela de gravaÃ§Ãµes salvas.
5. Utilize os botÃµes na tabela para visualizar, baixar ou excluir as gravaÃ§Ãµes.

## Estrutura do Projeto

- `screenrec.html`: Arquivo principal da aplicaÃ§Ã£o contendo o HTML, CSS e JavaScript.
- `screenrec/README.md`: Arquivo de documentaÃ§Ã£o da aplicaÃ§Ã£o.

## ObservaÃ§Ãµes

- Certifique-se de permitir o acesso Ã  tela e ao microfone quando solicitado pelo navegador.
- As gravaÃ§Ãµes sÃ£o armazenadas no `localStorage` do navegador, portanto, serÃ£o perdidas se o cache do navegador for limpo.

## LicenÃ§a

Este projeto estÃ¡ licenciado sob a [MIT License](LICENSE).