# 🏥 Farmácia Cidade — Saúde & Beleza (Catálogo Digital & Delivery PWA)

Aplicação web responsiva (*mobile-first*) de alta conversão desenvolvida para a **Farmácia Cidade - Saúde & Beleza** (Estrada de Belém, 649 — Hipódromo/Encruzilhada, Recife - PE).

![Logo Farmácia Cidade](./assets/logo/logo.svg)

## ✨ Funcionalidades Principais

- **Status Dinâmico em Tempo Real:** Identificação automática de horário comercial (Seg a Sáb, 8h às 21h).
- **Envio Rápido de Receita Médica:** CTA direto integrado ao WhatsApp para consulta de medicamentos e envio de receitas.
- **Busca Instantânea & Categorias Deslizáveis:** Filtragem em tempo real por nome, apresentação ou categoria (*Ofertas do Dia, Infantil & Fraldas, Higiene & Beleza, Vitaminas & Suplementos*).
- **Cesta de Pedidos Interativa:**
  - Persistência local (`localStorage`) para não perder os itens ao atualizar a página.
  - Cálculo automático de taxa de entrega por bairro (*Hipódromo, Encruzilhada, Campo Grande, Rosarinho, Torreão e Retirada na Loja*).
  - Seleção de forma de pagamento (*Pix, Cartão na Entrega ou Dinheiro com campo opcional de troco*).
  - Geração automática do resumo completo formatado direto para o WhatsApp da farmácia.
- **Experiência Estilo Aplicativo Mobile:** Navegação inferior fixa e barra flutuante de resumo da cesta.

## 📁 Estrutura do Repositório

```text
├── assets/
│   └── logo/
│       ├── logo.svg                    # Logotipo vetorial horizontal
│       ├── logo-icon.svg               # Ícone vetorial quadrado (PWA)
│       └── logo-farmacia-cidade.jpg    # Logotipo oficial em alta resolução
├── index.html                          # Aplicação completa (HTML5 + Tailwind CSS + Vanilla JS)
├── vercel.json                         # Configuração de deploy estático na Vercel
└── README.md                           # Documentação do projeto
```

## 🚀 Como Executar Localmente

Basta abrir o arquivo `index.html` diretamente em qualquer navegador moderno ou servir a pasta com um servidor estático:

```bash
npx serve .
```

---

Desenvolvido por **Ricardo Leão** — [estilo-dev.vercel.app](https://estilo-dev.vercel.app) • `@dev.leao`
