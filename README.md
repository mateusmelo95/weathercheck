# Weather Check
Medidor Climático ou Weather Check é um projeto de uma estação meteorológica inteligente para coleta, processamento e análise de dados sensoriais para criação de referência temporal de dados e geração de alertas com uso de Machine Learning e IA

![Mobile 1](https://lh3.googleusercontent.com/pw/ADCreHdjKhmMVEm_Ba82Votl0Fcun2LVu3JEs-RpqDECw6wp2iLjcHVpIb33afHCfM3Rd2dKE3kSEkNEk-Ij9G2VCJOaBWH4zWgjnKWxhgp2EdcrBAigpYxs84LK3Ot1tzc1FnP3OypXtwuSrhKq1ZXaBLCztherTls5_sZpW0ZV_FtSD_WxIrXxTtKwCWddvBGSorhWvwyLX6tkCrK0D9GJuzp6gdBjHCTgO1FEy8ZvTuw0fxtEEY0kTzKTM277UZlsn-DN-LuH8Qqi_DiUij60-_2bsW2Xze4bndJpJ8gkGN1M_IpLDoXoR0LULJrspVlgyPWreXnn8Qf_MW6TRAJtf30BGQIv2k45mjaZQUynv56tpxQs_AIZ1cKSrGOHQHMH7Y3au7aOtCJS2DodsN9yh9M7dHwba0fnc-uSBlrzzcByPeiJiuBsr5EY48wqD2667nXXAVOXYgju7w6YrEJXtXblfEAXozaNdRlrzYFUwpZmY2peuT8uH3WcJr59r2VuzXiDNrsYx6C92FdfznPd_KqQfhj4sxJ3TTKvw95NvMZg9sVixX96ywDDUVJJhDbXoLI7sl0122oRcYg-mogkjO_o_UUqutMSwudVklo5mS6Mu-Eoaoqz72I8TWtjrzXheOsNwuh8wC_cESg6hHw37xzU5Wh34el5byGlXsa8UWflbVq3ybC9IFYHXo5uXY4BnYb7Mqkt8eveY0dniDKvf_s5EYKrEFA0b9XQw1vG-V5zSvn7EVICflb0nylYI3aQzMM4IgmTqxWyLPBCG5nlr86fhQpEpIlxC4ihY7dLzHoCHxdbkSFQEWKB8-YQ67O7h21nzPyO-UV3rXKu0e5ZAQPVvaHel5Lu0mehfQi6fqbWLT0k1MsA_3N5dvz7Y7aj6opZWChe3aQZOSTv10CgvX5XE9kyEj4d5bfnpZkTL5h6hVTHK0f9c0fRQgnA9ngarien9xcuy1bU2xKy3JoxnROAV9IduIzY=w721-h597-s-no-gm?authuser=0)
# Sobre o projeto

https://wmazoni-sds1.netlify

Big Game Survey é uma aplicação full stack web e mobile construída durante a 1ª edição da **Semana DevSuperior** (#sds1), evento organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

A aplicação consiste em uma pesquisa de preferência de games, onde os dados são coletados no app mobile, e depois são listados no app web, que também apresenta um dashboard com gráficos baseados nestes dados.

## Layout mobile
![Mobile 1](https://lh3.googleusercontent.com/pw/ADCreHfsz6NmAE_V79lEFHSSMoyOq71m2EbPIrDJXexpQWduaMFotcVF0yCeqcB1wuKEmbvNMgLmGJQX-WK6HZtbOOlXxB5ynYz7adB83BwUHD6gKAPl6ARfitaNE0R-KW-HqewCvTcG4cqSoe4MrEMDjvZ4=w842-h632-s-no?authuser=0) ![Mobile 2](https://github.com/acenelio/assets/raw/main/sds1/mobile2.png)

## Layout web
![Web 1](https://github.com/acenelio/assets/raw/main/sds1/web1.png)

![Web 2](https://github.com/acenelio/assets/raw/main/sds1/web2.png)

## Modelo conceitual
![Modelo Conceitual](https://github.com/acenelio/assets/raw/main/sds1/modelo-conceitual.png)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
## Front end
- HTML / CSS / JS / TypeScript
- ReactJS
- React Native
- Apex Charts
- Expo
## Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

# Como executar o projeto

## Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/devsuperior/sds1-wmazoni

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

## Front end web
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone https://github.com/devsuperior/sds1-wmazoni

# entrar na pasta do projeto front end web
cd front-web

# instalar dependências
yarn install

# executar o projeto
