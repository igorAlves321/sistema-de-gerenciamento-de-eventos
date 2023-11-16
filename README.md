#Sistema de gerenciamento de eventos:
O objetivo deste sistema é gerenciar eventos e seus participantes. Este projeto foi desenvolvido durante um curso de Java realizado nos anos de 2022 e início de  2023, abordando fundamentos da linguagem de programação Java, orientação a objetos e o framework Spring.
Pré-requisitos para Execução
Para executar este projeto, é necessário ter instalado:

JDK, preferencialmente a versão 17.

Um gerenciador de banco de dados, como MySQL ou XAMPP (que inclui o MySQL).

As dependências do Spring, que podem ser instaladas através do IntelliJ ou outra IDE de sua preferência, utilizando o arquivo `pom.xml`. Alternativamente, é possível instalar as dependências manualmente via linha de comando. Neste caso, navegue até a pasta do projeto com o comando `cd` (por exemplo: `cd desktop`, `cd sistema-de-gerenciamento-de-eventos`) e execute `mvnw install`.
Funcionalidades

Classe `Evento`: Permite a criação e gerenciamento de eventos, com atributos como `nome`, `local`, `data` e `horário`.

Classe `Convidado`: Gerencia os convidados de cada evento, com cada `Convidado` associado a um `Evento`.

Classes `Usuario` e `Role`: Implementam a autenticação e autorização no sistema. `Usuario` representa os usuários do sistema, enquanto `Role` representa os diferentes papéis ou permissões disponíveis para esses usuários.
Este breve resumo oferece uma visão geral do projeto.