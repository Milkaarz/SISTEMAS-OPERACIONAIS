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

graph LR
    %% Configuração de Estilos e Cores (baseados na imagem)
    classDef eixo fill:#2d3748,stroke:#1a202c,color:#fff,font-weight:bold;
    classDef rosa fill:#fed7d7,stroke:#feb2b2,color:#1a202c;
    classDef azulClaro fill:#ebf8ff,stroke:#bee3f8,color:#1a202c;
    classDef azul fill:#dbeafe,stroke:#93c5fd,color:#1a202c;
    classDef verdeClaro fill:#f0fdf4,stroke:#bbf7d0,color:#1a202c;
    classDef verde fill:#d1fae5,stroke:#6ee7b7,color:#1a202c;
    classDef roxo fill:#e0e7ff,stroke:#c7d2fe,color:#1a202c;
    classDef cinza fill:#f3f4f6,stroke:#d1d5db,color:#1a202c;
    classDef laranja fill:#ffedd5,stroke:#fed7aa,color:#1a202c;

    %% --- EIXO CENTRAL DE ANOS ---
    E65((1965)) :::eixo --- E69((1969)) :::eixo --- E72((1972)) :::eixo --- E78((1978)) :::eixo --- E81((1981)) :::eixo --- E84((1984)) :::eixo --- E85((1985)) :::eixo --- E87((1987)) :::eixo --- E90((1990)) :::eixo --- E91((1991)) :::eixo --- E93((1993)) :::eixo --- E94((1994)) :::eixo --- E96((1996)) :::eixo --- E01((2001)) :::eixo --- E05((2005)) :::eixo --- E08((2008)) :::eixo

    %% --- CARDS SUPERIORES (CIMA) ---
    MULTICS["<b>Multics</b><br>• Projeto desenvolvido por MIT, AT&T e GE.<br>• Sistema multiusuário, multitarefa.<br>• Muito avançado e complexo.<br>• Influenciou diretamente o Unix."] :::rosa
    UNIX_C["<b>Unix em C</b><br>• Reescrito em linguagem C.<br>• Aumento da portabilidade e popularização.<br>• Tornou-se referência para sistemas operacionais."] :::azulClaro
    MSDOS["<b>PC e MS-DOS</b><br>• IBM lança PC.<br>• Microsoft fornece o MS-DOS.<br>• Sistema simples, monousuário e monotarefa.<br>• Grande impacto nos PCs."] :::roxo
    WIN1["<b>Windows</b><br>• Interface gráfica sobre o MS-DOS.<br>• Introdução de janelas e uso do mouse.<br>• Popularização da interface gráfica em PCs."] :::azul
    GNU_HURD["<b>GNU Hurd</b><br>• Desenvolvimento de microkernel para o projeto GNU.<br>• Alternativa ao kernel tradicional."] :::verdeClaro
    WIN_NT["<b>Windows NT</b><br>• Arquitetura independente do MS-DOS.<br>• Suporte a redes e múltiplos usuários.<br>• Introdução do sistema NTFS."] :::rosa
    REACTOS["<b>ReactOS</b><br>• Sistema livre compatível com Windows NT.<br>• Projeto open-source ainda em desenvolvimento."] :::azulClaro
    MAC_INTEL["<b>Mac OS (Intel)</b><br>• Mac migra para processadores Intel.<br>• Uso de kernel Darwin V/Unix-like."] :::azul

    %% Conexões Cima -> Eixo
    MULTICS --- E65
    UNIX_C --- E72
    MSDOS --- E81
    WIN1 --- E85
    GNU_HURD --- E90
    WIN_NT --- E93
    REACTOS --- E96
    MAC_INTEL --- E05

    %% --- CARDS INFERIORES (BAIXO) ---
    UNIX["<b>Unix</b><br>• Criado por Ken Thompson e Dennis Ritchie.<br>• Base para múltiplos sistemas operacionais.<br>• Base para diversos sistemas operacionais modernos."] :::azulClaro
    APPLE2["<b>Apple II</b><br>• Popularização dos computadores pessoais.<br>• Padronizou BASIC e permitiu armazenamento em fitas e disquetes."] :::verde
    MAC_OS["<b>Mac OS</b><br>• Interface gráfica baseada em mouse.<br>• Boa usabilidade no desktop.<br>• Tornou computadores mais acessíveis visualmente."] :::azul
    GNU["<b>Projeto GNU</b><br>• Iniciado para criar um sistema totalmente livre.<br>• Desenvolveu utilitários cruciais."] :::laranja
    MINIX["<b>Minix</b><br>• Criado por Andrew Tanenbaum.<br>• Sistema Unix-like educacional.<br>• Microkernel leve e limpo."] :::cinza
    LINUX["<b>Linux</b><br>• Criado por Linus Torvalds.<br>• Kernel tipo Unix escrito em C.<br>• Amplamente adotado em servidores e supercomputadores."] :::laranja
    POWERPC["<b>Mac PowerPC</b><br>• Mac passa a usar arquitetura PowerPC.<br>• Portabilidade de novos tipos de sistemas."] :::laranja
    WINXP["<b>Windows XP</b><br>• Unificou linhas corporativas e de consumo.<br>• Alta compatibilidade e popularidade."] :::verdeClaro
    ANDROID["<b>Android</b><br>• Sistema operacional móvel baseado em Linux.<br>• Domínio do mercado de smartphones."] :::verde

    %% Conexões Eixo -> Baixo
    E69 --- UNIX
    E78 --- APPLE2
    E84 --- MAC_OS
    MAC_OS --- GNU
    E87 --- MINIX
    E91 --- LINUX
    E94 --- POWERPC
    E01 --- WINXP
    E08 --- ANDROID
