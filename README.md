# PowerGreen
**PowerGreen**
*Energia limpa em moviento*
![GitHub repo size](https://img.shields.io/github/repo-size/wagnermor/PowerGreen_BackEnd?color=green) [![GitHub](https://img.shields.io/github/license/wagnermor/PowerGreen_BackEnd)](https://github.com/wagnermor/PowerGreen_BackEnd/blob/main/LICENSE) ![GitHub top language](https://img.shields.io/github/languages/top/wagnermor/PowerGreen_BackEnd?color=green)
# Sobre o projeto

[https://powerGreen.com.br](https://github.com/wagnermor/PowerGreen_BackEnd "Projeto powerGreen")
PowerGreen é uma aplicação full stack, web e mobile, construída como projeto integrador durante o bootcamp **JAVA FullStack** oferecido por [Generation](https://brazil.generation.org "Site da Generation") e [Zé Delivery](https://www.ze.delivery "Site do Zé Delivery").

A aplicação consiste em um e-commerce para locação de bateria recaregável (powerbank) para veículos elétricos, onde é feito o cadastro e login do usuário e depois de logado, são listadas as baterias disponíveis para locação.


## Modelo 
```mermaid
graph TD;
Página_principal-->Cadastro/usuário;
Página_principal-->Login_usuário;
Cadastro/usuário-->Escolha_da_assinatura;
Login_usuário-->Escolha_da_assinatura;
Escolha_da_assinatura-->Escolha_da_bateria;
Escolha_da_bateria-->Pagamento_adicional;
Escolha_da_bateria-->Finaliza_pedido;
Pagamento_adicional-->Finaliza_pedido;
```

## DER - Diagrama Entidade Relacionamento
![DER](./assets/DER.png)

# Tecnologias utilizadas
## Back end &nbsp; ![GitHub language count](https://img.shields.io/github/languages/count/wagnermor/PowerGreen_BackEnd)

- Java
- Spring Boot
- JPA / Hibernate
- Maven

## Implantação em produção
- Back end: 
- Banco de dados: MySQL

# Como executar o projeto

## Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/wagnermor/PowerGreen_BackEnd

# entrar na pasta do projeto back end
cd powerGreen

# executar o projeto
./mvnw spring-boot:run
```

# Colaboradores
<div>
  <div style = "max-width:140px;
    text-align:center;
    border:none;
    float:left;
    display:inline-block;
    margin: 0 24px 16px 0">
    <div style="border-radius: 100%;
        margin:0 auto;
        overflow: hidden;
        height: 100px;
        width:100px;
        background: black;">
        <img style = "width:50px" src="https://avatars.githubusercontent.com/u/47096330?v=4"/>
    </div>
    <p>Wagner Moreira</p>
    <a href="https://github.com/wagnermor" target="_blank">
      <img src="https://img.shields.io/github/followers/wagnermor?style=social"/>
    </a>
  </div>

<div style = "max-width:140px;
    text-align:center;
    border:none;
    float:left;
    display:inline-block;
    margin: 0 24px 16px 0">
    <div style="border-radius: 100%;
        margin:0 auto;
        overflow: hidden;
        height: 100px;
        width:100px;
        background: black;">
        <img style = "width:50px" src="https://avatars.githubusercontent.com/u/120661184?v=4"/>
    </div>
    <p>Marlon Bassoto</p>
    <a href="https://github.com/Killbazz" target="_blank">
      <img src="https://img.shields.io/github/followers/Killbazz?style=social"/>
    </a>
  </div>

<div style = "width:140px;
    text-align:center;
    border:none;
    float:left;
    display:inline-block;
    margin: 0 24px 16px 0">
    <div style="border-radius: 100%;
        margin:0 auto;
        overflow: hidden;
        height: 100px;
        width:100px;
        background: black;">
        <img style = "width:50px" src="https://avatars.githubusercontent.com/u/120653890?v=4"/>
    </div>
    <p>Joel Jr.</p>
    <a href="https://github.com/Joeljrbeginner" target="_blank">
      <img src="https://img.shields.io/github/followers/Joeljrbeginner?style=social"/>
    </a>
  </div>

<div style = "width:140px;
    text-align:center;
    border:none;
    float:left;
    display:inline-block;
    margin: 0 24px 16px 0">
    <div style="border-radius: 100%;
        margin:0 auto;
        overflow: hidden;
        height: 100px;
        width:100px;
        background: black;">
        <img style = "width:50px" src="https://avatars.githubusercontent.com/u/120660461?v=4"/>
    </div>
    <p>Carol Bertulli</p>
    <a href="https://github.com/CarolBertulli" target="_blank">
      <img src="https://img.shields.io/github/followers/CarolBertulli?style=social"/>
    </a>
  </div>
  
  <div style = "width:140px;
    text-align:center;
    border:none;
    float:left;
    display:inline-block;
    margin: 0 24px 16px 0">
    <div style="border-radius: 100%;
        margin:0 auto;
        overflow: hidden;
        height: 100px;
        width:100px;
        background: black;">
        <img style = "width:50px" src="https://avatars.githubusercontent.com/u/120189007?v=4"/>
    </div>
    <p>Jessica Cavalcante</p>
    <a href="https://github.com/jess59cavalcante" target="_blank">
      <img src="https://img.shields.io/github/followers/jess59cavalcante?style=social"/>
    </a>
  </div>

<div style = "width:140px;
    text-align:center;
    border:none;
    float:left;
    display:inline-block;
    margin: 0 24px 16px 0">
    <div style="border-radius: 100%;
        margin:0 auto;
        overflow: hidden;
        height: 100px;
        width:100px;
        background: black;">
        <img style = "width:50px" src="https://avatars.githubusercontent.com/u/117678443?v=4"/>
    </div>
    <p>Gustavo Henrique</p>
    <a href="https://github.com/Jotapppe" target="_blank">
      <img src="https://img.shields.io/github/followers/Jotapppe?style=social"/>
    </a>
  </div>

  <div style = "width:140px;
    text-align:center;
    border:none;
    float:left;
    display:inline-block;
    margin: 0 24px 16px 0">
    <div style="border-radius: 100%;
        margin:0 auto;
        overflow: hidden;
        height: 100px;
        width:100px;
        background: black;">
        <img style = "width:50px" src="https://avatars.githubusercontent.com/u/47096330?v=4"/>
    </div>
    <p>Henrique Vieira</p>
    <a href="https://github.com/wagnermor" target="_blank">
      <img src="https://img.shields.io/github/followers/wagnermor?style=social"/>
    </a>
  </div>
</div>
