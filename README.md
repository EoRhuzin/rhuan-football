# 📘 Rhuan Football – Bot de Inteligência Artificial para Análise de Apostas Esportivas

## 🎯 Introdução
O Rhuan Football é um projeto de automação e inteligência artificial voltado para o mercado de apostas esportivas. A proposta é desenvolver um bot inteligente que receba comandos via Telegram, consulte dados reais de partidas de futebol através de APIs externas, analise as informações com auxílio de IA e sugira as melhores apostas do dia com base em valor esperado.

Criado com foco em praticidade, inovação e acessibilidade, o bot é uma solução útil tanto para apostadores iniciantes quanto experientes.

## 🛠️ Tecnologias Utilizadas
- **Make.com (Integromat)** – Plataforma de automação responsável por orquestrar todas as etapas do fluxo.
- **Telegram Bot API** – Para interagir com os usuários via comandos e respostas.
- **PiAPI (baseada em GPT)** – Para gerar análises de apostas a partir dos dados do jogo.
- **Football-Data.org** – API usada para obter dados oficiais sobre jogos, ligas e times de futebol.
- **JavaScript + JSON** – Manipulação de dados no Make.com e formatação de mensagens.
- **Design** – Criação de interface visual, logo, e cards de apoio para divulgação e apresentação.

## 🔗 APIs Utilizadas
1. **Football-Data.org**
   - Fornece dados oficiais de jogos, competições e resultados.
   - Utilizada para obter partidas da La Liga, Premier League, Champions League, etc.
   - Endpoint de partidas e detalhes da partida por ID.

2. **PiAPI (IA via DeepSeek Reasoner)**
   - Ferramenta de inteligência artificial para interpretar os dados do jogo.
   - Gera sugestões de apostas com base na análise de forma recente, histórico, escalações e mais.

## 🧠 Objetivo do Projeto
- Automatizar o processo de análise de jogos para apostas esportivas.
- Fornecer recomendações objetivas e baseadas em dados.
- Criar uma experiência de usuário fluida via Telegram.
- Servir como projeto de portfólio demonstrando domínio em automação, APIs e IA.

## 🧩 Como Funciona (Passo a Passo)
1. Usuário envia comando `/jogos DATA` no Telegram.
   - Exemplo: `/jogos CL 29-04-2025`
2. O bot busca os jogos da Champions League no dia 29/04/2025 via Football-Data.org.
3. Retorna as partidas com data, horário e ID.
4. Usuário escolhe uma partida e envia `/analisar ID_PARTIDA`.
5. O Make.com consulta os dados detalhados do jogo (times, competição, etc.).
6. Envia o contexto para a IA (via PiAPI) com um prompt estruturado.
7. A IA responde com sugestões de apostas SIMPLES e COMBINADAS.
8. A resposta da IA é formatada e enviada ao Telegram.

**Exemplo de mensagem**:

Segundo as análises de Rhuan, essas são as melhores apostas:

💡 Sugestões SIMPLES: 1- Vitória do São Paulo 2- Under 2.5 gols

💡 Sugestões COMBINADAS: 1- São Paulo vencer + Under 2.5 gols



## ✅ Pontos Positivos
- 🤖 **Totalmente automatizado com IA**.
- ⚽ **Baseado em dados reais e atualizados**.
- 📲 **Acessível direto pelo Telegram (PC ou celular)**.
- 🧠 **IA treinada para sugerir apostas com valor esperado positivo**.
- 💼 **Ideal para portfólio profissional**.

## ❌ Pontos Negativos
- Depende da disponibilidade da **Football-Data.org** (limite diário de requisições).
- Sugestões da IA podem variar com base em contexto limitado (dependência do prompt).
- Ainda não possui **painel visual** (Dashboard).

## 📈 Possíveis Melhorias Futuras
- Adicionar suporte a múltiplas ligas no mesmo comando.
- Criar histórico de apostas sugeridas e resultados.
- Incluir filtros de odds e mercados favoritos.
- **Dashboard** visual com estatísticas dos jogos analisados.

## 👨‍💻 Conclusão
O Rhuan Football é mais do que um simples bot – é um assistente de apostas com inteligência artificial que reflete o poder da automação integrada com APIs modernas. Este projeto demonstra minha habilidade de integrar múltiplas tecnologias, estruturar fluxos de dados inteligentes, lidar com APIs complexas e criar interfaces de uso acessíveis.

Desenvolvido por Rhuan de Oliveira Costa – com paixão por futebol, dados e IA ⚽💡
