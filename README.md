# Ajudante do Ajudante Salweb - Ferramenta de Análise Automática do CNIS que Gera uma Tabela para a Extensão

## Objetivo Principal
Este projeto visa processar os PDFs 'SIBE Completo' e 'Contribuições/Recolhimentos' para identificar problemas de contribuição (ex: abaixo do mínimo), sugerir ações necessárias (ex: complementação de 11% para 20%, complementar para o mínimo 11%, MEI de 5% para 20%, complementar para o mínimo código 1007/1406), e gerar automaticamente uma tabela HTML. Esta tabela é formatada para ser importada pela extensão , facilitando a entrada automática de competências no Salweb.

## Funcionalidades Principais
- Analisa o CNIS para identificar pendências.
- Gera HTML para importação na extensão  para preenchimento automático no Salweb.

## Para Quem é Destinado
Esta ferramenta é destinada a servidores do INSS (Instituto Nacional do Seguro Social) que precisam calcular as diferenças de valores de recolhimentos para lançar no Salweb e gerar a GPS (Guia da Previdência Social) para o segurado.

## Como Usar
1.  Use o prompt fornecido com os PDFs do CNIS.
2.  Copie a tabela HTML gerada.
3.  Salve com a terminação .sal.
4.  Importe o arquivo pela extensão.
5.  Com o Salweb aberto em outra aba, clique em exportar para preenchimento automático da GPS.

## Requisitos
-   Um Large Language Model (LLM) para usar o prompt.
-   Os PDFs 'SIBE Completo' e 'Contribuições/Recolhimentos'.
-   A extensão 'Ajudante Salweb' instalada no Firefox.

## Limitações e Recomendações
Esta ferramenta foi exaustivamente testada várias vezes, e os valores foram verificados tanto manualmente (usando a regra de três) quanto inserindo-os na planilha do CI, sempre produzindo os mesmos resultados. No entanto, **cada servidor é responsável pelo seu próprio trabalho e deve verificar e checar cada interação e entrada.** A ferramenta é um auxílio, mas a responsabilidade final pela correção e adequação do trabalho é do servidor.

## Contato
Para dúvidas ou sugestões, você pode entrar em contato via e-mail: wanderleyamorim.com@gmail.com

## Informações Adicionais
Este processo é extremamente útil e tem me economizado uma quantidade significativa de tempo, além de ser menos suscetível a falhas, erros de cálculo humanos, erros de preenchimento, etc.
