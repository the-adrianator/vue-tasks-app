# Vue Tasks App

A modern, type-safe task management application built with Vue 3 and TypeScript. This project demonstrates clean component architecture, reactive state management, and smooth user interactions.

![Vue 3](https://img.shields.io/badge/Vue-3.5.22-4FC08D?logo=vue.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.9.3-3178C6?logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-7.1.7-646CFF?logo=vite&logoColor=white)

## ✨ Features

- ✅ **Add Tasks** - Create new tasks with form validation
- 🎯 **Toggle Completion** - Mark tasks as done or pending
- 🗑️ **Delete Tasks** - Remove tasks with a single click
- 🔍 **Filter Tasks** - View all, active (todo), or completed tasks
- 📊 **Task Counter** - Track your progress with a completion counter
- 🎨 **Smooth Animations** - Beautiful transitions when adding/removing tasks
- 📱 **Responsive Design** - Works seamlessly across all device sizes

## 🛠️ Technologies Used

### Core Framework
- **Vue 3.5.22** - Progressive JavaScript framework with Composition API
- **TypeScript 5.9.3** - Type-safe JavaScript for better developer experience
- **Vite 7.1.7** - Next-generation frontend build tool

### Development Tools
- **@vitejs/plugin-vue** - Official Vue plugin for Vite
- **vue-tsc** - TypeScript type checking for Vue SFCs
- **@vue/tsconfig** - Shared TypeScript configuration for Vue projects

### UI & Icons
- **lucide-vue-next** - Beautiful, customizable icon library
- **Vanilla CSS** - Custom styling with scoped component styles

### Key Features
- **Composition API** with `<script setup>` syntax
- **Strict TypeScript** configuration with comprehensive type checking
- **Reactive State Management** using Vue's reactivity system
- **Component-Based Architecture** for maintainable code

## 🚀 Getting Started

### Prerequisites

- Node.js (v22.21.1 or higher recommended)
- pnpm (or npm/yarn)

### Installation

1. Clone the repository
```bash
git clone https://github.com/the-adrianator/vue-tasks-app.git
cd vue-tasks-app
```

2. Install dependencies
```bash
pnpm install
```

3. Start the development server
```bash
pnpm dev
```

4. Open your browser and navigate to `http://localhost:5173`

### Build for Production

```bash
pnpm build
```

The production build will be generated in the `dist` directory.

### Preview Production Build

```bash
pnpm preview
```

## 📁 Project Structure

```
tasks-app/
├── src/
│   ├── components/
│   │   ├── FilterButton.vue    # Filter button component
│   │   ├── TaskForm.vue         # Task input form
│   │   └── TaskList.vue         # Task list with transitions
│   ├── App.vue                  # Main application component
│   ├── main.ts                  # Application entry point
│   ├── types.ts                 # TypeScript type definitions
│   └── style.css                # Global styles
├── public/                      # Static assets
├── index.html                   # HTML template
├── vite.config.ts               # Vite configuration
└── tsconfig.json                # TypeScript configuration
```

## 🎯 Key Implementation Details

- **Type Safety**: Full TypeScript support with strict type checking
- **Reactive Computed Properties**: Efficient filtering and counting using Vue's computed properties
- **Event-Driven Architecture**: Clean parent-child communication via emits
- **Form Validation**: Client-side validation with user-friendly error messages
- **Smooth Transitions**: Vue's TransitionGroup for list animations
- **Unique IDs**: Uses `crypto.randomUUID()` for task identification

## 🌐 Live Demo

[Deployed on Netlify](https://your-app-name.netlify.app) *(Update with your actual Netlify URL)*

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Adrian**
- GitHub: [@the-adrianator](https://github.com/the-adrianator)

---

Built with ❤️ using Vue 3 and TypeScript
