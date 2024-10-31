# **APP AGENDA**

> Um aplicativo Android simples para simular uma agenda.

## 📱 Descrição

O **APP AGENDA** utiliza banco de dados, ListView, um layout de menu, para simular uma agenda. Você pode cadastrar e pesquisar itens em uma lista.

## 🔧 Funcionalidades

- [x] Entrada de dados (nome, cpf e telefone)
- [x] ListView para mostrar os itens salvas em uma lista
- [x] Exibição do resultado por pesquisa 
- [x] Interface simples e intuitiva
- [x] Criar as opções para atualizar e excluir itens (planejado para futuras versões)

## 🚀 Tecnologias Utilizadas

- [x] **Android Studio** (Koala | 2024.1.2)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [X] **Layout menu** para um menu superior e funcional
- [X] **ListView** para criar um componente de lista
- [x] **TextView** e **EditText** para entrada e exibição de dados
- [x] **Button**   para executar o app.

## 🛠️ Como Rodar o Projeto

Siga os passos abaixo para rodar o projeto localmente:

1. Clone este repositório:

    ```bash
    git clone https://github.com/Andriele15/APP-AGENDA.git

    ```

2. Abra o projeto no Android Studio.
3. Compile e execute o projeto em um emulador ou dispositivo físico.

## 📂 Estrutura do Projeto

```bash
├── app
│ ├── src
│ │ ├── main
│ │ │ ├── java/br/ulbra/appagenda
│ │ │ │ ├── MainActivity.java # Atividade principal para atualizar o cadastro
│ │ │ │ ├── Conexao.java # Atividade para o banco de dados
│ │ │ │ ├── ListarPessoasActivity.java # Atividade para a manipulação dos cadastros
│ │ │ │ ├── Pessoa.java # Atividade para método getters e setters
│ │ │ │ ├── PessoaDAO.java # Atividade CRUD
│ │ │ ├── res
│ │ │ │ ├── layout
│ │ │ │ │ ├── activity_main.xml # Layout da tela principal
│ │ │ │ │ ├── activity_listar_pessoa_activity.xml # Layout da ListView
│ │ │ │ └── menu
│ │ │ │ │ ├── menu_principal.xml # Layout do menu
│ │ │ │ │ ├── menu_contexto.xml # Layout do menu para excluir e atualizar
│ │ │ │ └── values
│ │ │ │ ├── strings.xml # Strings usadas no app
│ │ │ │ ├── colors.xml # Cores definidas no projeto
│ └── build.gradle # Configuração do Gradle
└── README.md # Este arquivo
```

## 🎨 Design e Prototipagem
 
A interface do app foi criada usando **ConstraintLayout** para manter a responsividade em diferentes tamanhos de tela.
 
O design é minimalista e fácil de usar, com foco na simplicidade.
 
 ## 🖥️ Telas do Aplicativo

1. **Tela Principal**
 
Na tela principal, o usuário poderá clicar e tanto no icone de mais ou na lupa para efetuar alguma ação, o icones ficam localizados no menu superior. Logo abaixo do menu,
fica uma ListView que exibirá os cadastros feitos pelo usuário.
 
![telaprincipal](https://github.com/user-attachments/assets/3b7358d4-03ce-4ab8-92f3-e55c23a994cc)

2. **Tela de cadastro**
 
Na tela de cadastro, o usuário poderá inserir informações como, nome, cpf e telefone nos EditText que estão na tela, e poderão efetuar o cadastro clicando no botão.
Para voltar para a tela principal, basta fazer a ação de retorno do seu celular ou simulador.

![cad](https://github.com/user-attachments/assets/30e939cc-086a-4a45-a92f-02b90ac07078)

2. **Tela de pesquisa**
 
Na tela de pesquisa, quando o usuário clicar na lupa aparecerá esse menu de pesquisa, que se você pesquisar pelo o nome irá ser devolvido só os semelhantes no ListView. 

![pesquisando](https://github.com/user-attachments/assets/08e6a959-b8ac-4cb2-9648-a39e30b40eca)
 
## 👨‍💻 Desenvolvedores –

**Andriele Pacheco** - Desenvolvedor - [GitHub](https://github.com/Andriele15)
 
 ## 📄 Licença

Este projeto está licenciado sob os termos da licença MIT. 
Para mais
detalhes, veja o arquivo [LICENSE](LICENSE).
