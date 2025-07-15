# Desafio_Azure-Speech-e-Language-Studio-focado-na-análise-de-fala-e-linguagem-natural.
Repositório prático com Azure Speech Studio e Language Studio — análise de voz, sentimentos e linguagem natural com IA aplicada.

# 💬 Azure Language Studio – Prática e Anotações Técnicas

## 📌 Visão Geral

O Azure Language Studio oferece ferramentas para processar linguagem natural, incluindo análise de sentimento, extração de entidades, detecção de idioma e categorização de texto.

---

## 🔧 Testes Realizados

### 1. Análise de Sentimento

#### Frase:
> "Estou extremamente decepcionado com o serviço ao cliente — esperei horas e ainda não resolveram meu problema."

- Resultado: **Negativo**
- Confiança: 98%
- Observação: A IA detectou frustração e insatisfação.

---

### 2. Extração de Entidades Nomeadas

#### Frase:
> "Desde a atualização do Microsoft Teams em 10 de julho de 2025, a produtividade da equipe em São Paulo caiu drasticamente."

- Entidades reconhecidas:
  - Microsoft Teams (Produto)
  - 10 de julho de 2025 (Data)
  - São Paulo (Localização)

- Observação: Mesmo com frase longa, as entidades foram corretamente extraídas.

---

### 3. Detecção de Idioma

#### Frase:
> "Je suis très mécontent du service."

- Resultado: Idioma detectado: Francês
- Observação: Boa precisão mesmo com frases curtas.

---

## 🧠 Aprendizados

- A ferramenta funciona bem para frases de 10 a 30 palavras.
- Frases ambíguas ou sarcásticas podem ter resultado de sentimento **neutro**.
- É possível treinar modelos personalizados para contextos específicos (ex: jurídico, médico).



