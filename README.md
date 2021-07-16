## Finapi
##### A Finapi é uma api simples que lida com movimentações financeiras

[![GitHub issues](https://img.shields.io/github/issues/diozhn/finapi)](https://github.com/diozhn/finapi/issues)
[![GitHub forks](https://img.shields.io/github/forks/diozhn/finapi)](https://github.com/diozhn/finapi/network)
[![GitHub stars](https://img.shields.io/github/stars/diozhn/finapi)](https://github.com/diozhn/finapi/stargazers)


<h4 align="center"> 
	Finapi 🚀 Projeto Concluído  
</h4>

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/). 
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

### 🎲 Rodando a API (servidor)

```bash
# Clone este repositório
$ git clone <https://github.com/diozhn/finapi.git>

# Acesse a pasta do projeto no terminal/cmd
$ cd finapi

# Instale as dependências
$ npm install
# Caso use yarn
$ yarn

# Execute a aplicação em modo de desenvolvimento
$ yarn dev
# Com npm
$ npm dev

# O servidor inciará na porta:3333 - acesse <http://localhost:3333>
```

### 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com)

---

### Requisitos

- [x] Deve ser possível criar uma conta
- [x] Deve ser possível buscar o extrato bancário do cliente
- [x] Deve ser possível realizar um depósito
- [x] Deve ser possível realizar um saque
- [x] Deve ser possível buscar o extrato bancário do cliente por data
- [x] Deve ser possível atualizar dados da conta do cliente
- [x] Deve ser possível obter dados da conta do cliente
- [x] Deve ser possível deletar uma conta
- [ ] Deve ser possível retornar o balance

---

## Regras de negócio

- [x] Não deve ser possível cadastrar uma conta com CPF já existente
- [x] Deve ser possível buscar extrato em uma conta não existente
- [x] Não deve ser possível fazer depósito em uma conta não existente
- [x] Não deve ser possível fazer saque em uma conta não existente
- [x] Não deve ser possível fazer saque quando o saldo for insuficiente
- [x] Não deve ser possível excluir uma conta não existente
  

  ### Autor
---

<a href="https://twitter.com.br/diozhn">
 <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/61253739?v=4" width="100px;" alt=""/>
 <br />
 <sub><b>Diogo Mendes</b></sub></a> <a href="https://twitter.com.br/diozhn" title="Twitter">🚀</a>


Feito com ❤️ por Diogo Mendes 👋🏽 Entre em contato!

[![Twitter Badge](https://img.shields.io/badge/-@diozhn-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/diozhn)](https://twitter.com/diozhn) [![Linkedin Badge](https://img.shields.io/badge/-Diogo-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/diozhn/)](https://www.linkedin.com/in/diozhn/) 
[![Gmail Badge](https://img.shields.io/badge/-diogo@blitzen.cc-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:diogo@blitzen.cc)](mailto:diogo@blitzen.cc)
