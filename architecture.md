# Arquitetura e decisões técnicas

## Apresentação

O site de produção utiliza uma arquitetura de páginas estáticas com conteúdo principal disponível no HTML entregue pelo servidor. Esta documentação descreve os princípios técnicos sem publicar o código-fonte de produção.

## Decisões

1. **HTML semântico** — `header`, `nav`, `main`, `section`, `article` e `footer` para estrutura robusta.
2. **URLs descritivas** — rotas coerentes com a intenção de busca e navegação humana.
3. **Metadados por página** — títulos, descrições e canonicals apropriados a cada URL.
4. **Dados estruturados** — anotações Schema.org quando o conteúdo e a entidade justificam o uso.
5. **Imagens e mídia** — dimensões explícitas, alternativas descritivas e carregamento responsivo.
6. **Acessibilidade** — foco visível, rótulos associados e conteúdo utilizável via teclado.
7. **Recursos** — scripts deferidos e assets dimensionados conforme necessidade.

## Limites

Ser acessível a crawlers não garante posicionamento ou citação por IA. Claims de desempenho, conformidade WCAG e resultados orgânicos só devem ser publicados após medição e verificação.
