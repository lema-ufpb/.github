<div align="center">

<img src="https://avatars.githubusercontent.com/u/202003493?v=4" width="112" alt="LEMA-UFPB" />

# LEMA · UFPB
### Laboratório de Estudos em Modelagem Aplicada

**Transformamos dados públicos brutos em conhecimento aplicado — e conhecimento em decisão.**

[![Website](https://img.shields.io/badge/site-lema.ufpb.br-e38a05?style=for-the-badge&logo=googlechrome&logoColor=white)](https://lema.ufpb.br)
[![UFPB](https://img.shields.io/badge/Universidade%20Federal%20da%20Para%C3%ADba-002856?style=for-the-badge)](https://www.ufpb.br)
[![Status](https://img.shields.io/badge/status-ativo-brightgreen?style=for-the-badge)](https://github.com/lema-ufpb)

</div>

<br/>

## Quem somos

O **LEMA** é o Laboratório de Estudos em Modelagem Aplicada da **UFPB**. Reunimos pesquisadores, professores e estudantes em torno de um propósito direto: pegar os dados públicos que o Brasil já produz em volume — saúde, educação, energia, meio ambiente — e transformá-los em pipelines confiáveis, indicadores acessíveis e ferramentas que sustentam decisões reais.

Não fazemos data engineering como exercício acadêmico. Fazemos porque cada ETL que sobe em produção alimenta um painel que alguém usa para planejar uma política pública.

<br/>

## Da fonte pública ao impacto

```mermaid
flowchart LR
    subgraph Fontes["📥 Dados públicos"]
        direction TB
        A1[DATASUS]
        A2[INEP · CAPES · CNPq]
        A3[ANEEL · ANATEL]
        A4[MapBiomas]
    end

    subgraph Pipeline["⚙️ Arquitetura Medallion"]
        direction TB
        B1["🥉 Bronze — ingestão"]
        B2["🥈 Silver — limpeza & modelagem"]
        B3["🥇 Gold — indicadores prontos"]
        B1 --> B2 --> B3
    end

    subgraph Produtos["🚀 Impacto"]
        direction TB
        C1["SIDTEC — Inteligência de C&T da Paraíba"]
        C2["ODS Racial — equidade racial orientada a dados"]
        C3["SAEGO — acompanhamento de egressos"]
        C4["Painéis Power BI"]
    end

    A1 & A2 & A3 & A4 --> B1
    B3 --> C1 & C2 & C3 & C4
```

Cada seta acima é um repositório de verdade rodando em produção — não um diagrama de intenções.

<br/>

## Linhas de atuação

| Área | O que construímos | Projetos |
|---|---|---|
| 🏥 **Saúde pública** | Pipelines para dados do DATASUS: mortalidade, natalidade, vigilância sanitária, rede hospitalar e ambulatorial | `etl-datasus-*` |
| 🎓 **Educação** | Orquestração de dados do INEP, CAPES e CNPq — do Censo Escolar ao fluxo da pós-graduação | `etl-inep-*` · `etl-capes-sucupira` · `etl-cnpq-bolsas` |
| ⚡ **Energia & telecom** | Indicadores de geração de energia e de densidade de banda larga/móvel no país | `etl-aneel-potencia` · `etl-anatel-densidade-internet` |
| 🌱 **Meio ambiente** | Uso e cobertura do solo a partir de dados do MapBiomas | `etl-mapbiomas-solo` |
| ⚖️ **Impacto social** | Aplicação e API dedicadas ao acompanhamento dos ODS sob a ótica racial | `app-odsr` · `api-odsr` |
| 🎓 **Gestão acadêmica** | Sistemas de acompanhamento de egressos da graduação e pós-graduação | `app-saego` · `app-saego-pos` · `app-saego-sebtt` |
| 🔎 **Inteligência de C&T** | Sistema de inteligência de dados de Ciência e Tecnologia da Paraíba | `app-sidtec` |

<br/>

## Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![ArgoCD](https://img.shields.io/badge/Argo%20CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

</div>

Por trás dos pipelines, mantemos nossa própria infraestrutura: deploy híbrido em Kubernetes/ArgoCD e Docker/Portainer, provisionamento via Ansible e conectividade segura via Twingate. Engenharia de dados de ponta a ponta, do dado bruto à infra que o sustenta.

<br/>

## Como contribuir

- 🍴 Faça um fork de um repositório e abra um Pull Request
- 🐛 Relate problemas ou sugira melhorias nas Issues
- 🤝 Entre em contato para propostas de pesquisa ou parceria

<br/>

## Conecte-se

🌍 **Site:** [lema.ufpb.br](https://lema.ufpb.br)
🏛️ **Instituição:** Universidade Federal da Paraíba

<br/>

<div align="center">

_"Do dado bruto ao ouro: transformamos informação pública em conhecimento aplicado à sociedade."_ ⭐

</div>
