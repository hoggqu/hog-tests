# Hog Tests

[中文 / Bilingual overview](README.md) · **English**

Public experiments with AI models and agents.

## Four-model NPC exploration experiment

**[Read the interactive report in English →](https://hoggqu.github.io/hog-tests/#en)**

Four models control the same game NPC, each starting from identical conditions on a 384-cell map:

- Gemini 3.1 Flash Lite
- GPT-5.6 Luna
- DeepSeek Flash
- TypeSafe · Jev 1.13.0

The game server defines the world rules and validates actions. The models choose how to explore, gather berries, eat, drink, and rest. Each run ends when the entire map has been discovered.

The report covers:

- Experimental setup and differences between the integration approaches.
- Completion time, action counts, and token usage.
- Behavioral reasonableness scores with explanations.
- Network latency measurements as a reference.
- Conditional cost estimates using official list prices, in USD and CNY.

> Only one complete run is shown per model. This is a system-level comparison, not a general model-capability ranking. Behavior scores are observational, not an independent blind evaluation. Some call usage is missing, and cost estimates are not final bills.

## Viewing options

- **Online:** [Open the English report](https://hoggqu.github.io/hog-tests/#en). The page also supports Chinese via the language switch at the top.
- **Offline:** download [`index.html`](index.html) and open it in a browser.
- **PDF:** use your browser's Print → Save as PDF. Only the selected language is printed.

Experiment date: **September 19, 2026**.
