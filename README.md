#### The versions of the README.md in english and spanish are right after, respectively.

#### Las versiones del README.md en inglés y español están justo después, respectivamente.

---

#### Versão em Português do Brasil.

# Sistema de Gerenciamento de Biblioteca 📚

Este projeto é uma atividade proposta durante as aulas do curso de Informática para Internet do SENAI Pará de Minas CFP Dr. Celso Charurí e foi desenvolvido com o propósito de iniciar e desenvolver o conhecimento sobre **casos de teste**. A atividade propõe a criação de um sistema de gerenciamento de biblioteca desenvolvido com **HTML**, **CSS** e **Bootstrap**. O objetivo é automatizar processos como empréstimo, devolução, reserva e consulta de livros, além de gerenciar o catálogo da biblioteca e as informações dos usuários.

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

2. Crie uma branch para sua feature:

```
   git checkout -b feature/nova-feature
```

3. Commit suas mudanças:

```
   git commit -m 'Adiciona nova feature'
```

4. Push para a branch:

```
   git push origin feature/nova-feature
```

6. Abra um Pull Request.

---

# Licença 📄

Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

---

#### English Version.

# Library Management System 📚

This project is an activity proposed during the classes of the Internet Informatics course at SENAI Pará de Minas CFP Dr. Celso Charurí and was developed with the purpose of initiating and developing knowledge about **test cases**. The activity proposes the creation of a library management system developed with **HTML**, **CSS**, and **Bootstrap**. The goal is to automate processes such as borrowing, returning, reserving, and querying books, as well as managing the library catalog and user information.

---

## Team Members 👥

