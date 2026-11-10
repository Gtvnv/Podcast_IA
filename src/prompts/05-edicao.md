# 05. Edição de áudio

Ferramenta sugerida: CapCut ou Audacity.

## Passo a passo

1. Importe `output/audio_sintetizado.mp3`.
2. Remova silêncios longos e respirações artificiais.
3. Normalize o volume da voz (alvo próximo de -16 LUFS para podcast).
4. Adicione trilha de fundo livre de direitos autorais:
   - abertura: volume 100% por 5 s, depois reduz para 10 a 15% sob a voz;
   - encerramento: sobe novamente nos últimos 5 s e faz fade out.
5. Inclua uma vinheta curta de abertura e encerramento.
6. Exporte em MP3, 128 kbps ou mais, em `output/podcast_editado.mp3`.

## Prompt auxiliar (ChatGPT)

| Ação | Prompt |
| :--- | :--- |
| Marcação de edição | Com base no roteiro abaixo, sugira em quais momentos subir e descer a trilha, onde inserir pausas e efeitos sonoros discretos. Responda em tabela com: trecho, ação, duração. |
