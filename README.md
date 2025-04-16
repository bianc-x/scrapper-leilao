# 🔍 Web Scraper para Leilões Online (Em Desenvolvimento)

Este projeto tem como objetivo a criação de um **web scraper** para coletar automaticamente informações sobre **leilões de bens** (como imóveis e veículos) disponíveis em sites especializados. A aplicação busca extrair dados relevantes, organizá-los em um formato estruturado e permitir análises futuras para oportunidades de investimento ou pesquisa de mercado.

---

## 🚧 Status do Projeto

📌 **Em andamento** – Algumas funcionalidades já foram implementadas, mas o sistema está em constante evolução e melhorias estão sendo adicionadas gradualmente.

---

## ✅ Funcionalidades já implementadas

- 🔗 **Coleta de anúncios abertos** em um site específico de leilões.
- 📄 **Extração de dados estruturados** como: título do item, valor inicial, status, data do leilão, link para o anúncio.
- 📦 **Exportação para CSV** dos dados coletados.
- 🧹 **Limpeza e padronização básica dos dados** (remoção de caracteres indesejados, formatação de números e datas).
- ⏱️ Execução rápida e simples por script Python.

---

## 🧠 Tecnologias Utilizadas

- **Python 3**
- **BeautifulSoup** – para parsing do HTML.
- **Requests** – para acesso às páginas e envio de requisições.
- **Pandas** – para manipulação e exportação dos dados.
- **re (Regex)** – para extrações pontuais e tratamento de strings.

---

## 🧭 Próximos Passos

- 🔄 Tornar o código escalável para **vários sites de leilões**.
- ⚙️ Implementar lógica de agendamento ou execução recorrente.
- 🛑 Tratar páginas com **JavaScript dinâmico** (com Selenium, se necessário).
- 🔒 Adicionar sistema de tratamento de erros e logs.
- 🗄️ Criar integração com banco de dados para armazenar dados históricos.

---

## ✍️ Sobre o Projeto

Este é um projeto pessoal em andamento, com o objetivo de desenvolver soluções de raspagem de dados voltadas para **oportunidades de negócios e automação de coleta de informações públicas**. Pretendo evoluir o scraper para um sistema completo de monitoramento e análise de leilões.
