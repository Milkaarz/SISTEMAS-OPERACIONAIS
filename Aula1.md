## 🎯 Conteúdos Abordados

- Conceito e prática de **Commit**
- Mapeamento e ideação com a ferramenta **Miro**
- **Criação de Repositórios** no GitHub
- Criação e **formatação de arquivos `.md`** (Markdown)

---

## 📌 1. O que é Commit?

O **commit** funciona como um "ponto de salvamento" (*checkpoint*) no histórico do seu projeto. Sempre que você faz uma alteração relevante no código ou na documentação e confirma o commit, você registra o estado exato do repositório naquele momento.

* **Boas práticas de commit:**
  * Escrever mensagens claras e objetivas.
  * Descrever o que foi alterado ou adicionado.
  * Mantenha um histórico organizado.

---

## 🎨 2. Planejamento com o Miro

O **Miro** é uma ferramenta de lousa virtual usada para planejar e estruturar ideias visualmente antes ou durante o desenvolvimento.

### Para que utilizamos:
- Criar **fluxogramas** e mapas mentais.
- Organizar tarefas e ideias com post-its virtuais.
- Fazer *brainstorming* em equipe.
- Esboçar estruturas e telas do projeto.

---

## 📁 3. Criação de Repositórios no GitHub

Aprendemos o passo a passo para inicializar um novo projeto diretamente na plataforma do GitHub:

1. Acessar o perfil no GitHub e ir na aba **Repositories**.
2. Clicar no botão **New**.
3. Definir o nome do repositório e uma breve descrição.
4. Escolher a visibilidade (Público ou Privado).
5. Inicializar o repositório (incluindo ou não o arquivo `README.md`).

---

## 📝 4. Criação e Formatação de Arquivos `.md`

Aprendemos a criar e estruturar arquivos Markdown (`.md`) para documentar os projetos de forma visual e organizada.

### Principais formatações que aprendemos:

| Elemento | Sintaxe Markdown | Resultado |
| :--- | :--- | :--- |
| **Título** | `# Título` | Título Principal |
| **Subtítulo** | `## Subtítulo` | Subtítulo |
| **Negrito** | `**texto**` | **texto** |
| **Itálico** | `*texto*` | *texto* |
| **Lista** | `- item` | • item |
| **Código** | `` `código` `` | `código` |

---

```mermaid
flowchart TB
    %% --- ESTILOS ---
    classDef rosa fill:#fed7d7,stroke:#feb2b2,color:#1a202c;
    classDef azulClaro fill:#ebf8ff,stroke:#bee3f8,color:#1a202c;
    classDef azul fill:#dbeafe,stroke:#93c5fd,color:#1a202c;
    classDef verdeClaro fill:#f0fdf4,stroke:#bbf7d0,color:#1a202c;
    classDef verde fill:#d1fae5,stroke:#6ee7b7,color:#1a202c;
    classDef roxo fill:#e0e7ff,stroke:#c7d2fe,color:#1a202c;
    classDef cinza fill:#f3f4f6,stroke:#d1d5db,color:#1a202c;
    classDef laranja fill:#ffedd5,stroke:#fed7aa,color:#1a202c;

    %% --- CARDS SUPERIORES (PARTE DE CIMA) ---
    MULTICS["<b>🔴 Multics</b><br>• Projeto MIT, AT&T e GE.<br>• Multiusuário e multitarefa."] :::rosa
    UNIX_C["<b>🔵 Unix em C</b><br>• Reescrito em C.<br>• Ganhou portabilidade."] :::azulClaro
    MSDOS["<b>💾 PC e MS-DOS</b><br>• Lançamento IBM PC.<br>• Sistema de linha de comando."] :::roxo
    WIN1["<b>🪟 Windows</b><br>• Interface gráfica sobre o DOS.<br>• Uso de janelas e mouse."] :::azul
    GNU_HURD["<b>🟢 GNU Hurd</b><br>• Microkernel para o GNU.<br>• Alternativa ao kernel."] :::verdeClaro
    WIN_NT["<b>🪟 Windows NT</b><br>• Arquitetura 32-bits.<br>• Suporte a redes."] :::rosa
    REACTOS["<b>💿 ReactOS</b><br>• SO livre compatível com NT.<br>• Projeto open-source."] :::azulClaro
    MAC_INTEL["<b>🍏 Mac OS (Intel)</b><br>• Migração para chips Intel.<br>• Kernel Darwin/Unix."] :::azul

    %% --- LINHA CENTRAL DE ANOS ---
    subgraph EIXO[" ─────────────── LINHA DO TEMPO ─────────────── "]
        direction LR
        E65((1965)) --- E69((1969)) --- E72((1972)) --- E78((1978)) --- E81((1981)) --- E84((1984)) --- E85((1985)) --- E87((1987)) --- E90((1990)) --- E91((1991)) --- E93((1993)) --- E94((1994)) --- E96((1996)) --- E01((2001)) --- E05((2005)) --- E08((2008))
    end

    %% --- CARDS INFERIORES (PARTE DE BAIXO) ---
    UNIX["<b>🐧 Unix</b><br>• Criado por Thompson e Ritchie.<br>• Base da computação."] :::azulClaro
    APPLE2["<b>🍏 Apple II</b><br>• Popularizou computadores pessoais.<br>• Padronizou BASIC."] :::verde
    MAC_OS["<b>🖥️ Mac OS</b><br>• Interface gráfica popular.<br>• Foco em usabilidade."] :::azul
    GNU["<b>🦬 Projeto GNU</b><br>• Sistema totalmente livre.<br>• Utilitários cruciais."] :::laranja
    MINIX["<b>🦝 Minix</b><br>• Criado por Tanenbaum.<br>• Unix-like educacional."] :::cinza
    LINUX["<b>🐧 Linux</b><br>• Criado por Linus Torvalds.<br>• Kernel open-source."] :::laranja
    POWERPC["<b>⚡ Mac PowerPC</b><br>• Transição de arquitetura.<br>• Processadores RISC."] :::laranja
    WINXP["<b>🪟 Windows XP</b><br>• Unificou linhas NT/9x.<br>• Alta estabilidade."] :::verdeClaro
    ANDROID["<b>🤖 Android</b><br>• SO móvel baseado em Linux.<br>• Domínio em smartphones."] :::verde

    %% --- CONEXÕES VERTICAIS (CIMA -> EIXO) ---
    MULTICS --- E65
    UNIX_C --- E72
    MSDOS --- E81
    WIN1 --- E85
    GNU_HURD --- E90
    WIN_NT --- E93
    REACTOS --- E96
    MAC_INTEL --- E05

    %% --- CONEXÕES VERTICAIS (EIXO -> BAIXO) ---
    E69 --- UNIX
    E78 --- APPLE2
    E84 --- MAC_OS
    MAC_OS --- GNU
    E87 --- MINIX
    E91 --- LINUX
    E94 --- POWERPC
    E01 --- WINXP
    E08 --- ANDROID
