# 🥁 SimpleDrums

> Uma beat machine direto no navegador, com sons de bateria e atalhos de teclado.

![SimpleDrums preview](images/bateria.png)

🔗 **[Acesse o projeto ao vivo](https://felipegardenghidev.github.io/SimpleDrums/)**

---

## 🎛️ Sons disponíveis

Os 9 pads são mapeados em um grid 3×3 que espelha o layout do teclado físico:

| Pad | Tecla | Instrumento |
|-----|-------|-------------|
| 808 | `Q` | Bumbo eletrônico |
| Clap | `W` | Caixa + palmas |
| Hi-Hat | `E` | Chimbal fechado |
| Bumbo | `A` | Bumbo acústico |
| Open Hat | `S` | Chimbal aberto |
| Ride | `D` | Prato ride |
| Snare | `Z` | Caixa eletrônica |
| Click | `X` | Metrônomo |
| Tom | `C` | Tom |

---

## 🚀 Como usar

**Mouse / toque:** clique em qualquer pad para tocar o som.

**Teclado:**
```
Q  W  E
A  S  D
Z  X  C
```
Cada tecla corresponde ao pad na mesma posição do grid. Dá pra fazer batidas completas só com o teclado!

---

## 🛠️ Tecnologias

- HTML5 semântico
- CSS3 (Grid, Flexbox, variáveis CSS, `clamp()`)
- JavaScript vanilla (sem dependências)
- [Bootstrap 5](https://getbootstrap.com/) — utilitários de layout e espaçamento
- [Bootstrap Icons](https://icons.getbootstrap.com/) — ícone do footer
- [Google Fonts](https://fonts.google.com/) — Montserrat

---

## ♿ Acessibilidade

- Navegação e ativação completa por teclado
- `aria-label` descritivo em cada botão (inclui nome do instrumento e tecla de atalho)
- Foco visível via `:focus-visible` (sem remover outline)
- Suporte a `prefers-reduced-motion`

---

## 📁 Estrutura

```
SimpleDrums/
├── index.html
├── main.js
├── css/
│   ├── estilos.css
│   └── reset.css
├── sounds/
│   └── *.wav
└── images/
    └── bateria.png
```

---

## 🙏 Origem

Projeto baseado no **Alura MIDI**, desenvolvido durante o curso de JavaScript da [Alura](https://www.alura.com.br/). O SimpleDrums é uma versão evoluída com nova identidade visual, responsividade, acessibilidade e atalhos de teclado globais.

---

Desenvolvido por **Felipe Gardenghi** · Projeto fictício sem fins comerciais.
