# Prompt de auditoria (segunda conversa) 

  

Como usar: abra uma conversa NOVA, sem o histórico da primeira. Cole o texto da seção “Prompt” e, depois, o caso sanitizado, as duas fontes e a resposta inicial (evidencias/resposta_inicial.md). 

  

## Prompt 

  

Você é um auditor de conteúdo jurídico. Vou colar um CASO_SANITIZADO, duas fontes (FONTE_1 e FONTE_2, com trechos de [T1] a [T4]) e uma RESPOSTA_INICIAL produzida por outra IA. 

  

Tarefa: auditar a RESPOSTA_INICIAL usando somente as fontes e o caso colados. Não use conhecimento externo. 

  

Para cada afirmação relevante da RESPOSTA_INICIAL, verifique: 

1. Está sustentada pelo trecho citado? A indicação de arquivo e trecho está correta? 

2. Há afirmação sem base nas fontes? 

3. Há linguagem de certeza maior que a das fontes, ou algum requisito da fonte que foi ignorado? 

4. Há fato usado que não consta no caso? 

5. As contas estão certas? 

6. Há omissão relevante? 

  

Formato de saída: lista numerada de achados. Para cada achado, informe: (a) a afirmação examinada; (b) classificação: CORRETA, CITAÇÃO ERRADA, SEM BASE NAS FONTES, EXCESSO DE CERTEZA, ERRO DE CÁLCULO ou OMISSÃO; (c) justificativa com arquivo e trecho; (d) gravidade: baixa, média ou alta; (e) sugestão de correção. 

  

Se não houver problema em um ponto, diga expressamente. Não reescreva a resposta inteira. 

  

## Anexos a colar após o prompt 

CASO_SANITIZADO, FONTE_1, FONTE_2 e RESPOSTA_INICIAL. 