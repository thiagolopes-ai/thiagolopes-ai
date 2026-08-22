<h1 align="center">Thiago Lopes</h1>

<p align="center">
  <strong>Estudante de Inteligência Artificial</strong><br>
  Construindo sistemas que aplicam LLMs e machine learning a problemas reais de documentos.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/tiagolopes-gerentegeral/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:thiago.lop.adv@gmail.com">
    <img src="https://img.shields.io/badge/E--mail-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="E-mail">
  </a>
</p>

---

## Sobre

Venho da área jurídica e migrei para Inteligência Artificial trazendo comigo o que aprendi lá: ler grandes volumes de texto, extrair o que importa e transformar isso em decisão. Hoje aplico o mesmo raciocínio construindo software.

Meu foco está em **documentos**: extrair, classificar e recuperar informação em textos longos e mal formatados — o problema que mais aparece no dia a dia de empresas e o que menos aparece em tutorial.

Em todo projeto aqui eu meço o resultado e publico o que não funcionou junto com o que funcionou.

- Estudando: recuperação de informação, avaliação de saídas de modelos e engenharia de contexto
- Interesse: automação de processos documentais com IA
- Aberto a: estágio, júnior e projetos colaborativos

---

## Stack

**Linguagens e base**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Dados e machine learning**

![Pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

**IA generativa e recuperação**

![Anthropic](https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
![HuggingFace](https://img.shields.io/badge/sentence--transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**Aplicação e entrega**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)

---

## Projetos

### [poda](https://github.com/thiagolopes-ai/poda) · [poda.digital](https://poda.digital)

Otimizador de tokens via WhatsApp. Recebe URLs e PDFs e devolve Markdown limpo. Medido em 9 páginas de tipos diferentes: **81,3% de redução de tokens**, com benchmark reproduzível no repositório.

`Python` · `FastAPI` · `LLM` · `Processamento de documentos`

### [classificador-juridico](https://github.com/thiagolopes-ai/classificador-juridico)

Classificação de textos jurídicos em 17 áreas do direito sobre 10.594 artigos reais. **78,5% de acurácia** contra baseline de 13,3%, com análise de vazamento por duplicata e ablação de entrada. Documenta também um experimento com dados sintéticos que falhou, e por quê.

`Python` · `scikit-learn` · `NLP` · `Classificação de texto`

### [rag-juridico](https://github.com/thiagolopes-ai/rag-juridico)

Perguntas em linguagem coloquial respondidas sobre LGPD, CDC e CLT, com o artigo citado. Recuperação medida contra gabarito de 40 perguntas: **recall@5 de 0,57**. Mostra que segmentar por artigo vale mais que trocar de modelo, e que o limiar de similaridade — guard-rail mais comum de RAG — não separa pergunta respondível de impossível.

`Python` · `sentence-transformers` · `RAG` · `Recuperação de informação`

---

## Contato

Se você está avaliando meu perfil para uma vaga ou quer trocar ideia sobre IA aplicada a documentos, me chame no [LinkedIn](https://www.linkedin.com/in/tiagolopes-gerentegeral/) ou por [e-mail](mailto:thiago.lop.adv@gmail.com).
