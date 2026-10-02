# Caso fictício: devolução antecipada de imóvel alugado, multa e caução 

  

## Finalidade 

Este repositório mostra, passo a passo, como usar IA em um caso jurídico inteiramente fictício de forma controlada e verificável: do relato original até uma orientação final revisada por pessoa. As etapas são: tirar dados pessoais (sanitização), escolher as fontes, perguntar à IA só com essas fontes (RAG manual), conferir cada afirmação, pedir uma auditoria em outra conversa e registrar a decisão humana. 

  

## Aviso 

Todos os nomes, valores, datas e documentos deste projeto são fictícios. Não há dados reais, processos reais nem informações sigilosas. É um exercício acadêmico e não é parecer jurídico. 

  

## Público 

Estudantes e operadores do Direito, em contexto de aprendizagem. A orientação final foi escrita em linguagem simples para um inquilino leigo fictício. 

  

## Autoria 

Thaissa — Atividade preparatória para a N1 — Inteligência Artificial Jurídica (Aula 04) — Prof. Edson Vaz Lopes — Católica SC. 

  

## O que há em cada pasta 

- entrada/relato_bruto.md: o relato original do caso fictício, com dados pessoais (fictícios). Não vai para a IA. 

- apoio/caso_sanitizado.md: o mesmo caso sem dados pessoais. É a única versão que vai para a IA. 

- apoio/fonte_1.md e apoio/fonte_2.md: as leis escolhidas como base (trechos numerados). 

- docs/limites_e_sigilo.md: regras de sigilo e limites do uso da IA. 

- docs/especificacao.md: o “contrato” do trabalho (finalidade, público, limites, critérios de aceitação). 

- docs/prompts/consulta_rag.md: o prompt usado para consultar a IA com as fontes. 

- docs/prompts/auditoria.md: o prompt usado para auditar a primeira resposta. 

- evidencias/resposta_inicial.md: a primeira resposta da IA. 

- evidencias/verificacao.md: a conferência de cada afirmação (manter, corrigir ou excluir). 

- evidencias/auditoria.md: a resposta da auditoria feita em outra conversa. 

- evidencias/revisao_humana.md: as decisões da autora sobre os achados da auditoria. 

- entrega/orientacao_inicial.md: o texto final revisado. 

  

## Ordem de leitura sugerida 

1. docs/limites_e_sigilo.md e docs/especificacao.md (as regras). 

2. entrada/relato_bruto.md e apoio/caso_sanitizado.md (do relato ao caso sem dados pessoais). 

3. apoio/fonte_1.md e apoio/fonte_2.md (as leis). 

4. docs/prompts/consulta_rag.md e evidencias/resposta_inicial.md (a pergunta e a resposta). 

5. evidencias/verificacao.md (o que foi mantido, corrigido ou excluído). 

6. docs/prompts/auditoria.md, evidencias/auditoria.md e evidencias/revisao_humana.md (auditoria e decisão humana). 

7. entrega/orientacao_inicial.md (resultado final). 

  

## Ferramentas 

Editor: VS Code. Versionamento: Git e GitHub. IA usada: [NOME DA IA E MODELO]. Data das consultas: [DATA]. 

  

## Limites 

A IA só podia usar as fontes da pasta apoio/, que reúnem trechos da Lei do Inquilinato (Lei 8.245/1991). Não foram analisados o contrato completo, jurisprudência, vias para reclamar ou eventual ação judicial. A responsabilidade pelo conteúdo final é humana. 

  

## Repositório 

https://github.com/ThaiDallagnelo/caso_ficticio_locacao.git