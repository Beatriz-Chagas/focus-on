# Focus On

> 🎯 **Projeto Workshop**: Contribuindo com Open Source com a ajuda do GitHub Copilot (Agent Mode)

Uma aplicação web projetada para ajudar os usuários a aumentar a produtividade e manter o foco através de um conjunto de ferramentas simples e eficazes. Este app combina uma lista de tarefas, um timer Pomodoro e um player de música lofi embutido, tudo em uma interface limpa e moderna com opções de modo claro e escuro.

**Este projeto é usado como exemplo prático para ensinar contribuições Open Source com GitHub Copilot Agent.**

## 🎯 Workshop: Contribuindo com Open Source

Este projeto foi especialmente preparado para o workshop **"Contribuindo com Open Source com a ajuda do GitHub Copilot (Agent Mode)"**.

### Para Participantes do Workshop

1. **Faça um fork deste repositório** para sua conta GitHub
2. **Clone seu fork** para sua máquina local
3. **Escolha uma issue** marcada com `good-first-issue` ou `workshop`
4. **Use o GitHub Copilot Agent** para entender o código e implementar melhorias
5. **Abra um Pull Request** com suas contribuições

### Issues Disponíveis

Criamos issues de diferentes níveis de dificuldade:

- 🟢 **Iniciante**: Issues marcadas com `good-first-issue`
- 🟡 **Intermediário**: Issues de complexidade média
- 🔴 **Avançado**: Issues que requerem mais experiência
- 🎨 **Design/UX**: Melhorias visuais e de experiência do usuário

## Funcionalidades

- **📝 Lista de Tarefas**: Adicione, gerencie e acompanhe suas tarefas facilmente.
- **🍅 Timer Pomodoro**: Trabalhe em intervalos focados de 25 minutos com pausas curtas, personalizável para seu fluxo de trabalho.
- **🎧 Player de Música Lofi**: Incorpore suas playlists favoritas do Spotify (ou outras mídias) para criar uma atmosfera relaxante de trabalho.
- **☀️/🌙 Modo Claro e Escuro**: Alterne entre temas claro e escuro para conforto visual ideal a qualquer hora do dia.
- **🎨 Interface Moderna**: Interface de usuário esteticamente agradável e intuitiva.

## Tecnologias Utilizadas

- **Frontend**: HTML, CSS, JavaScript Vanilla
- **Servidor de Desenvolvimento**: `live-server` (via scripts npm)

## Estrutura do Projeto

```text
focus-on/
├── manifest.json        # Configuração para extensão do Chrome
├── icons/               # Ícones da aplicação
├── src/                 # Código-fonte principal
│   ├── index.html       # Estrutura HTML principal
│   ├── css/             # Estilos CSS
│   │   └── style.css    # Estilos principais + temas claro/escuro
│   └── js/              # Lógica JavaScript
│       ├── app.js       # Lógica principal da aplicação
│       ├── todoList.js  # Funcionalidade da lista de tarefas
│       └── components/  # Componentes reutilizáveis
│           ├── mediaEmbed.js     # Player de música
│           ├── pomodoroTimer.js  # Timer Pomodoro
│           └── todoList.js       # Componente de lista de tarefas (legado)
├── package.json            # Metadados do projeto e dependências
└── README.md               # Este arquivo
```

## Começando

### Pré-requisitos

- [Node.js](https://nodejs.org/) (que inclui npm) instalado em sua máquina.

### Instalação

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/seuusuario/focus-on.git
   ```

   (Substitua `seuusuario` pelo seu nome de usuário real do GitHub ou a URL correta do repositório se estiver hospedado em outro lugar.)

2. **Navegue até o diretório do projeto:**

   ```bash
   cd focus-on
   ```

3. **Instale as dependências:**
   (Este projeto usa `live-server` como devDependency, conforme especificado no `package.json`.)

   ```bash
   npm install
   ```

### Executando a Aplicação

1. **Inicie o servidor de desenvolvimento:**

   ```bash
   npm start
   ```

   Este comando executará o script `start` definido no `package.json` (que é `live-server src`). Normalmente abrirá a aplicação em seu navegador padrão, geralmente em `http://127.0.0.1:8080`.

2. **Alternativamente, você pode abrir `src/index.html` diretamente em seu navegador.** No entanto, usar `npm start` é recomendado para aproveitar os recursos do `live-server` como recarregamento automático.

## Como Usar

- **Alternar Tema**: Clique no botão "☀️/🌙" (Alternar Tema), geralmente localizado no canto superior direito da página, para alternar entre os modos claro e escuro.
- **Gerenciar Tarefas**: Na seção "Lista de Tarefas", digite sua tarefa no campo de entrada e clique no botão "Adicionar Tarefa".
- **Usar Timer Pomodoro**: Na seção "Timer Pomodoro", clique em "Iniciar" para começar uma sessão de foco. Use os botões "Pausar" e "Reiniciar" conforme necessário.
- **Ouvir Música**: O player de mídia incorporado na seção "Música Lofi" deve estar pronto para reproduzir.

## Contribuindo

As contribuições são o que tornam a comunidade open source um lugar incrível para aprender, inspirar e criar. Qualquer contribuição que você fizer será **muito apreciada**.

### Para Participantes do Workshop

Este projeto foi especificamente projetado para ensinar como contribuir com projetos Open Source usando o GitHub Copilot Agent como seu parceiro inteligente.

#### Como Contribuir

1. **Faça um Fork do Projeto**
2. **Clone seu fork**: `git clone https://github.com/seuusuario/focus-on.git`
3. **Crie sua Feature Branch**: `git checkout -b feature/FuncionalidadeIncrivel`
4. **Escolha uma Issue**: Procure por issues rotuladas como `good-first-issue`, `help-wanted`, ou `workshop`
5. **Use o GitHub Copilot Agent**: Deixe a IA ajudar você a entender a base de código e implementar funcionalidades
6. **Commit suas Mudanças**: `git commit -m 'Add: alguma FuncionalidadeIncrivel'`
7. **Push para a Branch**: `git push origin feature/FuncionalidadeIncrivel`
8. **Abra um Pull Request**

### Labels das Issues

- 🟢 `good-first-issue` - Perfeito para iniciantes
- 🆘 `help-wanted` - Precisamos de ajuda da comunidade
- 🎓 `workshop` - Projetado para participantes do workshop
- 🐛 `bug` - Algo não está funcionando
- ✨ `enhancement` - Nova funcionalidade ou solicitação
- 📚 `documentation` - Melhorias na documentação
- 🎨 `design` - Melhorias de design e UX

### Obtendo Ajuda

- Use o **GitHub Copilot Agent** para entender código e obter sugestões de implementação
- Faça perguntas nos comentários das issues
- Confira o [Código de Conduta](CODE_OF_CONDUCT.md)
- Leia nossas [Diretrizes de Contribuição](CONTRIBUTING.md)

## Licença

Distributed under the MIT License. See the `LICENSE` file (you may need to create one if it doesn't exist) for more information.

## Author

- **Your Name** - *Initial work* - (e.g., `Pachicodes` or your GitHub profile link)

---

*Remember to replace placeholders like `yourusername`, `Your Name`, and potentially add a `LICENSE` file if you intend to distribute this project more formally.*
