# Registro de decisões metodológicas

Este documento registra decisões metodológicas relevantes do projeto, incluindo mudanças posteriores ao pré-projeto. O objetivo é preservar a rastreabilidade das escolhas e evitar reconstruções retrospectivas do desenho da pesquisa.

## Situação de referência

Versão-base: pré-projeto entregue em 2 de novembro de 2026.

Título da versão entregue:

> **Acurácia e cobertura de LLMs sobre países da CPLP e implicações para a Administração Pública**

As formulações abaixo permanecem sujeitas a revisão após orientação, aprofundamento da literatura, piloto e qualificação.

## Decisões registradas

### 1. Recorte empírico

O recorte inicial compreende os nove Estados-membros da Comunidade dos Países de Língua Portuguesa (CPLP):

- Angola
- Brasil
- Cabo Verde
- Guiné-Bissau
- Guiné Equatorial
- Moçambique
- Portugal
- São Tomé e Príncipe
- Timor-Leste

A CPLP funciona como recorte empírico comparativo, não como amostra probabilística de países do mundo.

### 2. Unidade de análise

A unidade primária proposta é cada resposta gerada para uma combinação de:

- modelo;
- país;
- tarefa;
- repetição.

Afirmações factuais e elementos requeridos funcionam como unidades internas de codificação.

### 3. Coleta principal

A coleta principal está prevista por API, em condições registradas e parcialmente controladas.

A etapa em chatbots públicos gratuitos é complementar e de menor escala. Seu objetivo é examinar se padrões observados na coleta controlada também aparecem em interfaces de uso comum. Essa etapa não é tratada como experimento causal de efeito da interface.

### 4. Desfechos principais

Os dois desfechos centrais propostos são:

- **acurácia factual**: proporção de afirmações verificáveis corretas entre as afirmações verificáveis produzidas;
- **cobertura correta**: proporção de elementos solicitados atendidos corretamente em relação aos elementos previamente requeridos na tarefa.

Erro, omissão, abstenção, conteúdo não verificável e falha técnica devem permanecer distinguíveis.

### 5. Interpretação de diferenças

Diferenças entre países ou modelos não serão tratadas automaticamente como evidência de viés.

Termos como viés, estereótipo, alinhamento cultural, diferença de desempenho, erro factual e cobertura designam fenômenos distintos e exigem critérios próprios.

### 6. Relação com o artigo sobre CPLP

O artigo relacionado permanece independente da dissertação. Poderá servir como estudo exploratório, piloto, antecedente metodológico ou fonte de instrumentos, desde que haja compatibilidade entre os desenhos. A dissertação não depende da submissão ou aceitação do artigo.

## Próximas decisões a documentar

- seleção final dos modelos e endpoints;
- número definitivo de tarefas por país;
- critérios de equivalência entre tarefas;
- composição e validação dos gabaritos;
- definição final das repetições e parâmetros de geração;
- procedimento de segunda codificação;
- análise de concordância entre avaliadores;
- estratégia quantitativa após o piloto;
- critérios de seleção dos casos para análise qualitativa;
- mudanças decorrentes da qualificação.

---

**Regra de registro:** mudanças relevantes devem indicar data, decisão, justificativa e impacto sobre o desenho.
