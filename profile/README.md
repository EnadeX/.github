<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/enadex-banner-negativo.svg">
    <img src="assets/enadex-banner.svg" alt="EnadeX" width="420">
  </picture>
</p>

<p align="center"><strong>ENADE eXplainability Framework</strong></p>

Arquitetura integrada de **mineração de dados, explicabilidade e Visual Analytics** para explorar os microdados do ENADE (INEP).

Os microdados do ENADE costumam ser pouco aproveitados por três motivos: as análises são fragmentadas, difíceis de reproduzir e não há ambientes interativos e interpretáveis para explorá-los. O EnadeX enfrenta esses problemas com um ecossistema de quatro TCCs interligados. Eles seguem a metodologia **Design Science Research** e compartilham o ETL, a harmonização de variáveis, as métricas e a API.

## Subprojetos

| Projeto | Foco |
|---|---|
| **MultiENADE** | Descoberta multidimensional: regressão (Random Forest), clusterização (K-Means), regras de associação (Apriori) e SHAP |
| **E-XplainENADE** | Modelagem estatística explicável e reproduzível: engine de regressão configurável, VIF, SHAP e relatórios automáticos |
| **EduCluster** | Perfis acadêmicos latentes: K-Means/Hierárquica, PCA/UMAP e dashboard interativo |
| **ENADE-Time** | Análise temporal de 2005 a 2021: harmonização entre ciclos, intervalos de confiança, tendências (LOESS) e séries temporais |

## Repositórios

- **`EnadeX_Backend`**: API em Python, com um módulo por subprojeto
- **`EnadeX_Frontend`**: site em Next.js, com uma rota por subprojeto
- **`EnadeX_Documentacao`**: proposta, entregáveis, artigos, diagramas e resultados de cada subprojeto