- **Evelyn Duarte** - [Github](!)
- **Expedita Nogueira** - [Github](https://github.com/ExpeditaNogueira)
- **Jonnattan Silva** - [Github](https://github.com/JonnattanSS)
- **Lucas Goebel** - [Github](https://github.com/lgoebel)
- **Luís Lima** - [Github](https://github.com/LGSLima)
- **Matheus Marzagão** - [Github](https://github.com/MatheusShuctzo)

---

## Main Features 🛠️

- **Book Registration**: Allows registering new books with information such as title, author, ISBN, publisher, year of publication, and number of copies.
- **User Registration**: Allows registering new users with information such as name, address, phone number, and email.
- **Book Borrowing**: Records the borrowing of a book by a user, including the borrowing date and the due date.
- **Book Return**: Records the return of a book, including the actual return date.
- **Book Reservation**: Allows a user to reserve a book that is currently unavailable.
- **Book Query**: Allows searching for books in the catalog by title, author, ISBN, or keyword.
- **Reports**: Generates reports on the most borrowed books, users with the most borrowings, and overdue books.

---

## Interfaces 🖥️

The system has a web interface with the following screens:

- Login Screen
- Book Registration Screen
- User Registration Screen
- Book Borrowing Screen
- Book Return Screen
- Book Reservation Screen
- Book Query Screen

---

## Business Rules ⚙️

- A user can have a maximum of **5 books borrowed** at the same time.
- The borrowing period for a book is **14 days**.
- A book can only be reserved by **one user at a time**.

---

## Test Cases 🧪

### 1. **Book Registration**
   - Test with valid data (title, author, ISBN, publisher, year of publication, number of copies).
   - Test with invalid data (incorrect ISBN, invalid year of publication).
   - Test with mandatory fields left blank.

### 2. **Book Borrowing**
   - Test for users without pending issues (less than 5 books borrowed).
   - Test for users with pending issues (5 books borrowed).
   - Test for users with overdue returns.

### 3. **Book Reservation**
   - Test reserving an available book.
   - Test reserving a book already reserved by another user.
   - Test reserving a borrowed book.

### 4. **Book Query**
   - Test query by title.
   - Test query by author.
   - Test query by ISBN.

---

## Technologies Used 💻

- **HTML**: Page structure.
- **CSS**: Interface styling.
- **Bootstrap**: Framework for responsive design and pre-styled components.
- **JavaScript (Bootstrap)**: Used only for Bootstrap functionalities, such as modals and interactions.

---

## How to Run the Project 🚀

1. Clone the repository:

```
   git clone https://github.com/your-username/library-system.git
```

2. Navigate to the project folder:

```
   cd library-system
```

3. Open the index.html file in your browser.

---

## Contribution 🤝

Contributions are welcome! Follow the steps below:

1. Fork the project.

2. Create a branch for your feature:

```
   git checkout -b feature/new-feature
```

3. Commit your changes:

```
   git commit -m 'Add new feature'
```

4. Push to the branch:

```
   git push origin feature/new-feature
```

5. Open a Pull Request.

---

# License 📄

This project is licensed under the MIT License. See the LICENSE file for more details.

---

#### Versión en español.

# Sistema de Gestión de Biblioteca 📚

Este proyecto es una actividad propuesta durante las clases del curso de Informática para Internet del SENAI Pará de Minas CFP Dr. Celso Charurí y fue desarrollado con el propósito de iniciar y desarrollar el conocimiento sobre **casos de prueba**. La actividad propone la creación de un sistema de gestión de biblioteca desarrollado con **HTML**, **CSS** y **Bootstrap**. El objetivo es automatizar procesos como préstamo, devolución, reserva y consulta de libros, además de gestionar el catálogo de la biblioteca y la información de los usuarios.

---

## Integrantes 👥

- **Evelyn Duarte** - [Github](!)
- **Expedita Nogueira** - [Github](https://github.com/ExpeditaNogueira)
- **Jonnattan Silva** - [Github](https://github.com/JonnattanSS)
- **Lucas Goebel** - [Github](https://github.com/lgoebel)
- **Luís Lima** - [Github](https://github.com/LGSLima)
- **Matheus Marzagão** - [Github](https://github.com/MatheusShuctzo)

---

## Funcionalidades Principales 🛠️

- **Registro de Libros**: Permite registrar nuevos libros con información como título, autor, ISBN, editorial, año de publicación y número de ejemplares.
- **Registro de Usuarios**: Permite registrar nuevos usuarios con información como nombre, dirección, teléfono y correo electrónico.
- **Préstamo de Libros**: Registra el préstamo de un libro a un usuario, incluyendo la fecha de préstamo y la fecha de devolución prevista.
- **Devolución de Libros**: Registra la devolución de un libro, incluyendo la fecha de devolución real.
- **Reserva de Libros**: Permite que un usuario reserve un libro que no está disponible en ese momento.
- **Consulta de Libros**: Permite buscar libros en el catálogo por título, autor, ISBN o palabra clave.
- **Reportes**: Genera reportes sobre los libros más prestados, usuarios con más préstamos y libros atrasados.

---

## Interfaces 🖥️

El sistema tiene una interfaz web con las siguientes pantallas:

- Pantalla de Inicio de Sesión
- Pantalla de Registro de Libros
- Pantalla de Registro de Usuarios
- Pantalla de Préstamo de Libros
- Pantalla de Devolución de Libros
- Pantalla de Reserva de Libros
- Pantalla de Consulta de Libros

---

## Reglas de Negocio ⚙️

- Un usuario puede tener un máximo de **5 libros prestados** al mismo tiempo.
- El plazo de préstamo de un libro es de **14 días**.
- Un libro solo puede ser reservado por **un usuario a la vez**.

---

## Casos de Prueba 🧪

### 1. **Registro de Libros**
   - Probar con datos válidos (título, autor, ISBN, editorial, año de publicación, número de ejemplares).
   - Probar con datos inválidos (ISBN incorrecto, año de publicación inválido).
   - Probar con campos obligatorios en blanco.

### 2. **Préstamo de Libros**
   - Probar para usuarios sin pendientes (menos de 5 libros prestados).
   - Probar para usuarios con pendientes (5 libros prestados).
   - Probar para usuarios con retrasos en la devolución.

### 3. **Reserva de Libros**
   - Probar reserva de libro disponible.
   - Probar reserva de libro ya reservado por otro usuario.
   - Probar reserva de libro prestado.

### 4. **Consulta de Libros**
   - Probar consulta por título.
   - Probar consulta por autor.
   - Probar consulta por ISBN.

---

## Tecnologías Utilizadas 💻

- **HTML**: Estructura de las páginas.
- **CSS**: Estilización de las interfaces.
- **Bootstrap**: Framework para diseño responsivo y componentes pre-estilizados.
- **JavaScript (Bootstrap)**: Utilizado solo para funcionalidades de Bootstrap, como modales e interacciones.

---

## Cómo Ejecutar el Proyecto 🚀

1. Clona el repositorio:

```
   git clone https://github.com/tu-usuario/sistema-biblioteca.git
```

2. Navega hasta la carpeta del proyecto:

```
   cd sistema-biblioteca
```

3. Abre el archivo index.html en tu navegador.

---

## Contribución 🤝

¡Las contribuciones son bienvenidas! Sigue los pasos a continuación:

1. Haz un fork del proyecto.

2. Crea una rama para tu feature:

```
   git checkout -b feature/nueva-feature
```

3. Haz commit de tus cambios:

```
   git commit -m 'Agrega nueva feature'
```

4. Haz push a la rama:

```
   git push origin feature/nueva-feature
```

5. Abre un Pull Request.

---

# Licencia 📄

Este proyecto está licenciado bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.
