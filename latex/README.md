# Estrutura LaTeX da dissertação

A estrutura deste diretório foi criada em 3 de novembro de 2026 a partir do template institucional Universidade IDP 2026 e do manual institucional vigente.

O arquivo principal é main.tex, localizado na raiz do repositório.

## Estrutura

- config.tex — tipografia, margens, espaçamento, hiperlinks e bibliografia;
- dados.tex — metadados centrais da dissertação;
- pretextuais/ — capa, folha de rosto, folha de aprovação, resumo, abstract e listas;
- capitulos/ — capítulos textuais separados;
- apendices/ — materiais produzidos pela autora.

A bibliografia é lida de referencias/referencias.bib.

Esse arquivo é exportado do Zotero por Better BibTeX.

## Compilação

Compilador recomendado: LuaLaTeX, com Biber para a bibliografia.

A configuração tenta usar Times New Roman quando a fonte estiver disponível. Em ambientes sem essa fonte, utiliza TeX Gyre Termes como alternativa.

## Normalização

A estrutura busca reproduzir o padrão visual e estrutural do template institucional, mas a conformidade final deve ser auditada contra:

- manual institucional vigente da Universidade IDP;
- ABNT NBR 6023:2025;
- ABNT NBR 10520:2023;
- ABNT NBR 14724:2024;
- demais normas indicadas pela Biblioteca.

O estilo biblatex-abnt automatiza a geração da lista de referências, mas sua saída será validada contra a NBR 6023:2025 antes da versão final.

## Regra de desenvolvimento

O texto da dissertação será produzido progressivamente nos arquivos de capítulos. Mudanças estruturais relevantes devem ser registradas no histórico Git.