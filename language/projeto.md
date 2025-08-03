# 🎵 Utilizando Letra de Música com Azure Speech Studio

## 🧠 Objetivo

Explorar o uso de letras de músicas como entrada para testes de:
- Reconhecimento de fala (Speech-to-Text)
- Tradução automática
- Síntese de voz (Text-to-Speech)

Utilizando o Azure Speech Studio como plataforma principal para experimentação.

## 🎶 Música Escolhida

**Somewhere Only We Know** – Keane

Trecho utilizado:
> I walked across an empty land  
> I knew the pathway like the back of my hand  
> I felt the earth beneath my feet  
> Sat by the river and it made me complete

## 🧪 Experimentos Realizados

### 1. 🎙️ Reconhecimento de Fala
- Entrada: áudio com o trecho cantado ou falado
- Resultado: transcrição precisa com pequenas variações dependendo do sotaque e entonação

### 2. 🌍 Tradução
- Idioma de origem: Inglês
- Idioma de destino: Português
- Resultado:
  > "Eu caminhei por uma terra vazia  
  > Eu conhecia o caminho como a palma da minha mão..."

### 3. 🗣️ Síntese de Voz
- Vozes testadas: Jenny (en-US), Antonio (pt-BR)
- Resultado: reprodução natural e fluida, com boa entonação poética

## 📂 Arquivos Relacionados

- `speech_studio_tests/lyrics_input.txt`: letra usada nos testes
- `speech_studio_tests/results_transcription.json`: resultado da transcrição
- `speech_studio_tests/audio_samples/`: amostras de áudio utilizadas

## 📌 Observações

- A escolha de letras com ritmo e repetição ajuda a testar a precisão do reconhecimento.
- Trechos poéticos podem desafiar a tradução literal, revelando nuances culturais.
- A síntese de voz com letras musicais é útil para criar experiências imersivas em apps de música ou aprendizado de idiomas.

## 🚀 Próximos Passos

- Testar com letras em outros idiomas (espanhol, francês)
- Comparar resultados entre vozes neurais e padrão
- Integrar com Azure Language para análise de sentimentos nas letras

---

