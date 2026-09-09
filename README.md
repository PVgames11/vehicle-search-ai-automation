# 🚗 Automação Inteligente para Busca de Veículos com IA

## 📋 Sobre o Projeto

Este projeto consiste em uma automação inteligente desenvolvida para facilitar a busca de veículos e automatizar a comunicação com possíveis clientes.

O usuário pode realizar uma busca utilizando diferentes critérios, como:

- Marca
- Modelo
- Ano
- Cor
- Valor

Após realizar a busca e informar seu endereço de e-mail, o sistema consulta automaticamente uma base de dados contendo os veículos disponíveis.

Os veículos encontrados são enviados para uma Inteligência Artificial, responsável por gerar um e-mail de vendas personalizado para o cliente.

---

## ⚙️ Como funciona

A automação segue o seguinte fluxo:

```text
Formulário de Busca
        ↓
       n8n
        ↓
Google Sheets
        ↓
Consulta de Veículos
        ↓
Gemini AI
        ↓
Geração do E-mail
        ↓
      Gmail
        ↓
Cliente recebe o resultado
```
Etapas da Automação
O usuário acessa o formulário de busca.
Seleciona o critério desejado.
Digita a informação que deseja buscar.
Informa seu endereço de e-mail.
Os dados são enviados para o n8n.
O n8n consulta a base de veículos no Google Sheets.
Os veículos encontrados são enviados para o Gemini AI.
A Inteligência Artificial gera um e-mail personalizado.
O e-mail é enviado automaticamente para o usuário.
🧠 Inteligência Artificial

O projeto utiliza o Gemini AI para transformar os dados dos veículos encontrados em um e-mail de vendas profissional, atrativo e personalizado.

A Inteligência Artificial foi configurada para utilizar exclusivamente as informações disponíveis na base de dados:

Marca
Modelo
Ano
Cor
Valor

Também foram definidas regras para evitar que a IA invente informações sobre os veículos.

Por exemplo, a IA não deve criar informações sobre:

Quilometragem
Motor
Opcionais
Descontos
Condições especiais
Disponibilidade

Caso nenhum veículo seja encontrado, a Inteligência Artificial gera uma mensagem alternativa incentivando o cliente a entrar em contato e conhecer outras opções disponíveis.

🛠️ Tecnologias Utilizadas
n8n
Google Sheets
Gemini AI
Gmail
Formulário Web
Inteligência Artificial Generativa
Automação de Processos
📊 Base de Dados

A base de dados utilizada no projeto foi criada utilizando o Google Sheets.

Cada veículo possui as seguintes informações:

Informação	Descrição
ID	Identificação do veículo
Marca	Marca do veículo
Modelo	Modelo do veículo
Ano	Ano do veículo
Cor	Cor do veículo
Valor	Valor do veículo
🎯 Objetivo

O objetivo deste projeto é demonstrar como a automação de processos e a Inteligência Artificial podem ser utilizadas para melhorar a comunicação entre empresas e clientes.

A solução pode ajudar empresas do setor automotivo a automatizar tarefas como:

Busca de veículos
Consulta de informações
Comunicação com clientes
Geração de e-mails
Atendimento inicial
Divulgação de produtos
🚀 Possíveis Melhorias Futuras

O projeto pode ser expandido com novas funcionalidades, como:

Integração com WhatsApp
Integração com CRM
Banco de dados como Supabase ou PostgreSQL
Cadastro automático de leads
Dashboard administrativo
Histórico de buscas
Recomendações inteligentes de veículos
Agendamento automático de test-drive
Chatbot com Inteligência Artificial
Integração com sites de concessionárias
💡 Possíveis Aplicações

Esta automação pode ser adaptada para diferentes tipos de empresas e negócios.

Alguns exemplos:

Concessionárias
Lojas de veículos
Revendedoras
Marketplaces automotivos
Empresas de vendas

A mesma ideia também pode ser adaptada para outros segmentos, permitindo que clientes pesquisem produtos e recebam automaticamente informações personalizadas por e-mail.

👨‍💻 Autor

Paulo Vitor

Graduado em Ciência da Computação e interessado nas áreas de:

Automação
Inteligência Artificial
n8n
IoT
Sistemas Inteligentes
Integração de Sistemas
📫 Contato

Caso queira trocar ideias sobre automação, Inteligência Artificial, IoT ou tecnologia, fique à vontade para entrar em contato.

⭐ Se você gostou do projeto, considere deixar uma estrela no repositório!
