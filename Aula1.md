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

flowchart TB
    %% --- ESTILOS ---
    classDef eixo fill:#2d3748,stroke:#1a202c,color:#fff,font-weight:bold;
    classDef rosa fill:#fed7d7,stroke:#feb2b2,color:#1a202c;
    classDef azulClaro fill:#ebf8ff,stroke:#bee3f8,color:#1a202c;
    classDef azul fill:#dbeafe,stroke:#93c5fd,color:#1a202c;
    classDef verdeClaro fill:#f0fdf4,stroke:#bbf7d0,color:#1a202c;
    classDef verde fill:#d1fae5,stroke:#6ee7b7,color:#1a202c;
    classDef roxo fill:#e0e7ff,stroke:#c7d2fe,color:#1a202c;
    classDef cinza fill:#f3f4f6,stroke:#d1d5db,color:#1a202c;
    classDef laranja fill:#ffedd5,stroke:#fed7aa,color:#1a202c;

    %% --- EIXO HORIZONTAL DE ANOS ---
    subgraph EIXO[" "]
        direction LR
        E65((1965)) :::eixo --- E69((1969)) :::eixo
        E69 --- E72((1972)) :::eixo
        E72 --- E78((1978)) :::eixo
        E78 --- E81((1981)) :::eixo
        E81 --- E84((1984)) :::eixo
        E84 --- E85((1985)) :::eixo
        E85 --- E87((1987)) :::eixo
        E87 --- E90((1990)) :::eixo
        E90 --- E91((1991)) :::eixo
        E91 --- E93((1993)) :::eixo
        E93 --- E94((1994)) :::eixo
        E94 --- E96((1996)) :::eixo
        E96 --- E01((2001)) :::eixo
        E01 --- E05((2005)) :::eixo
        E05 --- E08((2008)) :::eixo
    end

    %% --- CARDS SUPERIORES ---
    MULTICS["<b>Multics</b><br>• Desenvolvido por MIT, AT&T e GE.<br>• Sistema multiusuário/multitarefa."] :::rosa
    UNIX_C["<b>Unix em C</b><br>• Reescrito em C.<br>• Aumento da portabilidade."] :::azulClaro
    MSDOS["<b>PC e MS-DOS</b><br>• IBM lança PC.<br>• Microsoft fornece o MS-DOS."] :::roxo
    WIN1["<b>Windows</b><br>• GUI sobre MS-DOS.<br>• Introdução do mouse."] :::azul
    GNU_HURD["<b>GNU Hurd</b><br>• Microkernel para o GNU.<br>• Alternativa ao kernel."] :::verdeClaro
    WIN_NT["<b>Windows NT</b><br>• Arquitetura 32-bits.<br>• Suporte a redes."] :::rosa
    REACTOS["<b>ReactOS</b><br>• SO livre compatível com NT.<br>• Projeto open-source."] :::azulClaro
    MAC_INTEL["<b>Mac OS (Intel)</b><br>• Migração para chips Intel.<br>• Kernel Darwin."] :::azul

    %% --- CARDS INFERIORES ---
    UNIX["<b>Unix</b><br>• Criado por Thompson e Ritchie.<br>• Base da computação."] :::azulClaro
    APPLE2["<b>Apple II</b><br>• Popularizou computadores pessoais.<br>• Padronizou BASIC."] :::verde
    MAC_OS["<b>Mac OS</b><br>• Interface gráfica popular.<br>• Foco em usabilidade."] :::azul
    GNU["<b>Projeto GNU</b><br>• Sistema totalmente livre.<br>• Utilitários cruciais."] :::laranja
    MINIX["<b>Minix</b><br>• Criado por Tanenbaum.<br>• Unix-like educacional."] :::cinza
    LINUX["<b>Linux</b><br>• Criado por Linus Torvalds.<br>• Kernel open-source."] :::laranja
    POWERPC["<b>Mac PowerPC</b><br>• Transição de arquitetura.<br>• Portabilidade de SO."] :::laranja
    WINXP["<b>Windows XP</b><br>• Unificou linhas NT/9x.<br>• Alta estabilidade."] :::verdeClaro
    ANDROID["<b>Android</b><br>• SO móvel baseado em Linux.<br>• Domínio nos smartphones."] :::verde

    %% --- LIGAÇÕES VERTICAIS ---
    MULTICS --- E65
    UNIX_C --- E72
    MSDOS --- E81
    WIN1 --- E85
    GNU_HURD --- E90
    WIN_NT --- E93
    REACTOS --- E96
    MAC_INTEL --- E05

    E69 --- UNIX
    E78 --- APPLE2
    E84 --- MAC_OS
    MAC_OS --- GNU
    E87 --- MINIX
    E91 --- LINUX
    E94 --- POWERPC
    E01 --- WINXP
    E08 --- ANDROID
