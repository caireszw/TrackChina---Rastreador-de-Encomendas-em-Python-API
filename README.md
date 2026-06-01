# TrackChina - Rastreador de Encomendas

## 📌 Sobre o Projeto

O **TrackChina** é um sistema desenvolvido em Python para acompanhar encomendas internacionais, especialmente compras vindas da China.

O projeto permite cadastrar códigos de rastreio, consultar o status das encomendas, visualizar o histórico salvo e organizar melhor os pedidos acompanhados pelo usuário.

---

## 🚀 Funcionalidades

* Cadastrar código de rastreio
* Consultar status da encomenda
* Salvar histórico em arquivo JSON
* Listar encomendas cadastradas
* Filtrar encomendas por status
* Remover encomendas do histórico
* Limpar histórico
* Menu interativo no terminal

---

## 🛠️ Tecnologias Utilizadas

* Python
* Requests
* JSON
* API de rastreamento de encomendas

---

## 📂 Estrutura do Projeto

```text
trackchina/
│
├── main.py
├── rastreio.py
├── interface.py
├── encomendas.json
└── README.md
```

---

## 💻 Exemplo de Uso

```text
1 - Adicionar código de rastreio
2 - Consultar encomenda
3 - Ver histórico
4 - Remover encomenda
5 - Limpar histórico
6 - Sair
```

---

## 🎯 Objetivo

Este projeto tem como objetivo praticar conceitos importantes de Python, como:

* Consumo de APIs
* Manipulação de JSON
* Leitura e escrita de arquivos
* Modularização de código
* Estruturas de dados
* Validação de entradas
* Organização de projetos em terminal

---

## 📦 Exemplo de Dados Salvos

```json
[
    {
        "codigo": "AB123456789CN",
        "status": "Em trânsito",
        "origem": "China",
        "destino": "Brasil",
        "ultima_atualizacao": "Objeto em transferência"
    }
]
```

---

## 👨‍💻 Autor

Matheus Caires
