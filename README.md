# Sistema de Gerenciamento de Biblioteca 📚

Este projeto é um sistema de gerenciamento de biblioteca desenvolvido com **HTML**, **CSS** e **Bootstrap**. O objetivo é automatizar processos como empréstimo, devolução, reserva e consulta de livros, além de gerenciar o catálogo da biblioteca e as informações dos usuários.

---

## Integrantes 👥

- **Evelyn Duarte** - [Github](!)
- **Expedita Nogueira** - [Github](https://github.com/ExpeditaNogueira)
- **Jonnattan Silva** - [Github](https://github.com/JonnattanSS)
- **Lucas Goebel** - [Github](https://github.com/lgoebel)
- **Luís Lima** - [Github](https://github.com/LGSLima)
- **Matheus Marzagão** - [Github](https://github.com/MatheusShuctzo)

---

## Funcionalidades Principais 🛠️

- **Cadastro de Livros**: Permite cadastrar novos livros com informações como título, autor, ISBN, editora, ano de publicação e número de exemplares.
- **Cadastro de Usuários**: Permite cadastrar novos usuários com informações como nome, endereço, telefone e e-mail.
- **Empréstimo de Livros**: Registra o empréstimo de um livro para um usuário, informando a data de empréstimo e a data de devolução prevista.
- **Devolução de Livros**: Registra a devolução de um livro, informando a data de devolução real.
- **Reserva de Livros**: Permite que um usuário reserve um livro que não está disponível no momento.
- **Consulta de Livros**: Permite pesquisar livros no catálogo por título, autor, ISBN ou palavra-chave.
- **Relatórios**: Gera relatórios sobre os livros mais emprestados, usuários com mais empréstimos e livros em atraso.

---

## Interfaces 🖥️

O sistema possui uma interface web com as seguintes telas:

- Tela de Login
- Tela de Cadastro de Livros
- Tela de Cadastro de Usuários
- Tela de Empréstimo de Livros
- Tela de Devolução de Livros
- Tela de Reserva de Livros
- Tela de Consulta de Livros

---

## Regras de Negócio ⚙️

- Um usuário pode ter no máximo **5 livros emprestados** ao mesmo tempo.
- O prazo de empréstimo de um livro é de **14 dias**.
- Um livro só pode ser reservado por **um usuário por vez**.

---

## Casos de Teste 🧪

### 1. **Cadastro de Livros**
   - Testar com dados válidos (título, autor, ISBN, editora, ano de publicação, número de exemplares).
   - Testar com dados inválidos (ISBN incorreto, ano de publicação inválido).
   - Testar com campos obrigatórios em branco.

### 2. **Empréstimo de Livros**
   - Testar para usuários sem pendências (menos de 5 livros emprestados).
   - Testar para usuários com pendências (5 livros emprestados).
   - Testar para usuários com atrasos na devolução.

### 3. **Reserva de Livros**
   - Testar reserva de livro disponível.
   - Testar reserva de livro já reservado por outro usuário.
   - Testar reserva de livro emprestado.

### 4. **Consulta de Livros**
   - Testar consulta por título.
   - Testar consulta por autor.
   - Testar consulta por ISBN.

---

## Tecnologias Utilizadas 💻

- **HTML**: Estrutura das páginas.
- **CSS**: Estilização das interfaces.
- **Bootstrap**: Framework para design responsivo e componentes pré-estilizados.
- **JavaScript (Bootstrap)**: Utilizado apenas para funcionalidades do Bootstrap, como modais e interações.

---

## Como Executar o Projeto 🚀

1. Clone o repositório:

```
   git clone https://github.com/seu-usuario/sistema-biblioteca.git
```

2. Navegue até a pasta do projeto:

```
cd sistema-biblioteca
```

3. Abra o arquivo index.html no seu navegador.

---

## Contribuição 🤝

Contribuições são bem-vindas! Siga os passos abaixo:

1. Faça um fork do projeto.

2. Crie uma branch para sua feature (git checkout -b feature/nova-feature).

3. Commit suas mudanças (git commit -m 'Adiciona nova feature').

4. Push para a branch (git push origin feature/nova-feature).

5. Abra um Pull Request.

---

# Licença 📄

Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.