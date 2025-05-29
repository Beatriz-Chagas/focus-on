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

## Project Structure

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
├── src/
│   ├── index.html          # Main HTML structure
│   ├── css/
│   │   └── style.css       # Stylesheets, including theme variables
│   ├── js/
│   │   ├── app.js          # Main application logic, theme toggling
│   │   └── components/
│   │       ├── todoList.js       # To-Do list functionality
│   │       ├── pomodoroTimer.js  # Pomodoro timer logic
│   │       └── mediaEmbed.js     # Media player embedding
├── package.json            # Project metadata and dependencies
└── README.md               # This file
```

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (which includes npm) installed on your machine.

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/focus-on.git
   ```

   (Replace `yourusername` with your actual GitHub username or the correct repository URL if it's hosted elsewhere.)

2. **Navigate to the project directory:**

   ```bash
   cd focus-on
   ```

3. **Install the dependencies:**
   (This project uses `live-server` as a devDependency, as specified in `package.json`.)

   ```bash
   npm install
   ```

### Running the Application

1. **Start the development server:**

   ```bash
   npm start
   ```

   This command will execute the `start` script defined in `package.json` (which is `live-server src`). It will typically open the application in your default web browser, often at `http://127.0.0.1:8080`.

2. **Alternatively, you can open `src/index.html` directly in your web browser.** However, using `npm start` is recommended to take advantage of `live-server`'s features like automatic reloading.

## How to Use

- **Toggle Theme**: Click the "Alternar Tema" (Toggle Theme) button, usually found at the top-right of the page, to switch between light and dark modes.
- **Manage Tasks**: In the "To-Do List" section, type your task into the input field and click the "Add Task" button.
- **Use Pomodoro Timer**: In the "Pomodoro Timer" section, click "Start" to begin a focus session. Use the "Stop" and "Reset" buttons as needed.
- **Listen to Music**: The embedded media player in the "Listen to Lofi" section should be ready to play.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

### For Workshop Participants

This project is specifically designed for learning how to contribute to Open Source projects using GitHub Copilot Agent as your intelligent partner.

#### How to Contribute

1. **Fork the Project**
2. **Clone your fork**: `git clone https://github.com/yourusername/focus-on.git`
3. **Create your Feature Branch**: `git checkout -b feature/AmazingFeature`
4. **Choose an Issue**: Look for issues labeled `good-first-issue`, `help-wanted`, or `workshop`
5. **Use GitHub Copilot Agent**: Let AI help you understand the codebase and implement features
6. **Commit your Changes**: `git commit -m 'Add some AmazingFeature'`
7. **Push to the Branch**: `git push origin feature/AmazingFeature`
8. **Open a Pull Request**

### Issue Labels

- 🟢 `good-first-issue` - Perfect for beginners
- 🆘 `help-wanted` - We need community help
- 🎓 `workshop` - Designed for workshop participants
- 🐛 `bug` - Something isn't working
- ✨ `enhancement` - New feature or request
- 📚 `documentation` - Improvements to docs
- 🎨 `design` - Design and UX improvements

### Getting Help

- Use **GitHub Copilot Agent** to understand code and get implementation suggestions
- Ask questions in the issue comments
- Check out the [Code of Conduct](CODE_OF_CONDUCT.md)
- Read our [Contributing Guidelines](CONTRIBUTING.md)

## License

Distributed under the MIT License. See the `LICENSE` file (you may need to create one if it doesn't exist) for more information.

## Author

- **Your Name** - *Initial work* - (e.g., `Pachicodes` or your GitHub profile link)

---

*Remember to replace placeholders like `yourusername`, `Your Name`, and potentially add a `LICENSE` file if you intend to distribute this project more formally.*
