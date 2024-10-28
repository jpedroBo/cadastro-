# Sistema de Cadastro de Usuários

Este projeto é um sistema de cadastro de usuários com interface gráfica desenvolvida em Python usando a biblioteca Tkinter. Ele permite que o usuário insira um nome e um e-mail, com validação do formato do e-mail. Caso as entradas sejam válidas, o cadastro é confirmado.

## Funcionalidades

- Interface gráfica intuitiva para cadastro de usuários.
- Validação de e-mail (formato correto: `usuario@dominio.com`).
- Mensagens de erro para entradas inválidas.
- Foco automático nos campos e cadastro ao pressionar "Enter".
- Limpeza automática dos campos após o cadastro.

## Tecnologias Utilizadas

- **Python 3.x**
- **Tkinter**: Biblioteca nativa do Python para a criação de interfaces gráficas.
- **re (Expressões Regulares)**: Utilizada para a validação do formato do e-mail.

## Como Executar o Projeto

1. Certifique-se de que o Python 3.x está instalado em seu sistema.
2. Clone o repositório ou baixe o código.
    ```bash
    git clone https://github.com/seuusuario/sistema-cadastro-usuarios.git
    ```
3. Navegue até a pasta do projeto:
    ```bash
    cd sistema-cadastro-usuarios
    ```
4. Execute o arquivo Python:
    ```bash
    python cadastro.py
    ```

## Estrutura do Projeto

- **cadastro.py**: Contém a lógica do sistema de cadastro e a interface gráfica com Tkinter.

## Funcionalidade do Código

1. O usuário insere o nome e o e-mail.
2. Ao pressionar **Enter** ou clicar no botão **Cadastrar**, o sistema valida se ambos os campos foram preenchidos corretamente:
   - O campo **nome** não pode estar vazio.
   - O **e-mail** deve seguir o formato correto de endereço de e-mail.
3. Se as validações forem atendidas, o sistema exibe uma mensagem confirmando o cadastro e limpa os campos para um novo cadastro.
4. Caso algum campo esteja incorreto ou vazio, uma mensagem de alerta é exibida.

## Exemplo de Uso

- Ao inserir um nome como `João Silva` e um e-mail válido como `joao.silva@gmail.com`, o sistema exibirá a mensagem:
    ```
    Usuário João Silva cadastrado com sucesso!
    ```
- Se o nome não for preenchido ou o e-mail estiver incorreto, o sistema alertará para corrigir os erros.

## Autor
