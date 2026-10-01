# Brand Builder Skill

Skill para Claude Code que funciona como um consultor de marca. Guia você na construção de uma marca irresistível e geradora de receita, combinando fundamentos acadêmicos com metodologia prática creator-first.

## O que faz

Ao ser acionado, o skill diagnostica onde você está e guia pelas 7 etapas de construção de marca:

1. **Diagnóstico profundo do público** — camada superficial (demografia, hábitos) + camada profunda (desejos reais, fissura cultural, paixão e raiva)
2. **Posicionamento** — mapa de posicionamento, marca-referência, buraco de mercado
3. **Promessa e personalidade** — contrato de final feliz, atributos insubstituíveis, universo de marca
4. **História (Hero Brand)** — cliente = herói, marca = aliado, produto resolve dor funcional, marca resolve dor cultural
5. **Marca pessoal do fundador** — história de criação, crenças únicas, palavras sagradas, tribo, storytelling
6. **Distribuição, conteúdo e comunidade** — funil invertido, criação de conteúdo como ciência, formato criativo, interseção criativa
7. **Product-audience fit e receita** — validação de fit, modelo de receita, diversificação

## Fontes

### Acadêmicas
- **Keller (1993)** — Customer-Based Brand Equity: brand awareness, brand image, associações favoráveis/fortes/únicas
- **Aaker (1997)** — Dimensions of Brand Personality: 5 dimensões, 15 facetas, 42 traços
- **Sirgy (1982)** — Self-Concept in Consumer Behavior: autocongruência real/ideal/social
- **Hoffmann & Akbar (2023)** — Consumer Behavior: motivação (7 motivos ultimatos), emoção (brand love), cognição (AIDA)

### Práticas
- **Tai Dantas / Vinci Society** — Hero Brand, marca irresistível, fissura cultural, funil invertido, empresa creator
- **Hana Frank / Criadores do Futuro** — conteúdo como ciência, formato criativo, interseção criativa, estruturas de roteiro (IHC, Jeito Errado/Certo)
- **Caso Manu Cit** — 6 pilares de marca creator, product-audience fit
- **Caso Flávio Augusto** — 6 pilares de marca pessoal (história, crenças, palavras sagradas, tribo)

## Estrutura

```
brand-builder/
├── SKILL.md                              # Instrução principal (7 etapas + princípios de condução)
├── README.md
└── references/
    ├── fundamentos-academicos.md         # Keller, Aaker, Sirgy, Hoffmann & Akbar
    ├── framework-pratico.md              # Método Vinci decodificado em 7 etapas
    └── criacao-conteudo.md               # Hana Frank: roteiros, formatos, criatividade
```

## Como instalar

### Claude Code CLI

```bash
claude skill add --from github:olivmath/brand-builder
```

### Manual

Copie a pasta `brand-builder/` para `~/.claude/skills/` ou para `.claude/skills/` no seu projeto.

## Como usar

O skill é acionado automaticamente quando você fala sobre:
- Criar, reposicionar ou escalar uma marca
- Posicionamento, storytelling, personalidade de marca
- Criação de conteúdo, roteiro, formato criativo
- Comunidade, audiência, product-audience fit
- Gerar receita a partir da marca

Ou invoque diretamente:

```
/brand-builder
```

## Idioma

Todo o conteúdo está em português brasileiro. O skill responde em pt-BR.
