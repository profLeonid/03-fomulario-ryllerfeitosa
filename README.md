[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/u0NkBhdA)
# 🎨 Atividade Prática: Explorando Tailwind CSS

## 📋 Objetivo
Desenvolver o layout proposto no Figma utilizando **exclusivamente HTML e Tailwind CSS**, explorando as classes utilitárias do framework para criar interfaces responsivas e modernas sem escrever CSS personalizado.

---

## 🔗 Recursos Necessários

### Design de Referência
- **Figma**: [Acesse o layout da atividade](https://www.figma.com/design/01MBS0EMWr2RtTacntLEgR/Untitled?node-id=0-1&t=0CeTmpf8ktyOqB6h-1)

### Documentação Oficial
- **Tailwind CSS Docs**: [https://tailwindcss.com/docs](https://tailwindcss.com/docs)  
  *(Consulte para entender as classes utilitárias, responsive design, cores, spacing, etc.)*

### Setup Recomendado
```bash
# Opção 1: CDN (apenas para estudos/prototipagem)
<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>

# Opção 2: Instalação via npm (recomendado para produção)
# Install Tailwind CSS
npm install tailwindcss @tailwindcss/cli
# Import Tailwind in your CSS
npx tailwindcss init
# Start the Tailwind CLI build process
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
# Start using Tailwind in your HTML
<link href="./output.css" rel="stylesheet">
```

> ⚠️ **Importante**: Para esta atividade, a versão via CDN é suficiente.

---

## ✅ Regras da Atividade

1. **Sem CSS personalizado**: Todo o estilo deve ser aplicado usando classes do Tailwind. Não crie ou vincule arquivos `.css`.
2. **HTML semântico**: Utilize tags apropriadas (`<header>`, `<main>`, `<section>`, `<footer>`, etc.).
3. **Responsividade**: O layout deve se adaptar a mobile e **opcionalmente** desktop usando os breakpoints do Tailwind (`sm:`, `md:`, `lg:`, etc.).
4. **Organização**: Mantenha o código legível, com indentação adequada e comentários quando necessário.
5. **Fidelidade ao design**: Siga o máximo possível as cores, espaçamentos e hierarquia visual do Figma.

---

## 📦 Estrutura Sugerida do Projeto
```
atividade-tailwind/
├── index.html          # Arquivo principal com HTML + classes Tailwind
├── README.md           # Este arquivo
└── (opcional) assets/  # Imagens ou ícones, se necessário
```

---

## 💡 Dicas para Desenvolvimento

- Use o **Inspector do Navegador** para testar classes rapidamente.
- Consulte a documentação para propriedades como:
  - `flex`, `grid`, `gap-*` para layout
  - `p-*`, `m-*`, `space-*` para espaçamento
  - `text-*`, `font-*`, `leading-*` para tipografia
  - `bg-*`, `text-*`, `border-*` para cores e bordas
  - `hover:`, `focus:`, `md:`, `lg:` para estados e responsividade
- Comece pela estrutura mobile-first e depois adapte para telas maiores.

---

## 📚 Material de Apoio

Para auxiliar nos primeiros passos com o framework, disponibilizamos os seguintes recursos complementares:

- [Documentação Oficial do Tailwind CSS](https://tailwindcss.com/docs)
- [Guia de Instalação](https://tailwindcss.com/docs/installation)
- [Cheat Sheet de Classes Utilitárias](https://nerdcave.com/tailwind-cheat-sheet)
- **Vídeo introdutório**: *Primeiros passos com Tailwind CSS*  
  → [Assistir no YouTube](https://www.youtube.com/watch?v=z5UctL_tnMY)  
  *(Recurso complementar disponível na plataforma para apoio ao aprendizado)*

---

## 📤 Entrega via GitHub Classroom

A entrega será realizada **diretamente neste repositório** criado pelo GitHub Classroom.

### ✅ Fluxo de Entrega
```bash
# 1. Clone seu repositório pessoal (link no Classroom)
git clone https://github.com/seu-usuario/nome-do-repo.git

# 2. Desenvolva a atividade
# Edite o index.html conforme o design do Figma

# 3. Faça commit e push
git add .
git commit -m "feat: layout inicial com header e hero section"
git push origin main
```

> 🔄 **Commits incrementais são bem-vindos!** Mostre a evolução do seu código.

### 🏷️ Sugestão de Prefixos para Commits
| Prefixo | Quando usar | Exemplo |
|---------|-------------|---------|
| `feat:` | Nova funcionalidade ou seção do layout | `feat: adiciona navbar responsiva` |
| `style:` | Ajustes de estilo/classes Tailwind | `style: ajusta spacing da seção features` |
| `fix:` | Correção de bug ou ajuste visual | `fix: corrige alinhamento mobile do footer` |
| `refactor:` | Reorganização do código sem mudar comportamento | `refactor: simplifica classes repetidas` |
| `docs:` | Atualização de comentários ou README | `docs: adiciona comentário sobre grid layout` |
| `chore:` | Tarefas de configuração/manutenção | `chore: atualiza .gitignore` |

### 💬 Exemplos de Mensagens
```bash
git commit -m "feat: estrutura HTML semântica com header, main e footer"
git commit -m "style: aplica cores e tipografia do Figma usando Tailwind"
git commit -m "fix: corrige overflow horizontal em telas pequenas"
git commit -m "feat: implementa responsividade para tablets e desktop"
```

> 📌 **Dica**: Commits descritivos ajudam na correção e demonstram sua evolução técnica!

---

## ❓ Dúvidas Comuns

| Pergunta | Resposta |
|----------|----------|
| Posso usar JavaScript? | Sim, mas apenas para interatividade. O foco da atividade é o estilo com Tailwind. |
| E se eu não encontrar uma classe no Tailwind? | Consulte a docs ou use `@apply` apenas se autorizado pelo professor. |
| Posso usar plugins do Tailwind? | Para esta atividade introdutória, mantenha-se nas classes padrão. |
| Preciso criar branch? | Não é obrigatório, mas se quiser praticar Git Flow, sinta-se à vontade! |

---

> 🚀 **Bônus**: Quem finalizar com antecedência pode explorar variações de tema usando `dark:` ou animações com `transition-*` e `animate-*`.

---

Boa codificação! ✨

**Prof. Fernando Leonid**
