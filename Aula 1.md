## 🎯 Conteúdos Abordados

- Conceito e prática de **Commit**
- Mapeamento e ideação com o **Miro**
- Upload de arquivos no **GitHub**
- Formatação e estilização de repositórios com **Markdown**

---

## 📌 1. O que é Commit?

O **commit** funciona como um "ponto de salvamento" (*checkpoint*) no histórico do seu projeto. Sempre que você realiza uma alteração relevante no código ou nos arquivos e faz um commit, você está registrando o estado exato do projeto naquele momento.

* **Boas práticas de mensagens de commit:**
  * Seja claro e direto.
  * Use verbos no imperativo ou presente (ex: `Adiciona layout inicial`, `Corrige bug no login`).
  * Mantenha um histórico legível para você e sua equipe.

---

## 🎨 2. Uso da Ferramenta Miro

O **Miro** é uma plataforma de lousa virtual colaborativa utilizada para planejar visualmente os projetos antes ou durante o desenvolvimento.

### Para que utilizamos:
- Criar **fluxogramas** e diagramas de arquitetura.
- Organizar ideias com **post-its digitais** e mapas mentais.
- Fazer sessões de *brainstorming* em equipe.
- Definir *wireframes* e telas iniciais do projeto.

---

## 📤 3. Upload de Arquivos no GitHub

Na aula, aprendemos como enviar arquivos para a nuvem através do GitHub, garantindo backup e versionamento do projeto.

### Formas de envio:
1. **Via Interface Web:**
   - Navegue até o repositório.
   - Clique em `Add file` > `Upload files`.
   - Arraste os arquivos, escreva a mensagem de commit e confirme.

2. **Via Terminal / Linha de Comando (Git):**
   ```bash
   # Adiciona os arquivos para a área de preparação (staging)
   git add .

   # Cria o registro das alterações com uma mensagem
   git commit -m "feat: adiciona arquivos da aula de hoje"

   # Envia as alterações para o repositório remoto
   git push origin main
