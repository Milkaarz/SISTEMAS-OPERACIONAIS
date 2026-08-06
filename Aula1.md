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
graph LR
    MULTICS["Multics (1965)<br>• MIT, AT&T e GE<br>• Multiusuário e multitarefa"]
    UNIX["Unix (1969)<br>• Thompson e Ritchie<br>• Base da computação"]
    UNIX_C["Unix em C (1972)<br>• Reescrito em C<br>• Ganhou portabilidade"]
    APPLE2["Apple II (1978)<br>• Popularizou PCs<br>• Padronizou BASIC"]
    MSDOS["MS-DOS (1981)<br>• Lançado com IBM PC<br>• Sistema em linha de comando"]
    MAC_OS["Mac OS (1984)<br>• Interface Gráfica (GUI)<br>• Uso do Mouse"]
    WIN1["Windows 1.0 (1985)<br>• Interface sobre o DOS<br>• Janelas e ícones"]
    MINIX["Minix (1987)<br>• Andrew Tanenbaum<br>• Unix educacional"]
    GNU_HURD["GNU Hurd (1990)<br>• Projeto GNU<br>• Conceito de Microkernel"]
    LINUX["Linux (1991)<br>• Linus Torvalds<br>• Kernel Open Source"]
    WIN_NT["Windows NT (1993)<br>• Arquitetura 32-bits<br>• Foco corporativo e redes"]
    POWERPC["Mac PowerPC (1994)<br>• Mudança de arquitetura<br>• Processadores RISC"]
    REACTOS["ReactOS (1996)<br>• SO Open Source<br>• Compatível com Windows"]
    WINXP["Windows XP (2001)<br>• Unificou NT e 9x<br>• Alta estabilidade"]
    MAC_INTEL["Mac OS Intel (2005)<br>• Transição para Intel<br>• Kernel Darwin"]
    ANDROID["Android (2008)<br>• SO Móvel Linux<br>• Líder em Smartphones"]

    %% Linha do Tempo Central
    MULTICS --- UNIX --- UNIX_C --- APPLE2 --- MSDOS --- MAC_OS --- WIN1 --- MINIX --- GNU_HURD --- LINUX --- WIN_NT --- POWERPC --- REACTOS --- WINXP --- MAC_INTEL --- ANDROID
