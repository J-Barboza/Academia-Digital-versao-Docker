<img src="https://hermes.digitalinnovation.one/tracks/48e9f018-f7c9-4f0f-b524-cd9223579626.png" alt="Formcao Docker Fundamentals logo" style="height: 100px; width: 100px">
<h1>Formação Docker Fundamentals>

<h2>Academia-Digital versao Docker</h2>
<p>Projeto educacional - Api Java com Spring Boot, Swagger em banco PostgreSql simulando app de uma academia, rodando no Docker</p>

Baseado na Api do projeto [Academia Digital](https://github.com/J-Barboza/academira-digital-dio)

- smartgym-0.0.3 - arquivo com o api do projeto com Java Spring Boot
- Dockerfile - aquivo com a imagem a ser utilizada e responsável por copiar a imagem.
- Docker-compose.yml - Arquivo que irá fazer o build da imagem e com as configurações dos demais containers.

Projeto:
- Api Java com Spring Boot
  - Imagem: openjdk:11-jre-slim
- Banco de Dados PostgreSql
  - Imagem: postgres:13.1-alpine
- Administrador para o Postgresql - PgAdmin
  - Imagem: dpage/pgadmin4:6.13

Para verificar a porta de acesso ao container da Api usa-se o comando
> Subir o container
>   `docker-compose up -d`
> Verificar a porta disponibilizada
>   `docker port smartgym`
> Baixar o container
>   `docker-compose down`
> Para testar a Api - Documentação
>   `localhost:<porta>/swagger-ui.html`

___
## Organizador: [DIO.me](https://web.dio.me/home)
### Mentor: Denilson Bonatti