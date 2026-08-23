<h1 align="center">Thiago Lopes</h1>

<p align="center">
  <strong>Legal Engineer · Advogado empresarial · Gestor de processos</strong><br>
  Diagnostico, construo e implanto os sistemas que resolvo
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

Entre quem entende o risco jurídico e quem escreve o código, quase sempre existe um tradutor.

**Comigo não existe — eu sou os dois.**

É isso que significa **Legal Engineer**: o profissional que entende a norma, o contrato e o processo, e que constrói o sistema que resolve — sem precisar de intérprete entre uma coisa e outra. Lá fora já é cargo; aqui ainda é raro.

Sou advogado empresarial e gestor de processos e pessoas. Lido com contrato, risco trabalhista, proteção de patrimônio e operação que trava. E, em vez de apontar o problema e ir embora, construo a solução, coloco para rodar e fico para ajustar.

---

## O ciclo que eu entrego

```
ESTUDO        →  DESENHO       →  CONSTRUÇÃO   →  IMPLANTAÇÃO  →  ACOMPANHAMENTO

Entendo o        Projeto o        Escrevo o       Coloco para     Meço, reviso
setor e onde     fluxo antes      sistema sob     rodar com as    e corrijo
mora o risco     da ferramenta    medida          pessoas usando
```

Consultoria entrega diagnóstico e vai embora. Fábrica de software entrega código e vai embora. **Eu fico.**

---

## O que sustenta isso

Este perfil não é vitrine de tutorial. Cada repositório prova uma coisa diferente, com número aferido e método aberto.

### [poda](https://github.com/thiagolopes-ai/poda) · [poda.digital](https://poda.digital)

Produto em operação: recebe URL ou PDF pelo WhatsApp e devolve Markdown limpo, pronto para um modelo de linguagem. Domínio próprio, cobrança por PIX, planos e limites, rate limiter em Redis, monitoramento de erro.

**Redução de 81,3% no custo de contexto**, medida em 9 páginas de tipos diferentes, com o script de medição aberto no repositório.

> Prova que eu levo do zero à operação comercial — não paro no protótipo.

### [classificador-juridico](https://github.com/thiagolopes-ai/classificador-juridico)

Classificação de texto jurídico em 17 áreas do direito, sobre 10.594 artigos reais. **78,5% de acurácia contra uma linha de base de 13,3%**, com análise de vazamento por duplicata e ablação de entrada.

Documenta também um experimento com dados sintéticos que **falhou**, e explica por quê.

> Prova que eu meço, e que meço honestamente. Quem só publica acerto está escondendo o método.

### [rag-juridico](https://github.com/thiagolopes-ai/rag-juridico)

Pergunta em linguagem de leigo respondida sobre LGPD, CDC e CLT, **sempre com o artigo citado**. Recuperação avaliada contra gabarito de 40 perguntas.

Mostra que segmentar pela estrutura da lei rende mais que trocar de modelo, e que o limiar de similaridade — o guard-rail mais comum de RAG — não separa pergunta respondível de impossível.

> Prova que eu avalio sistema de IA com método, em vez de confiar na impressão de que está funcionando.

### [trilha-ia](https://github.com/thiagolopes-ai/trilha-ia)

Camada de auditoria para decisões apoiadas por IA: confere frase a frase se a resposta está sustentada pelas fontes, cifra o conteúdo em repouso e manda para revisão humana o que o art. 20 da LGPD torna revisável.

**F1 de 0,971 na detecção de invenção, com recall de 1,00** sobre 36 respostas rotuladas à mão — contra 0,641 de uma linha de base que acusa tudo. API em FastAPI, Docker e 32 testes.

Documenta o caso em que o detector acusou uma resposta e **o errado era o meu gabarito**, não o método.

> Prova que eu fecho a etapa de implantação, e que governança de IA aqui é código medido, não slide.

### [escala-clt](https://github.com/thiagolopes-ai/escala-clt)

Escala de postos de trabalho gerada por programação por restrições, com 12x36, interjornada, repouso semanal e habilitação de posto como restrição dura — cada regra com o artigo citado no código.

**R$ 61.670 por mês mais barata** que a escala manual conforme, com **zero infrações** e ótimo provado em 8 segundos. Estável entre 18,3% e 24,6% de economia em cinco cenários independentes.

E entrega o que o gestor precisa antes da escala: **onde falta gente de verdade**. No cenário de referência, contratar mais vigilante — o instinto óbvio — aumenta a folha e não cobre um turno sequer.

> Prova que eu resolvo o problema que eu vivi comandando a operação, e que jurídico e engenharia cabem no mesmo arquivo.

---

## O que não está aqui

Boa parte do que eu construo é feita sob contrato, para a operação de uma empresa específica. Esse código não me pertence, roda dentro da casa do cliente e com o dado dele — então não vai para repositório público. Confidencialidade e titularidade não são detalhe: são parte do serviço.

O que está neste perfil é o que eu posso abrir. São os projetos em que eu escolhi o problema, defini o método e publiquei o número. Eles existem para mostrar **como** eu trabalho, não para inventariar **quanto** eu já entreguei.

O restante eu apresento em conversa, no nível de detalhe que o contrato permite.

---

## Como eu trabalho

| Princípio | Na prática |
|---|---|
| **Métrica antes do código** | Defino como vou saber que funcionou antes de começar. Sem isso, todo sistema "funciona" |
| **O fluxo vem antes da ferramenta** | Automatizar processo ruim só acelera o erro |
| **Conformidade no desenho, não depois** | No `poda`, CPF e CNPJ ficam criptografados em repouso, com o art. 46 da LGPD citado no comentário do código |
| **Decisão documentada** | Todo repositório tem uma tabela do que escolhi, contra o que, e por quê |
| **O que deu errado também é publicado** | Erro documentado é o que separa método de sorte |
| **Auditabilidade** | Em domínio jurídico, sistema que decide sem justificar não passa por revisão nenhuma |

---

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![HuggingFace](https://img.shields.io/badge/sentence--transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white)

E o que não cabe em badge: direito empresarial, LGPD, gestão de risco, desenho de processo e treinamento de equipe.

---

## Para conversar

Se a sua empresa tem um processo que trava, um risco que ninguém mapeou ou uma operação que depende da memória de uma pessoa só — é exatamente esse o tipo de problema que eu resolvo.

[LinkedIn](https://www.linkedin.com/in/tiagolopes-gerentegeral/) · [e-mail](mailto:thiago.lop.adv@gmail.com)
