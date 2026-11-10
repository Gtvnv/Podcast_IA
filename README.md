# Podcast gerado por IA: Clean Architecture em .NET

Projeto prático para produzir um episódio de podcast usando uma esteira de prompts. Cada etapa do processo criativo (pauta, roteiro, voz, capa e edição) tem um prompt versionado neste repositório.

**Tema do episódio:** "Clean Architecture em .NET: por que suas dependências devem apontar para dentro".

## Tecnologias

- [ChatGPT](https://chat.openai.com/) para pauta e roteiro
- [ElevenLabs](https://elevenlabs.io/) para síntese de voz
- [Midjourney](https://www.midjourney.com/) para a capa
- [CapCut](https://www.capcut.com/) (ou Audacity) para edição e trilha de fundo

## Estrutura

```
.
├── assets/            # capa do episódio
├── docs/
│   ├── fluxo.md       # passo a passo da esteira
│   └── etica.md       # uso responsável de IA e vozes sintéticas
├── output/            # áudios gerados e editado final
└── src/prompts/
    ├── 01-pauta.md
    ├── 02-roteiro.md
    ├── 03-elevenlabs.md
    ├── 04-midjourney.md
    └── 05-edicao.md
```

## Como executar

1. Rode os prompts de `01-pauta.md` e `02-roteiro.md` no ChatGPT e salve o roteiro final em `output/roteiro.md`.
2. Use o texto do roteiro com as configurações de `03-elevenlabs.md` e salve o áudio bruto em `output/audio_sintetizado.mp3`.
3. Gere a capa com `04-midjourney.md` e salve em `assets/cover.png`.
4. Edite o áudio seguindo `05-edicao.md` e salve o resultado em `output/podcast_editado.mp3`.

Detalhes em [docs/fluxo.md](docs/fluxo.md).

## Preview

Depois de gerar o áudio final, ele aparece aqui:

<audio src="output/podcast_editado.mp3" controls title="Podcast editado"></audio>

## Uso responsável

Leia [docs/etica.md](docs/etica.md) antes de publicar. Em resumo: avise que o conteúdo é gerado por IA, não clone vozes sem autorização e revise os fatos do roteiro.

## Licença

Uso educacional. Adapte os prompts ao seu tema.
