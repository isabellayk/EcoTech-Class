# 🌱 EcoTech Class

O **EcoTech Class** é uma plataforma que incentiva o descarte correto de resíduos eletrônicos por meio da educação ambiental e da gamificação.

A proposta é transformar escolas e instituições de ensino em pontos de coleta de lixo eletrônico, incentivando estudantes e a comunidade a participarem de ações sustentáveis.

## 🎯 Objetivo do projeto

Promover a conscientização ambiental e estimular o descarte adequado de resíduos eletrônicos, tornando a sustentabilidade uma atividade participativa e colaborativa dentro das instituições de ensino.

## 💡 Funcionalidades

- **Página inicial:** apresentação do projeto, dos materiais aceitos e da proposta de sustentabilidade.
- **Cadastro e login integrados à API:** criação de contas para estudantes (com seleção de turma) e instituições, com autenticação persistida no navegador (`localStorage`).
- **Controle de acesso e rotas protegidas:** bloqueio de navegação não autorizada, garantindo que estudantes acessem apenas seu painel e que o painel administrativo seja exclusivo da instituição.
- **Painel do estudante:** acompanhamento em tempo real de pontos acumulados, peso total entregue, histórico individual de doações e posição no ranking da própria turma.
- **Painel administrativo (CRUD completo):** gerenciamento das coletas de resíduos eletrônicos (registrar, listar, editar e excluir doações), além de indicadores gerais e ranking entre turmas.
- **Tema claro e escuro:** opção de personalização da aparência da plataforma, com preferência salva no navegador.
- **Gamificação:** incentivo à participação por meio de pontos e rankings dinâmicos calculados a partir das entregas registradas.

## 🛠️ Tecnologias utilizadas

- React
- Vite
- JavaScript
- Tailwind CSS
- React Router DOM
- MockAPI.io (API REST)
- HTML5
- CSS3

## 📁 Estrutura do projeto

O projeto está organizado em páginas, componentes, hooks, serviços e arquivos de dados, buscando manter o código limpo e facilitar sua manutenção.

- `components/`: componentes reutilizáveis da interface e controle de rotas protegidas.
- `pages/`: páginas da plataforma (Início, Login, Cadastro, Dashboard e Painel Administrativo).
- `hooks/`: lógica reutilizável por meio de Hooks e Custom Hooks.
- `services/`: integração centralizada com a API REST (`api.js`).
- `data/`: informações utilizadas na apresentação dos conteúdos.
- `assets/`: imagens e outros recursos visuais.

## 👩‍💻 Integrantes

| Nome | RM |
|---|---:|
| Eduarda Soares Moraes | 569369 |
| Isabella Yogui Kohara | 569777 |
| Julia Souza Matarazzo | 571340 |
| Marcella Pinheiro Silva | 569457 |
| Mariana Malagutti Gomes Peixoto | 570290 |

## 🔗 Repositório GitHub

[EcoTech Class — GitHub](https://github.com/isabellayk/EcoTech-Class.git)

## ▶️ Como executar o projeto

1. Clone este repositório:

   ```bash
   git clone https://github.com/isabellayk/EcoTech-Class.git
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd EcoTech-Class
   ```

3. Instale as dependências:

   ```bash
   npm install
   ```

4. Inicie o servidor de desenvolvimento:

   ```bash
   npm run dev
   ```

5. Acesse o endereço disponibilizado no terminal, geralmente `http://localhost:5173`.

## 🌎 Sustentabilidade

O EcoTech Class está alinhado aos Objetivos de Desenvolvimento Sustentável (ODS), especialmente:

- **ODS 4 – Educação de Qualidade**
- **ODS 9 – Indústria, Inovação e Infraestrutura**
- **ODS 11 – Cidades e Comunidades Sustentáveis**
- **ODS 13 – Ação Contra a Mudança Global do Clima**

---

| Campo | Descrição |
| :--- | :--- |
| **Nome da CitizenTech** | EcoTech Class |
| **Cidade e bairro** | São Paulo (SP) |
| **Cidadão beneficiado** | Estudantes, famílias, moradores de periferias/baixa renda, catadores e comunidades próximas a áreas de descarte irregular |
| **Problema, em uma frase** | O descarte incorreto e a falta de pontos de coleta acessíveis para lixo eletrônico em São Paulo geram graves riscos ambientais e sociais. |
| **Como funciona** | Plataforma web e mobile que transforma escolas em pontos comunitários de coleta de e-lixo, registrando o peso dos descartes por meio de QR Code para gerar pontos, rankings e prêmios. |
| **O que cada parte faz** | • **Plataforma:** gerencia cadastros, pesos, pontuações, relatórios e alertas;<br>• **Escolas:** organizam as campanhas e pontos de coleta;<br>• **Alunos e comunidade:** descartam os aparelhos;<br>• **Parceiros/cooperativas:** realizam o transporte, a reciclagem física e a emissão dos certificados. |
| **Link do repositório** | https://github.com/isabellayk/EcoTech-Class.git |
| **Indicador de impacto** | Estimativa de CO₂ evitado (metodologia ACV / EPA WARM) e volume em quilogramas (kg) de lixo eletrônico arrecadado e destinado corretamente. |
| **ODS conectados** | ODS 4 (Educação de Qualidade), ODS 9 (Indústria, Inovação e Infraestrutura), ODS 11 (Cidades e Comunidades Sustentáveis) e ODS 13 (Ação contra a Mudança Global do Clima). |

---

**EcoTech Class — Pequenas atitudes, grandes transformações.**