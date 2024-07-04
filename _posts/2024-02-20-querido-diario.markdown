---
layout: post
title: Evolução do Querido Diário
date: 2024-04-24 13:32:20 +0700
description: Evolução do Querido Diário
img: https://raw.githubusercontent.com/ResidenciaTICBrisa/T2G4-Querido-Diario/main/docs/imagens/mascote.webp
fig-caption: # Add figcaption (optional)
tags: [transparencia, python, diario oficial, fastapi, typescript, angular, s3, elasticsearch]
comments: false
---

Onde conseguimos encontrar a maior parte dos dados relacionados às atividades municipais? No Diário Oficial.

Com 5570 municípios no país, perfis como jornalistas, acadêmicos, ativistas e gestores públicos que desejem acompanhar as publicações de vários municípios para realização de matérias, estudos e tomadas de decisão, tem seu trabalho muito limitado, pois cada município publica seus diários oficiais da sua própria maneira e normalmente utilizando formatos fechados.

O Querido Diário (https://queridodiario.ok.org.br/) é um projeto de código aberto que busca solucionar esta situação raspando, processando e disponibilizando os diários oficiais dos municípios brasileiros de forma centralizada e utilizando padrões abertos de publicação. Hoje, o projeto permite acessar as informações publicadas nos diários oficiais de mais de 350 municípios por meio da pesquisa em sua plataforma web e também em API pública (https://queridodiario.ok.org.br/api/docs).

Porém, ainda há muita oportunidade de melhoria na forma de publicação dos diários para atender casos de uso comuns. Neste projeto propomos o desenvolvimento de rotinas de processamento de dados, criação de pontos de acesso na API e desenvolvimento de interfaces na plataforma web para atender o deseolvimento das novas funcionalidades a seguir:

Com estes cenários solucionados, o Querido Diário será uma ferramenta ainda mais poderosa para enfrentamento ao deserto de dados governamentais municipais.

**Novas funcionalidades esperadas:**
1. Funcionalidade de download de resultados de busca no “Querido Diário” (https://queridodiario.ok.org.br/) e “Querido Diário: Tecnologias na Educação” (https://queridodiario.ok.org.br/educacao) desenvolvida na interface da plataforma web;
   - Como jornalista, quero poder baixar os resultados da minha busca na plataforma web do Querido Diário para sistematizar o processo de apuração de reportagens;
   - Como pesquisadora, quero poder baixar os textos completos dos diários oficiais para realizar meus próprios recortes e processamentos de forma transversal.
2. Desenvolvimento de rotina de agregação e compactação de arquivos de diários (em seu formato textual) em recortes geográficos e cronológicos (unidade federativa, município, ano, mês e dia) para disponibilização em sistema de arquivos em nuvem para download;
3. Ponto de acesso na API do Querido Diário (https://queridodiario.ok.org.br/api/docs) para listagem de URLs de arquivos de diários agregados e compactados disponíveis para download pelos recortes geográficos e cronológicos desejados;
4. Página na plataforma web do projeto para download de diários oficiais em formato agregado e compactado pelos recortes geográficos e cronológicos desejados.

**Tamanho do projeto:** Médio

**Dificuldade:** Grande

## Roadmap

<iframe width="768" height="432" src="https://miro.com/app/live-embed/uXjVOlm4vs8=/?moveToViewport=-470,-3363,6023,2733&embedId=592248376332" frameborder="0" scrolling="no" allow="fullscreen; clipboard-read; clipboard-write" allowfullscreen></iframe>
<a href="https://miro.com/app/board/uXjVOlm4vs8=/?moveToViewport=-470,-3363,6023,2733&embedId=592248376332" target="_blank" rel="noopener">Roadmap | Querido Diário</a>

## Habilidades necessárias/preferenciais  
- Python
- FastAPI
- Typescript
- Angular
- Sistemas de arquivos s3-like (Digital Ocean Spaces)
- Elasticsearch/Opensearch

## Mentores
- Giulio Carvalho, Open Knowledge Brasil

## Repositórios da Equipe

- O site do Querido Diário é dividido em [Backend](https://github.com/Wildemberg-Projects/querido-diario-frontend) e [Frontend](https://github.com/Wildemberg-Projects/querido-diario-backend).
- [API do Querido Diário](https://github.com/Wildemberg-Projects/querido-diario-api).
- [Data Processing](https://github.com/Wildemberg-Projects/querido-diario-data-processing).

## Equipe 

|                                    Foto                                    |       Nome       |                                Github                                 |
| :------------------------------------------------------------------------: | :--------------: | :-------------------------------------------------------------------: |
| <img src="https://github.com/ArthurFerreiraRodrigues.png" width="150px" /> | Arthur Ferreira  | [ArthurFerreiraRodrigues](https://github.com/ArthurFerreiraRodrigues) |
|       <img src="https://github.com/csafurtado.png" width="150px" />        | Cristian Furtado |              [csafurtado](https://github.com/csafurtado)              |
|       <img src="https://github.com/esteerlino.png" width="150px" />        |    Ester Lino    |              [esteerlino](https://github.com/esteerlino)              |
|       <img src="https://github.com/pkbceira03.png" width="150px" />        | Pedro Cabeceira  |              [pkbceira03](https://github.com/pkbceira03)              |
|    <img src="https://github.com/raissamsoliveira.png" width="150px" />     | Raissa Oliveira  |        [raissamsoliveira](https://github.com/raissamsoliveira)        |
|    <img src="https://github.com/wildemberg-sales.png" width="150px" />     | Wildemberg Sales |        [wildemberg-sales](https://github.com/wildemberg-sales)        |
