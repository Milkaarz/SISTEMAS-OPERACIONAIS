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

# Linha do Tempo da Evolução dos Sistemas Operacionais

Uma visão cronológica e detalhada dos principais marcos na história dos Sistemas Operacionais (SOs), desde os primeiros processadores de lote até a era da computação em nuvem e mobile.

---

```
                       [ LINHA DO TEMPO DOS SISTEMAS OPERACIONAIS ]
                                            |
    +-------------------+-------------------+-------------------+-------------------+
    |                   |                   |                   |                   |
[ Anos 50-60 ]      [ Anos 70 ]         [ Anos 80 ]         [ Anos 90 ]     [ Anos 2000+ ]
  Primeiros SOs       Unix & BSD        Interface Gráfica    Linux & Web      Mobile & Nuvem
```

---

## 📅 Destaques por Década

### 1. Década de 1950 – Processamento em Lote (Batch Processing)
> *Nesta época, não havia interfaces gráficas ou interação em tempo real. Os programas eram inseridos via cartões perfurados.*

- **1956 — GM-NAA I/O**
  - **Desenvolvedor:** General Motors / North American Aviation para IBM 704.
  - **Impacto:** Considerado o **primeiro sistema operacional da história**. Executava tarefas em lote (*batch processing*), reduzindo o tempo ocioso entre a execução de programas.

---

### 2. Década de 1960 – Compartilhamento de Tempo e Multiprogramação

- **1961 — CTSS (Compatible Time-Sharing System)**
  - **Desenvolvedor:** MIT.
  - **Impacto:** Um dos primeiros sistemas de **compartilhamento de tempo** (*time-sharing*), permitindo que múltiplos usuários utilizassem o mesmo computador simultaneamente.

- **1965 — OS/360**
  - **Desenvolvedor:** IBM.
  - **Impacto:** Padronizou o SO para toda a linha de mainframes IBM System/360, introduzindo conceitos modernos de gerenciamento de memória e multiprogramação.

- **1969 — Multics (Multiplexed Information and Computing Service)**
  - **Desenvolvedores:** MIT, Bell Labs e General Electric.
  - **Impacto:** Pioneiro em segurança por camadas e sistemas de arquivos hierárquicos. Apesar de complexo, serviu de inspiração direta para o Unix.

---

### 3. Década de 1970 – A Era Unix e o Nascimento do Software Moderno

- **1969/1970 — Unix**
  - **Criadores:** Ken Thompson, Dennis Ritchie, Douglas McIlroy e Joe Ossanna (AT&T Bell Labs).
  - **Impacto:** Escrito posteriormente em linguagem C (1973), tornou-se portátil, modular e influenciou virtualmente todos os sistemas operacionais modernos (Linux, macOS, iOS, Android).

- **1974 — CP/M (Control Program for Microcomputers)**
  - **Criador:** Gary Kildall (Digital Research).
  - **Impacto:** O primeiro SO padrão para microcomputadores de 8 bits baseados nos processadores Intel 8080/Z80.

- **1977 — BSD (Berkeley Software Distribution)**
  - **Desenvolvedor:** Universidade de Califórnia, Berkeley.
  - **Impacto:** Derivado do Unix, trouxe avanços fundamentais como a pilha de protocolos TCP/IP integrada.

- **1978 — Apple DOS**
  - **Desenvolvedor:** Apple Computer (para o Apple II).
  - **Impacto:** Popularizou o uso de disquetes de 5,25 polegadas no mercado de computadores pessoais.

---

### 4. Década de 1980 – Computação Pessoal e Interfaces Gráficas (GUI)

- **1980 — Xenix**
  - **Desenvolvedor:** Microsoft.
  - **Impacto:** Uma versão licenciada do Unix adaptada para microcomputadores.

- **1981 — MS-DOS (Microsoft Disk Operating System)**
  - **Desenvolvedor:** Microsoft (baseado no 86-DOS de Tim Paterson).
  - **Impacto:** Tornou-se o SO padrão dos computadores IBM PC e dominou o mercado de PCs durante toda a década de 80.

- **1984 — Mac OS (System 1)**
  - **Desenvolvedor:** Apple.
  - **Impacto:** Popularizou em massa a **Interface Gráfica do Usuário (GUI)** com janelas, ícones, menus e o uso do mouse.

- **1985 — Windows 1.0**
  - **Desenvolvedor:** Microsoft.
  - **Impacto:** Primeira tentativa da Microsoft de criar uma interface gráfica, rodando como uma extensão sobre o MS-DOS.

