### Literarum

Literarum é uma aplicação web dedicada aos amantes da leitura. Com ela, você pode explorar uma vasta coleção de livros, descobrir novos autores e explorar temas fascinantes.

#### Recursos Principais

1. **Exploração por Título**: Busque livros de acordo com o título desejado.
2. **Catálogo de Livros**: Veja todos os livros disponíveis na plataforma.
3. **Autores em Destaque**: Conheça os autores mais lidos e apreciados.
4. **Análise de Temas**: Explore livros por temas específicos.
5. **Perfil de Leitor**: Personalize suas preferências de leitura.

#### Tecnologias Utilizadas

- Linguagem Java
- Framework Spring Boot
- Banco de Dados PostgreSQL
- API de Livros Gutendex
- Gerenciador de Dependências Maven

#### Configuração do Projeto

**Requisitos**
- Java 17 ou superior
- Maven
- Banco de Dados PostgreSQL

**Instalação**
1. Clone o repositório: `git clone https://github.com/324317/LitelAlura.git`
2. Configure o banco de dados no arquivo `application.properties`.
3. Execute o projeto: `mvn spring-boot:run`

#### Estrutura do Projeto

- `br.com.alura.literalura`
   - `controller`: Controladores da aplicação.
   - `model`: Classes de modelo (`Livro`, `Autor`, `Usuario`).
   - `repository`: Repositórios JPA para acesso ao banco de dados.
   - `service`: Serviços para lógica de negócio (`ConsultaAPI`, `ConversorDados`).

#### Uso

- Ao iniciar a aplicação, navegue pelas opções do menu principal para acessar as funcionalidades disponíveis.

#### Contribuição

- Faça um fork do projeto, crie uma nova branch, implemente suas melhorias e abra um pull request.

#### Licença

Este projeto está licenciado sob a MIT License. Consulte o arquivo `LICENSE` para mais informações.

#### Contato

Para qualquer dúvida ou sugestão, entre em contato conosco!

---

Aproveite o Literarum para explorar novos mundos através da leitura!