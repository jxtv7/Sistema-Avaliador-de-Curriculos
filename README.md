Sistema Avaliador de Currículo 🚀

Projeto de Back-end da graduação em ADS, desenvolvido em time com 3 integrantes:

Nome | Matrícula

Jennifer Dos Santos Santana Batista | 2023100043

Lucas Andrade da Silva | 2020102079

João Victor Cavalcante Lima de Sá | 2023101275

OBJETIVO:

Sistema web desenvolvido para análise automatizada de currículos com foco em aderência a vagas de emprego, inspirado nos ATS (Applicant Tracking Systems) utilizados por empresas em processos seletivos.

O projeto compara o currículo com a descrição da vaga, identificando:

compatibilidade entre perfil e requisitos; competências relevantes; gaps técnicos e profissionais; feedbacks automáticos orientados à melhoria do currículo. 🎯 Objetivo

Atualmente, plataformas de recrutamento utilizam sistemas automatizados para filtrar candidatos com base em:

palavras-chave; habilidades; aderência à vaga.

O problema é que candidatos normalmente não possuem visibilidade sobre:

como seus currículos estão sendo avaliados; quais competências estão faltando; quais pontos precisam melhorar; qual o nível real de compatibilidade com a vaga.

O Sistema Avaliador de Currículo foi criado para resolver esse problema através de uma análise estruturada, transparente e acessível.

✨ Funcionalidades 🔎 Análise Inteligente Extração dinâmica de competências; Parsing de currículo e vaga; Matching entre currículo e requisitos da vaga; Identificação de gaps técnicos. 📊 Classificação de Competências

O sistema classifica automaticamente:

habilidades;

ferramentas;

conhecimentos.

📈 Métricas e Scores

Cálculo de score do currículo;

Cálculo de compatibilidade com a vaga;

Análise estrutural do currículo;

Feedback automático estilo recrutador.

🖥️ Interface Web

Tela de inserção de currículo e vaga;

Tela de resultados da análise;

Visualização comparativa de competências.

🏗️ Tecnologias Utilizadas

Back-end

Python

Flask

Flask-CORS

Front-end

HTML5

CSS3

JavaScript

Processamento de Texto

Regex

NLP simplificado

Extração dinâmica de keywords

Normalização textual

📂 Estrutura do Projeto

project/ ├── routes/ ├── services/ ├── static/ ├── templates/ ├── app.py

⚙️ Principais Serviços

Serviço Responsabilidade

analysis_service Orquestra toda a análise

matching_service Calcula compatibilidade

classification_service Classifica competências

feedback_service Gera feedback automático

resume_parser_service Processa currículo

job_parser_service Processa vaga

resume_analyzer_service Calcula scores estruturais

📊 Regras de Negócio

O score final prioriza aderência à vaga;

Apenas competências relevantes são consideradas;

Stopwords são removidas automaticamente;

Competências são classificadas em categorias;

O sistema identifica gaps técnicos;

O feedback é gerado dinamicamente com base nos resultados da análise.

🚀 Como Executar

1️⃣ Clonar o repositório

git clone https://github.com/YoungAndrade/Sistema-Avaliador-de-Curriculos-

2️⃣ Instalar dependências

pip install -r requirements.txt

3️⃣ Executar aplicação

python app.py

4️⃣ Acessar no navegador

http://127.0.0.1:5000

📌 Futuras Evoluções

Upload de PDF/DOCX;

Dashboard estatístico;

Histórico de análises;

Exportação em PDF;

IA generativa para feedback avançado.
