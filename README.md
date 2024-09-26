# Moneygment

**Moneygment** é um sistema de gestão de finanças pessoais que permite aos usuários monitorar suas despesas diárias de forma simples e eficiente. Ele oferece funcionalidades básicas de gerenciamento financeiro, como inserir, excluir, listar e alterar despesas, utilizando um modelo CRUD (Create, Read, Update, Delete).

## Funcionalidades
- **Clique no botão de adicionar do menu para adicionar e remover lancamentos como receitas ou despesas**;
- **Clique no botão à esquerda do botão de adicionar para vizualizar, editar e excluir os lançamentos**;
- **Inserir Despesa**: Adicione novas despesas com informações como descrição, valor e data.
- **Excluir Despesa**: Remova despesas indesejadas ou incorretas do sistema.
- **Listar Despesas**: Exiba todas as despesas cadastradas de forma organizada.
- **Alterar Despesa**: Edite as informações de uma despesa já cadastrada.

## Tecnologias Utilizadas

- **Java (Servlets)**: Implementação das regras de negócio e controle de fluxo entre frontend e backend.
- **JSP (JavaServer Pages)**: Geração dinâmica de páginas web e interação com o usuário.
- **Bootstrap**: Criação de uma interface responsiva e amigável.
- **JavaScript**: Validações no frontend e interações dinâmicas.
- **OracleSQL**: Banco de dados utilizado para armazenamento seguro das despesas.

## Estrutura do Projeto

- **src/**: Contém os arquivos de código-fonte do backend (Java, Servlets).
- **WebContent/**: Contém as páginas JSP e arquivos estáticos (HTML, CSS, JavaScript).

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/edunetviper/projeto-fintech.git
   ```

2. Configure o ambiente:
   - Certifique-se de ter o **JDK 11+** e **Apache Tomcat** instalados.

3. Importe o projeto para sua IDE (Eclipse, IntelliJ, etc.).

4. Configure o servidor Tomcat e rode a aplicação.

5. Acesse o sistema no navegador:
   ```
   http://localhost:8080/Moneygment/login.jsp
   ```

---
Desenvolvido por [Eduardo Gonçalves](https://github.com/edunetviper) para o challenge da FIAP.


