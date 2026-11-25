# Cor & Forma — Gráfica e Comunicação Visual

> *"Sua marca em todo lugar."*

Landing page institucional desenvolvida para a **Cor & Forma**, gráfica e empresa de comunicação visual com **14 anos de mercado**, focada na divulgação de pequenos comércios, empresas e profissionais independentes.

---

## Sobre o projeto

A página apresenta os serviços, prazos médios, destaques, galeria visual e canal de contato da **Cor & Forma**, com layout responsivo construído com **Bootstrap 5** (`5.3.8`), tipografia do **Google Fonts** e identidade visual personalizada em CSS.

### Principais seções
- **Hero / Letreiro Luminoso:** Título principal com efeito de brilho animado (`text-shadow` + `@keyframes brilho`), subtítulo, slogan e chamadas para orçamento e serviços.
- **Sobre nós:** Apresentação da empresa e de sua atuação no mercado há 14 anos.
- **Destaques:** Três cards com bordas coloridas destacando:
  1. **Adesivos e películas** (carros, vans e utilitários).
  2. **Fachadas e letreiros luminosos** (projeto, produção e instalação, com visita técnica sem custo).
  3. **Impressos e sacolas** (panfletos, cartões e sacolas personalizadas).
- **Serviços e prazos:** Tabela responsiva com prazos médios e valores iniciais.
- **Galeria:** Grade responsiva com imagens e legendas descritivas dos trabalhos.
- **Contato e horário:** Informações de atendimento e formulário de contato com seleção de assunto e aceite da política de privacidade.

---

## Serviços, prazos e valores iniciais

| Serviço | Prazo médio | A partir de |
| :--- | :--- | :--- |
| Adesivos personalizados (50 unidades) | 3 dias | R$ 90,00 |
| Panfletos (1.000 unidades) | 4 dias | R$ 160,00 |
| Sacolas personalizadas (100 unidades) | 7 dias | R$ 380,00 |
| Película em veículos | 1 dia | R$ 450,00 |
| Fachadas e letreiros luminosos | Sob consulta | Sob orçamento |

---

## Identidade visual e tecnologias

- **HTML5** semântico (`corForma.html`)
- **CSS3** com variáveis customizadas, animações e suporte a `prefers-reduced-motion` (`corEForma.css`)
- **Bootstrap 5.3.8** (grid, navbar responsiva, cards, tabelas e formulários)
- **Google Fonts:** `Rubik` (títulos, com fallback para `Arial, sans-serif`) e `Work Sans` (corpo do texto, com fallback para `Arial, sans-serif`)

### Paleta de cores
| Variável | Cor | Uso principal |
| :--- | :--- | :--- |
| `--escuro` | `#1f2430` | Cabeçalho, rodapé, hero e textos |
| `--ciano` | `#00a6d6` | Botões primários, links e brilho do letreiro |
| `--magenta` | `#d6247b` | Destaques e gradiente de acento |
| `--amarelo` | `#ffd23f` | Subtítulo, estados de foco/hover e detalhes |
| `--fundo` | `#f7f8fa` | Fundo geral da página |

---

## Estrutura de arquivos

```text
.
├── corForma.html
├── corEForma.css
└── img/
    └── (arquivos de imagem referenciados na galeria)
