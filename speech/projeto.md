# 🗣️ Projeto de Voz com Azure Speech Studio

## 🧠 Objetivo

Explorar os recursos de reconhecimento de fala, síntese de voz e tradução automática usando o Azure Speech Studio. O foco é testar diferentes entradas (como letras de músicas) e avaliar a precisão e naturalidade dos resultados.

## 🎵 Experimento com Letra de Música

**Música:** Somewhere Only We Know – Keane  
Trecho utilizado:
> I walked across an empty land  
> I knew the pathway like the back of my hand...

### Testes Realizados

1. **Speech-to-Text (Reconhecimento de Fala)**
   - Entrada: áudio falado com o trecho da música
   - Resultado: transcrição precisa com variações sutis de pontuação

2. **Text-to-Speech (Síntese de Voz)**
   - Vozes testadas: Jenny (en-US), Antonio (pt-BR)
   - Resultado: entonação natural, boa fluidez

3. **Tradução Automática**
   - Tradução do inglês para o português
   - Resultado: tradução coerente e contextualizada

## 📂 Arquivos Relacionados

- `audio_samples/`: amostras de áudio utilizadas
- `transcriptions/`: resultados das transcrições
- `tts_outputs/`: arquivos gerados com síntese de voz

## 📌 Observações

- A qualidade do áudio influencia diretamente na precisão da transcrição.
- Vozes neurais oferecem resultados mais naturais na síntese.
- Letras de músicas são úteis para testar ritmo, prosódia e entonação.

## 🚀 Próximos Passos

- Testar com diferentes sotaques e velocidades de fala
- Comparar resultados entre vozes padrão e neurais
- Integrar com Azure Bot Framework para aplicações interativas

---


