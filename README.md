[README-terrorism-gtd-vdem.md](https://github.com/user-attachments/files/32254722/README-terrorism-gtd-vdem.md)
# Between Violence and Politics: An Analysis of Global Terrorism

Projeto académico de Visualização e Análise de Dados (VAD), NOVA FCT, 2026.

## Objetivo

Explorar a dinâmica do terrorismo global através de uma abordagem orientada a dados, cruzando o **Global Terrorism Database (GTD)** com indicadores políticos do **Varieties of Democracy Project (V-Dem)**, para responder a três questões de investigação:

1. Qual é o ciclo de vida de um grupo terrorista (emergência, picos de atividade, declínio)?
2. Como é que o tipo de ataque, o tipo de alvo e a região influenciam conjuntamente a letalidade e o sucesso dos ataques?
3. Como é que os regimes políticos moldam a frequência, a letalidade e o sucesso dos ataques terroristas?

## Datasets

- **GTD** (1970–2017, exceto 1993) — 181 692 eventos de terrorismo globais
- **V-Dem Core v16** — indicadores político-institucionais por país-ano (democracia, liberdades civis, violência governamental, corrupção, etc.)

## Metodologia

- Limpeza e harmonização dos dois datasets (padronização de nomes de países, criação de hierarquias espaciais e temporais)
- Análise exploratória de dados (EDA)
- Construção de **8 dashboards interativos em Tableau**, cobrindo:
  1. Ciclo de vida dos grupos terroristas
  2. Perfil tático (armas e tipos de ataque)
  3. Panorama global (escala, distribuição, mortalidade)
  4. Dinâmica e impacto dos ataques (letalidade, sucesso, vítimas)
  5–8. Relação entre regimes políticos e frequência, letalidade e sucesso dos ataques

## Principais conclusões

- O período pós-2010 é dominado por um pequeno número de grupos extraordinariamente letais (ISIL, Boko Haram, Talibã)
- Bombing/Explosion é consistentemente o método de ataque mais frequente
- As taxas de sucesso dos ataques são uniformemente altas (>84%) em todas as regiões
- **Autocracias eleitorais** estão associadas às maiores frequências de ataques; **autocracias fechadas**, apesar de menos eventos, produzem os incidentes individuais mais letais
- A relação entre regime político e terrorismo é não-linear: o maior risco concentra-se em estados em transição política

## Autores

Bernardo Prazeres, Inês Pinto, Leonor Afonso — NOVA FCT

## Ficheiros

- `paper.pdf` — relatório completo do projeto, com todas as figuras e dashboards descritos
