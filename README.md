ControlComBL | Sales Intelligence

Gestão comercial, indicadores de desempenho e controle de comissões.

<p align="center">
  <a href="https://control-com-bl.vercel.app/">
    <img src="https://img.shields.io/badge/Aplicação-Online-2563EB?style=for-the-badge&logo=vercel" alt="Aplicação online"/>
  </a>
  <a href="https://github.com/dvignali01-oss/ControlComBL">
    <img src="https://img.shields.io/badge/Código-GitHub-181717?style=for-the-badge&logo=github" alt="Repositório GitHub"/>
  </a>
  <img src="https://img.shields.io/badge/Área-Inteligência%20Comercial-0F766E?style=for-the-badge" alt="Inteligência comercial"/>
</p>---

Sobre o projeto

O ControlComBL é uma aplicação web voltada à gestão comercial, desenvolvida para centralizar o registro de vendas, o acompanhamento de clientes, o controle de metas e a simulação de comissões.

A plataforma organiza informações operacionais e as transforma em indicadores de desempenho (KPIs), facilitando o acompanhamento dos resultados e apoiando a tomada de decisão baseada em dados.

O projeto também representa uma aplicação prática de conhecimentos em desenvolvimento web, organização de dados e análise de desempenho comercial.

Acesse a aplicação: "control-com-bl.vercel.app" (https://control-com-bl.vercel.app/)

Repositório: "github.com/dvignali01-oss/ControlComBL" (https://github.com/dvignali01-oss/ControlComBL)

Problema e proposta de solução

A rotina comercial exige o acompanhamento constante de vendas, instalações, metas financeiras e comissões. Quando essas informações ficam dispersas, torna-se mais difícil monitorar resultados e identificar pendências.

O ControlComBL propõe reunir essas informações em uma única interface, simplificando o controle da operação e a visualização dos indicadores.

Desafio| Solução
Registros comerciais dispersos| Centralização das vendas cadastradas
Cálculos manuais| Totalização automática dos valores
Dificuldade de acompanhar instalações| Controle por status
Metas pouco visíveis| Indicadores de progresso
Controle de comissões| Cálculo e simulação por faixas
Falta de visão consolidada| Dashboard de desempenho

Funcionalidades

Dashboard de desempenho

Painel de indicadores para acompanhamento dos principais resultados comerciais:

- Total de vendas registradas.
- Ticket médio.
- Quantidade de vendas instaladas.
- Taxa de instalação.
- Ganhos garantidos e pendentes, conforme as regras do sistema.

Cadastro de vendas

Formulário para registrar e organizar informações comerciais:

- Dados dos clientes e contato via WhatsApp.
- Produtos comercializados: TV, internet, móvel e fixo.
- Quantidades e valores individuais.
- Cálculo do valor total da venda.
- Data e status da instalação.

Gestão da carteira de clientes

Área destinada ao acompanhamento dos registros comerciais:

- Listagem de clientes cadastrados.
- Pesquisa por nome.
- Consulta de valores, datas e status.
- Exclusão de registros.

Metas e comissões

Ferramentas para acompanhar o desempenho e estimar resultados:

- Monitoramento de metas financeiras e quantitativas.
- Visualização do progresso das metas.
- Cálculo de comissões conforme as faixas configuradas.
- Simulador de ganhos para diferentes volumes de instalações.

Ferramentas complementares

- Bloco de notas para anotações operacionais.
- Relatório de fechamento comercial.
- Interface adaptável a diferentes tamanhos de tela.

Indicadores de desempenho (KPIs)

O sistema reúne métricas que ajudam a compreender os resultados da operação.

Indicador| Finalidade
Total de vendas| Acompanhar o volume financeiro registrado
Ticket médio| Avaliar o valor médio por venda
Taxa de instalação| Medir a proporção de vendas instaladas
Ganhos garantidos| Acompanhar valores considerados confirmados pelas regras de comissão
Ganhos pendentes| Monitorar valores associados a vendas ainda pendentes

Exemplos de cálculo

Ticket médio

Valor total das vendas dividido pela quantidade de vendas consideradas no cálculo.

Taxa de instalação

Quantidade de vendas instaladas dividida pela quantidade total de vendas elegíveis, multiplicada por 100.

As fórmulas acima são referências conceituais. Os critérios de contagem e os cálculos devem corresponder à implementação efetiva da aplicação.

Tecnologias utilizadas

A documentação inicial do projeto indica as seguintes tecnologias:

- HTML5: estrutura da aplicação.
- CSS3 / Tailwind CSS: estilização e responsividade.
- React: construção da interface por componentes.
- Vite: ambiente de desenvolvimento e compilação.
- LocalStorage: armazenamento local de informações no navegador.
- Git e GitHub: controle de versão e gerenciamento do código.
- Vercel: hospedagem e publicação da aplicação.

Nota: confirme as tecnologias no código-fonte e no arquivo "package.json" antes de considerar esta lista definitiva.

Arquitetura da aplicação

O funcionamento pode ser organizado em três componentes principais:

1. Camada de apresentação

Interface responsável pela exibição de formulários, indicadores, registros de clientes e ferramentas comerciais.

2. Camada de lógica de negócio

Responsável pelo processamento dos valores, cálculo dos indicadores, acompanhamento de metas e simulação de comissões.

3. Camada de persistência

Utiliza o "LocalStorage" do navegador para armazenar dados localmente, conforme a implementação atual descrita do projeto.

Fluxo de processamento

Registro de vendas
       |
       v
Processamento das informações
       |
       v
Cálculo de indicadores e comissões
       |
       v
Apresentação dos resultados
       |
       v
Acompanhamento do desempenho

Armazenamento de dados

O "LocalStorage" permite manter informações no navegador entre sessões, mas não equivale a um banco de dados centralizado e não sincroniza automaticamente os registros entre diferentes dispositivos.

Por isso, o armazenamento local deve ser considerado uma limitação arquitetural a ser avaliada em futuras evoluções, especialmente se a aplicação passar a trabalhar com múltiplos usuários ou dados comerciais sensíveis.

Como executar localmente

Pré-requisitos

- Node.js compatível com as dependências do projeto.
- npm.
- Git.

1. Clonar o repositório

git clone https://github.com/dvignali01-oss/ControlComBL.git

2. Acessar a pasta

cd ControlComBL

3. Instalar as dependências

npm install

4. Iniciar o ambiente de desenvolvimento

npm run dev

Após a inicialização, acesse o endereço local apresentado no terminal. Em uma configuração padrão do Vite, ele costuma ser "http://localhost:5173".

5. Gerar a versão de produção

npm run build

Para executar a pré-visualização da versão compilada, caso o script esteja configurado:

npm run preview

Próximas evoluções

O projeto pode evoluir para uma solução analítica mais completa por meio de melhorias como:

- Visualização de dados: gráficos de evolução das vendas e comparação de metas.
- Análise temporal: acompanhamento do desempenho por dia, semana e mês.
- Qualidade dos dados: validação de entradas e prevenção de inconsistências.
- Exportação de dados: geração de arquivos CSV para análises externas.
- Persistência avançada: integração com banco de dados e sincronização entre dispositivos.
- Testes automatizados: validação dos cálculos e das principais funcionalidades.
- Segurança: implementação de mecanismos apropriados de autenticação, autorização e proteção de dados, conforme os requisitos do sistema.

Esses itens são propostas de evolução e não representam funcionalidades necessariamente disponíveis na versão atual.

Objetivos de aprendizagem

O desenvolvimento do ControlComBL proporciona experiência prática em:

- Desenvolvimento de aplicações web.
- Organização e manipulação de dados.
- Implementação de regras de negócio.
- Definição e interpretação de indicadores de desempenho.
- Visualização de informações para apoio à decisão.
- Versionamento de código e publicação de aplicações.

Licença

O projeto utiliza um selo de licença MIT na apresentação anterior. Antes de distribuir o código sob essa licença, confirme se o repositório contém um arquivo "LICENSE" com o texto correspondente.

---

ControlComBL — Gestão comercial orientada por dados.
