# cypress-direto-ao-ponto

Projeto realizado no curso Cypress - Direto ao Ponto ministrado por Samuel Lucas.

### *Requisitos*
É necessário ter o Node instalado para rodar este projeto.

### *Comando para inicializar um projeto Node*

```   
    npm init --yes
```
### *Comandos para instalar o Cypress*
```
    npm install -D cypress
    npm install -D cypress@12.5.0 [versão específica]
```

### *Testes*
É possível rodar os testes simulando a visualização desktop e mobile.

#### *Desktop*
#### Comandos para abrir o Cypress
```
    npx cypress open [modo interativo]
    npx cypress run  [modo headless]
    npm test  [script customizado para modo headless]
```

#### *Mobile*
#### Comando para rodar em visualização mobile (via terminal):
```
    npx cypress run --config viewportHeight=1000,viewportWidht=600
```

### Gif da Execução dos Testes

![Gif da Execução](https://github.com/camilaaptt/cypress-direto-ao-ponto/blob/main/cypress-direto-ao-ponto.gif)

### Documentação do Cypress:

https://docs.cypress.io/guides/overview/why-cypress

Apoie este projeto, deixe uma ⭐.







