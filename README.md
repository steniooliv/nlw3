<p align="center"><img src="https://github.com/steniooliv/nlw3/blob/master/web/public/cover.jpg" width=400 alt="Happy">
<h1 align="center">Next Level Week 3 - Happy<h1>
</p>
  
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/steniooliv/nlw3/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/steniooliv/nlw3/?branch=master) [![Stenio](https://img.shields.io/badge/steniooliv-in-%230072b1)](https://www.linkedin.com/in/steniooliv)
  
## Sobre
*Na terceira edição da NLW criamos uma aplicação OpenSource de uma plataforma para localizar orfanatos para visitar.*
*Ao acessar a aplicação vamos ser redirecionados ao mapa com pontos de localização dos orfanatos, ao clicar neles é possível acessar a página de detalhes.*
*Na página de detalhe é possível clicar no botão para direcionar e criar uma rota no Google Maps, é possível ver também o horário de funcionamento e se abre aos finais de semana.*
*Também temos a opção de cadastro de orfanato, é possível colocar a posição do orfanato no mapa, informar o nome e horário de funcionamento e se abre no final de semana através de um botão on/off.*
*A aplicação foi desenvolvida em Typescript com Node, React e React Native.*

## Ferramentas Utilizadas
### Front-end
**React**, uma lib usada para criarmos nossa interface, com o React conseguimos trazer uma experiência de Single Page Application para o usuário, deixando a navegação muito mais agradável e ágil
**Axios**, uma ferramenta para auxiliar o nosso frond-end a consumir os dados da API

### Back-end
- **Express**, framework utilizado para criar nossa API
- **TypeORM**, ORM que pode ser utilizado com Typescript em Node e React
- **SQLite3**, utilizamos o SQLite para criar nossa database
- **Cors**, permite que nossa API seja acessada através de outro endereço
- **Insomnia**, utilizamos para testar nossas metodos POST e GET
  
### Mobile
- **React Native**, uma lib para deselvolver aplicativos Android e iOS de forma nativa
- **Expo**, framework de desenvolvimento mobile para acesso ágil à API's

## Pré Requisitos
- Git, utilize para clonar este repositório, baixe através de um gerenciador de pacotes ou clicando [aqui](https://git-scm.com/).
- Node, motor de desenvolvimento da aplicação, baixe através de um gerenciador de pacotes ou clicando [aqui](https://nodejs.org/en/).
Essa aplicação foi feita usando a versão 12.18.3.
- Expo, framework de desenvolvimento mobile, instale através do gerenciador de pacotes do próprio Node através do comando abaixo:

  ```npm install expo-cli --global```


## Utilização
- Atráves do terminal, faça o clone do repositório com o comando git abaixo:

  ```git clone https://github.com/steniooliv/nlw3.git nlw3```

### Executando a aplicação Web
```
# Acesse a pasta da aplicação web (frontend) 
$ cd web

# Instale as dependências necessárias
$ npm install

# Execute a aplicação
$ npm start

# Caso a aplicação não seja aberta no navegador acesse o endereço: http://localhost:3333
```

### Executando a API
```
# Acesse a pasta do servidor (backend) 
$ cd backend

# Instale as dependências necessárias
$ npm install

# Crie um banco de dados limpo
$ npm run typeorm migration:run

# Execute o servidor
$ npm run dev

# Caso a aplicação não seja aberta no navegador acesse o endereço: http://localhost:3333
# Mantenha o servidor rodando para ter acesso ao banco de dados tanto no frontend quanto no mobile
```

### Executando Aplicação Mobile
- Baixe o Expo para [Android](https://play.google.com/store/apps/details?id=host.exp.exponent&hl=pt_BR) ou [iOS](https://apps.apple.com/br/app/expo-client/id982107779)

```
# Acesse a pasta mobile 
$ cd mobile

# Instale as dependências necessárias
$ npm install

# Execute o servidor
$ npm start

# Abra o Aplicativo Expo no seu smartphone e escaneie o QRCode para acessar a aplicação mobile no smartphone
```

## Updates
Esse documento será atualizado de acordo com o andamento da aplicação

## License
Este projeto é protegido sobre o MIT License - veja o arquivo [LICENSE.md](LICENSE.md) para mais detalhes
