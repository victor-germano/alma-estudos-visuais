# Alma Estudos Visuais — Site Artístico

> Site artístico minimalista com identidade visual personalizada, desenvolvido para estúdio de artes visuais com foco em experiência do usuário e estética refinada.

---

## Sobre o Projeto

Site desenvolvido para o estúdio Alma Estudos Visuais, com identidade visual exclusiva e layout responsivo. O projeto traduz a linguagem artística do cliente em uma experiência digital imersiva.

Demo: [victor-germano.github.io/alma-estudos-visuais](https://victor-germano.github.io/alma-estudos-visuais/)

---

## Funcionalidades

- Design minimalista com identidade visual personalizada
- Galeria de obras e projetos artísticos
- Layout responsivo (mobile, tablet, desktop)
- Animações suaves para experiência imersiva
- Formulário de contato
- Tipografia e paleta de cores exclusivas

---

## Tecnologias

| Camada | Tecnologia |
|---|---|
| Estrutura | HTML5 semântico |
| Estilo | CSS3 (animações, variáveis CSS, Grid) |
| Interatividade | JavaScript puro (ES6+) |
| Design | Figma |
| Prototipagem | IA (Lovable / Claude) |

---

## Estrutura do Projeto

```
alma-estudos-visuais/
├── index.html          # Página principal (hero, sobre, galeria, contato)
├── css/
│   └── styles.css      # Estilos, variáveis de tema, animações, responsividade
├── js/
│   └── main.js         # Navegação mobile, fade-in ao rolar, validação do formulário
└── README.md
```

---

## Como rodar localmente

Site estático, sem dependências ou build:

```bash
git clone https://github.com/victor-germano/alma-estudos-visuais.git
cd alma-estudos-visuais
python3 -m http.server 8000
# acesse http://localhost:8000
```

---

## Status

- Estrutura, layout responsivo, navegação e animações de entrada: implementados
- Galeria: usa blocos de cor como placeholder em `js/main.js` — substituir por imagens reais das obras em uma pasta `assets/obras/`
- Formulário de contato: validação client-side implementada; sem backend de envio configurado (integrar um serviço como Formspree, EmailJS, ou endpoint próprio)

---

## Autor

**Victor Germano** — Desenvolvedor Web Full Stack, IA & Automação

- Portfólio: [victor-germano.github.io/portfolio-germano-dev](https://victor-germano.github.io/portfolio-germano-dev)
- E-mail: dev.germanoo@gmail.com
- LinkedIn: [linkedin.com/in/victor-germano-65787b2b1](https://linkedin.com/in/victor-germano-65787b2b1)

---

## Licença

MIT License
