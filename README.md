# ControlComBL 🚀

<div align="center">

[![Vercel Deployment](https://img.shields.io/badge/Status-Online-success?style=for-the-badge&logo=vercel)](https://control-com-bl.vercel.app/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repositório-blue?style=for-the-badge&logo=github)](https://github.com/dvignali01-oss/ControlComBL)
[![Licença](https://img.shields.io/badge/Licença-MIT-purple?style=for-the-badge)](https://opensource.org/licenses/MIT)

**Gestão Comercial e Indicadores de Vendas**  
*Plataforma web interativa desenvolvida com foco em inteligência comercial, controle de comissões, gestão de carteira de clientes e análise de desempenho para profissionais de vendas.*

</div>

---

## 📌 Apresentação do Projeto

O **ControlComBL** (*Sales Intelligence Pro*) é uma aplicação web moderna e responsiva desenvolvida para auxiliar profissionais de vendas e gestão comercial no controle diário de seus negócios, cálculo automatizado de comissões por faixas de volume, acompanhamento de metas financeiras e quantitativas, e gestão de carteira de clientes.

Criado como projeto prático de desenvolvimento web e expansão para **análise de dados**, o sistema transforma registros simples de vendas em **indicadores comerciais claros (KPIs)**, facilitando a tomada de decisão baseada em dados (*data-driven*).

---

## 🎯 Problema que o Projeto Busca Resolver

Profissionais de vendas autônomos e equipes comerciais frequentemente enfrentam dificuldades em:
1. **Acompanhar em tempo real** o atingimento de metas de faturamento e quantidade de instalações.
2. **Calcular comissões complexas** baseadas em diferentes faixas de volume de produtos (TV, Internet, Móvel e Fixo).
3. **Gerenciar a carteira de clientes** (pendentes vs. instalados) sem depender de planilhas complexas ou anotações em papel dispersas.
4. **Visualizar métricas essenciais** como Ticket Médio e Taxa de Conversão de Instalação de forma imediata e intuitiva.

O **ControlComBL** centraliza todas essas necessidades em uma interface limpa, rápida e inspirada em dashboards analíticos de alto nível.

---

## ✨ Principais Funcionalidades Implementadas

* **🔒 Autenticação e Acesso Seguro:** Tela de entrada protegida com fluxo direto para o painel comercial.
* **📊 Dashboard de Indicadores de Performance (KPIs):** Visão executiva consolidando Total de Vendas, Ticket Médio, Vendas Instaladas, Taxa de Instalação (%), Ganhos Garantidos e Ganhos Pendentes.
* **📝 Registro de Novas Vendas:** Formulário estruturado para cadastro de clientes, contato WhatsApp, produtos comercializados (TV, Net, Móvel, Fixo com quantidade e valores individuais), cálculo automático do valor total, data de instalação e status (*Pendente* ou *Instalado*).
* **🗂️ Gestão de Carteira (`Minha Carteira`):** Listagem completa de clientes cadastrados, com filtro por nome, visualização de status, valores, datas e opção de exclusão de registros.
* **🎯 Metas & Ganhos e Simulador de Faixas:** Acompanhamento visual do progresso de metas (quantidade e valor), cálculo dinâmico de comissão acumulada e um **Simulador de Faixas** interativo para testar ganhos projetados com base em diferentes volumes de instalação.
* **📓 Bloco de Notas Rápido:** Área integrada no painel para anotações diárias do operador.
* **📤 Relatório de Fechamento:** Geração de resumo executivo para fechamento de período.

---

## 📸 Galeria de Capturas de Tela

<div align="center">

| Dashboard Principal | Gestão de Clientes (Carteira) |
| :---: | :---: |
| ![Dashboard Principal](dashboard.png) | ![Gestão de Clientes](gestao-clientes.png) |
| *Visão consolidada dos KPIs de vendas e ganhos.* | *Filtro e acompanhamento de carteira de clientes.* |

| Metas, Ganhos e Simulador | Cadastro de Nova Venda |
| :---: | :---: |
| ![Metas e Comissões](comissoes-metas.png) | *(Interface de formulário integrada)* |
| *Acompanhamento de metas e simulador de faixas.* | *Cadastro por categorias (TV, Net, Móvel, Fixo).* |

</div>

---

## 🛠️ Tecnologias Utilizadas

O projeto foi construído utilizando tecnologias modernas e leves do ecossistema web:

* **Linguagem:** HTML5, CSS3 / Tailwind CSS (estilização moderna e responsiva).
* **Framework / Biblioteca:** React.js / Vite (componentização e alta performance).
* **Persistência de Dados:** `LocalStorage` do navegador (armazenamento local seguro e offline-first).
* **Hospedagem & Deploy:** [Vercel](https://control-com-bl.vercel.app/) (entrega contínua e alta disponibilidade).
* **Controle de Versão:** Git e GitHub.

---

## 🏗️ Diagrama da Arquitetura

O diagrama abaixo ilustra a arquitetura técnica e o fluxo de dados do **ControlComBL**:

<div align="center">
  <img src="arquitetura.png" alt="Diagrama de Arquitetura do ControlComBL" width="80%"/>
</div>

* **Camada de Apresentação (Frontend):** Aplicação Single Page em React / Vite renderizada no navegador do usuário ou via Vercel.
* **Camada de Lógica & Estado:** Gerenciamento de estado local para cálculos de KPIs, ticket médio, taxas e simulação de comissões.
* **Camada de Persistência:** Utilização nativa do `LocalStorage` para persistir os registros de vendas, clientes e metas do usuário no próprio dispositivo.

---

## 🚀 Como Acessar a Aplicação

A aplicação está totalmente funcional e hospedada na nuvem. Você pode acessá-la diretamente pelo navegador (computador ou celular):

🔗 **[Acessar ControlComBL na Vercel](https://control-com-bl.vercel.app/)**

---

## 💻 Como Executar o Projeto Localmente

Se você deseja clonar e executar o repositório em sua máquina de desenvolvimento, siga os passos abaixo:

### Pré-requisitos
Certifique-se de ter instalado em seu computador:
* **Node.js** (versão 16 ou superior)
* **Git**

### Passo a passo

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/dvignali01-oss/ControlComBL.git](https://github.com/dvignali01-oss/ControlComBL.git)
   

