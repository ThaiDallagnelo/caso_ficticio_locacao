# Prompt de consulta (RAG manual) 

  

Como usar: abra uma conversa nova na IA. Cole o texto da seção “Prompt” e, logo depois, cole o conteúdo de apoio/caso_sanitizado.md, apoio/fonte_1.md e apoio/fonte_2.md, nessa ordem. Se a ferramenta permitir, use temperatura baixa. 

  

## Prompt 

  

OBJETIVO: Identificar, com base exclusivamente nas fontes anexadas, se o inquilino L. deve pagar multa pela devolução antecipada do imóvel e como ela seria calculada, se D. pode cobrar pintura e vidro, e o que as fontes dizem sobre a caução. 

  

CONTEXTO: Estudo de caso fictício para fins acadêmicos. O resultado será conferido por uma pessoa e depois transformado em orientação para um inquilino leigo. 

  

DOCUMENTOS: Use apenas os textos colados abaixo: CASO_SANITIZADO (apoio/caso_sanitizado.md), FONTE_1 (apoio/fonte_1.md) e FONTE_2 (apoio/fonte_2.md). Os trechos estão numerados de [T1] a [T4]. 

  

DADOS: Os fatos estão no CASO_SANITIZADO. Não presuma fatos que não estejam ali. 

  

RESTRIÇÕES: 

- Não use nenhuma lei, julgado, doutrina ou conhecimento externo às fontes. 

- Se algo não constar nas fontes, escreva “não consta nas fontes”. 

- Não invente nomes, datas ou valores. 

- Separe com clareza FATO, REGRA DA FONTE e HIPÓTESE. 

- Não preveja resultado de processo. 

- Não use linguagem de certeza quando a fonte não a sustentar. 

  

PÚBLICO: Revisora com formação jurídica em fase de estudo. 

  

CRITÉRIO: Cada afirmação relevante deve vir acompanhada do arquivo e do rótulo do trecho que a sustenta. Se fizer algum cálculo, mostre a conta passo a passo e diga qual método usou. Liste ao final as lacunas, isto é, o que as fontes não permitem responder. 

  

FORMATO: Responder em quatro seções: 1) Fatos relevantes; 2) Análise com base nas fontes (lista numerada, cada item com arquivo e trecho); 3) Cálculo hipotético da multa; 4) Lacunas e pontos a verificar. 

  

## Anexos a colar após o prompt 

CASO_SANITIZADO: [colar apoio/caso_sanitizado.md] 

FONTE_1: [colar apoio/fonte_1.md] 

FONTE_2: [colar apoio/fonte_2.md] 