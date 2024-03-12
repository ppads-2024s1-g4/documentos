# Definição de Arquitetura 
## Componentes:
- Cliente Web: Interface web e mobile para os usuários interagirem com o sistema.
- API Spring Boot: API RESTful que fornece acesso aos dados e funcionalidades da rede social.
- Banco de Dados AWS RDS: Armazena os dados da rede social, como usuários, avaliações, filmes, séries e livros.
- Servidor AWS EC2: Para executar a API Spring Boot.

## Ambiente de Desenvolvimento e Implantação:
- Optamos por utilizar serviços de nuvem, como AWS, para hospedar nossa aplicação devido à sua escalabilidade e facilidade de gerenciamento.

## Tecnologias Utilizadas:
- Escolhemos o framework IntelliJ e VScode para o backend devido à sua robustez, facilidade de desenvolvimento e grande comunidade de suporte.
- Bancos de dados escaláveis e eficientes para armazenar os dados da aplicação, como MySQL ou PostgreSQL.
- Para o frontend, optamos pelo framework React, Javascript, HTML e CSS pois já estamos mais familiarizados, além da sua eficiência e capacidade de construir interfaces de usuário interativas.
  
## Arquitetura da Aplicação:
- Adotamos uma arquitetura de microserviços pois permite que a equipe trabalhe em diferentes partes da aplicação sem interferir no trabalho por completo.
- Dividimos as funcionalidades em diferentes serviços, como autenticação, gestão de usuários, avaliação de filmes, séries e livros, etc., para facilitar o desenvolvimento e manutenção da aplicação.

## Segurança:
- Implementamos algumas medidas de segurança, como autenticação e autorização de usuários - apenas usuários com conta poderão acessar a plataforma. A fim de proteger os dados e garantir que apenas usuários autorizados tenham acesso às funcionalidades da aplicação.
- HTTPS para garantir a segurança das comunicações entre o cliente e o servidor, protegendo os dados sensíveis dos usuários contra ataques de interceptação.