- **1987 — OS/2**
  - **Desenvolvedores:** IBM e Microsoft.
  - **Impacto:** Criado para suceder o MS-DOS com multitarefa preempitiva, embora mais tarde a parceria tenha sido desfeita.

- **1987 — MINIX**
  - **Criador:** Andrew S. Tanenbaum.
  - **Impacto:** Sistema educacional baseado em microkernel criado para ensinar SOs, servindo de inspiração para Linus Torvalds.

---

### 5. Década de 1990 – A Revolução Open Source e a Era da Internet

- **1991 — Linux (Kernel)**
  - **Criador:** Linus Torvalds.
  - **Impacto:** Kernel código aberto de licença GPL que, combinado com as ferramentas GNU, deu origem às distribuições Linux. Hoje domina servidores, supercomputadores e dispositivos móveis.

- **1993 — Windows NT (New Technology)**
  - **Desenvolvedor:** Microsoft.
  - **Impacto:** Arquitetura totalmente nova de 32 bits voltada para redes e corporações. Base de todas as versões do Windows a partir do Windows XP.

- **1995 — Windows 95**
  - **Desenvolvedor:** Microsoft.
  - **Impacto:** Marco na história dos PCs. Introduziu o **Menu Iniciar**, a **Barra de Tarefas**, nomes de arquivos longos e suporte a *Plug and Play*.

- **1996 — Windows CE**
  - **Desenvolvedor:** Microsoft.
  - **Impacto:** Plataforma para dispositivos embarcados e computadores de mão (PDAs).

- **1998 — Windows 98**
  - **Desenvolvedor:** Microsoft.
  - **Impacto:** Maior integração com a Web (Internet Explorer) e suporte aprimorado a dispositivos USB.

---

### 6. Década de 2000 – Unificação, Estabilidade e Dispositivos Móveis

- **2001 — Mac OS X (Cheetah)**
  - **Desenvolvedor:** Apple.
  - **Impacto:** Reconstrução completa do sistema da Apple baseada no NeXTSTEP e Unix (BSD), trazendo a interface Aqua e estabilidade industrial.

- **2001 — Windows XP**
  - **Desenvolvedor:** Microsoft.
  - **Impacto:** Unificou a linha doméstica (Windows 9x) com a linha corporativa (Windows NT), tornando-se uma das versões mais populares da história.

- **2007 — iOS (originalmente iPhone OS)**
  - **Desenvolvedor:** Apple.
  - **Impacto:** Revolucionou os smartphones ao introduzir uma interface 100% projetada para telas multitoque (*multi-touch*).

- **2008 — Android OS**
  - **Desenvolvedor:** Android Inc. / Google.
  - **Impacto:** Sistema móvel *open-source* baseado no kernel Linux. Tornou-se o sistema operacional mais utilizado no planeta em número de dispositivos.

- **2009 — ChromeOS**
  - **Desenvolvedor:** Google.
  - **Impacto:** SO leve focado em armazenamento e aplicações em nuvem, rodando sobre o navegador Chrome.

---

### 7. Década de 2010 até os dias atuais – Computação Ubíqua, Nuvem e IA

- **2015 — Windows 10**
  - **Desenvolvedor:** Microsoft.
  - **Impacto:** Transição do Windows para o modelo "SISTEMA COMO SERVIÇO" (*Windows as a Service*), com atualizações contínuas e integração multiplataforma.

- **2020 — Apple Silicon macOS (macOS Big Sur em diante)**
  - **Desenvolvedor:** Apple.
  - **Impacto:** Transição da Apple dos chips Intel para processadores ARM próprios (M1/M2/M3), unificando a arquitetura entre iOS e macOS.

- **2021 — Windows 11**
  - **Desenvolvedor:** Microsoft.
  - **Impacto:** Nova interface centralizada, suporte a aplicativos Android nativos via subsistema e foco em produtividade e IA.

---

## 📊 Resumo Comparativo das Famílias de SOs

| Família / Linhagem | Ancestral Direto | Principais Exemplos Atuais | Foco Principal |
| :--- | :--- | :--- | :--- |
| **Unix-like (POSIX)** | AT&T Unix / BSD | macOS, iOS, watchOS | Desktops Apple, Dispositivos Móveis |
| **Linux-based** | Linux Kernel / GNU | Ubuntu, Debian, Android, ChromeOS | Servidores, Mobile, IOT, Nuvem |
| **Windows NT** | Windows NT 3.1 / VMS | Windows 10, Windows 11, Windows Server | Desktops PCs, Corporativo |
