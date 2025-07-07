# 🚀 Angular Parent-Child Communication Demo

A simple Angular application demonstrating **@Input** and **@Output** decorators for component communication.

## 📋 Features

- ✅ **Parent Component** with input field and send button
- ✅ **Child Component** that receives data via `@Input`
- ✅ **Event emission** from child to parent via `@Output`
- ✅ **Real-time communication** between components
- ✅ **Modern Angular 20** with standalone components
- ✅ **TypeScript** with proper type definitions
- ✅ **Responsive UI** with gradient background

## 🎯 How It Works

1. **Parent → Child**: User types a name and clicks "Send Name to Child"
2. **@Input**: Child component receives the name property
3. **Child displays**: "Received name: [NAME]"
4. **@Output**: Child emits greeting event back to parent
5. **Parent displays**: Greeting message from child

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ installed
- Angular CLI installed globally

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/MishalSaleem/angular-parent-child-app.git
   cd angular-parent-child-app
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start development server:**
   ```bash
   ng serve
   ```
   OR
   ```bash
   npm start
   ```

4. **Open your browser:**
   Navigate to `http://localhost:4200`

## 📸 Screenshots

### Main Application
![Main App](screenshots/main-app.png)
*Angular Parent-Child Communication Demo with gradient background*

### Parent Component
![Parent Component](screenshots/parent-component.png)
*Parent component with input field and send button*

### Child Component Interaction
![Child Component](screenshots/child-interaction.png)
*Child component receiving @Input and emitting @Output events*

### Complete Communication Flow
![Communication Flow](screenshots/communication-flow.png)
*Full parent-child communication demonstration*

## 🎮 How to Use the App

1. **Enter a name** in the input field (e.g., "John")
2. **Click "Send Name to Child"** button
3. **Observe** the child component displays: "Received name: John"
4. **Click "Send Greeting Back"** in the child component
5. **See** the parent displays: "Received: Hello, John! Nice to meet you."
6. **Use "Clear All"** to reset and try again

## 🔧 Running the Project (Multiple Methods)

### Method 1: Using Batch File (Windows)
- **Double-click** `start-app.bat` in the project folder

### Method 2: Command Line
```bash
cd angular-app
ng serve --open
```

### Method 3: VS Code
- Open project in VS Code
- Open terminal (`Ctrl + \``)
- Run: `ng serve`

### Method 4: npm Scripts
```bash
npm start    # Starts development server
npm run build    # Builds for production
npm test     # Runs unit tests
```

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
