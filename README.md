# 📝 QuickNotes

A modern, responsive note-taking application built with React and Vite. Create, organize, search, and manage your notes with an intuitive interface and powerful categorization system.

## 🚀 Live Demo

**[View Live Application](https://zingermarat.github.io/QuickNotes/)**

## ✨ Features

- **📝 Create Notes**: Add notes with titles and rich text content
- **🏷️ Categorization**: Organize notes with color-coded categories:
  - 🌫️ General (Gray)
  - 👤 Personal (Green)
  - 💼 Work (Blue)
  - 💡 Ideas (Light Blue)
  - 📚 Study (Yellow)
- **🔍 Smart Search**: Search notes by title or content
- **🎯 Filter by Category**: Filter notes by specific categories
- **✏️ Edit Notes**: Click on any note to edit it in a modal window
- **🗑️ Delete Notes**: Remove notes with confirmation
- **💾 Auto-Save**: Notes are automatically saved to browser's local storage
- **📱 Responsive Design**: Works seamlessly on desktop and mobile devices
- **🌙 Modern UI**: Clean, intuitive interface with smooth animations

## 🛠️ Tech Stack

- **Frontend**: React 19.1.0
- **Build Tool**: Vite 7.0.6
- **Styling**: CSS3 with modern features
- **Components**:
  - `react-modal` - Modal dialogs
  - `react-textarea-autosize` - Auto-resizing text areas
- **Code Quality**: ESLint with React-specific rules
- **Deployment**: GitHub Actions + GitHub Pages

## 🏗️ Project Structure

```
QuickNotes/
├── src/
│   ├── components/
│   │   ├── InputForm.jsx      # Note creation/editing form
│   │   ├── Note.jsx           # Individual note display
│   │   ├── Notes.jsx          # Notes grid container
│   │   ├── ModalWindow.jsx    # Modal wrapper component
│   │   └── SearchBar.jsx      # Search and filter controls
│   ├── App.jsx                # Main application component
│   ├── App.css                # Application styles
│   ├── index.css              # Global styles
│   └── main.jsx               # Application entry point
├── public/                    # Static assets
├── .github/workflows/         # GitHub Actions for deployment
└── dist/                      # Built application (auto-generated)
```

## 🚀 Getting Started

### Prerequisites

- Node.js (version 18 or higher)
- npm or yarn

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/ZingerMarat/QuickNotes.git
   cd QuickNotes
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start development server**

   ```bash
   npm run dev
   ```

4. **Open your browser** and navigate to `http://localhost:5173`

### Building for Production

```bash
npm run build
```

The built files will be in the `dist` directory.

### Preview Production Build

```bash
npm run preview
```

## 📝 Usage

1. **Creating Notes**: Enter a title (optional) and note content, select a category, then click "Add"
2. **Searching**: Use the search bar to find notes by title or content
3. **Filtering**: Select a category from the dropdown to show only notes from that category
4. **Editing**: Click on any note to open it in edit mode
5. **Deleting**: Click the ✖ button on a note and confirm deletion

## 🎨 Categories

Notes are organized into 5 color-coded categories:

| Category | Color       | Use Case                               |
| -------- | ----------- | -------------------------------------- |
| General  | Light Gray  | Everyday notes and reminders           |
| Personal | Mint Green  | Personal thoughts and private notes    |
| Work     | Light Blue  | Work-related tasks and meetings        |
| Ideas    | Sky Blue    | Creative ideas and inspirations        |
| Study    | Pale Yellow | Educational content and learning notes |

## 🔧 Configuration

### Vite Configuration

The project uses Vite with React plugin and is configured for GitHub Pages deployment:

- Development: serves from root `/`
- Production: serves from `/QuickNotes/` (GitHub Pages subdirectory)

### ESLint Configuration

Code quality is maintained with ESLint rules for:

- React best practices
- React Hooks rules
- Modern JavaScript standards

## 🚀 Deployment

This project uses GitHub Actions for automatic deployment to GitHub Pages:

1. **Push to main branch** triggers automatic build and deployment
2. **GitHub Actions** builds the project and deploys to `gh-pages`
3. **Live site** updates automatically at https://zingermarat.github.io/QuickNotes/

### Manual Deployment

```bash
npm run build
npm run deploy
```

## 🌟 Key Features Explained

### Local Storage Persistence

Notes are automatically saved to browser's local storage, ensuring your notes persist between sessions.

### Responsive Grid Layout

Notes are displayed in a responsive grid that adapts to different screen sizes:

- Desktop: 4 columns
- Tablet: 2-3 columns
- Mobile: 1-2 columns

### Modal Editing

Click any note to open it in a full-featured modal editor with:

- Title editing
- Category selection
- Auto-resizing text area
- Update/Cancel options

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Marat Zinger**

- GitHub: [@ZingerMarat](https://github.com/ZingerMarat)

## 🙏 Acknowledgments

- React team for the amazing framework
- Vite team for the lightning-fast build tool
- GitHub for free hosting via GitHub Pages

---

**Made with ❤️ and React**
