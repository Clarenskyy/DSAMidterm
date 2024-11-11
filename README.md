# React JS

## WHAT IS REACT?
React is JavaScript library for building user interfaces created at facebook. It's designed to create reusable UI components, making it efficient to build complex and interactive web applications.

### Key Features of React:
- **Component-Based Architecture**: React promotes building UI components, which are self-contained units of code that encapsulate specific parts of the user interface. This modular approach makes code more organized, reusable, and easier to maintain.   
- **JSX**: React uses JSX, a syntax extension for JavaScript, to write HTML-like structures directly within JavaScript code. This makes it easier to understand and write UI components.   
- **Virtual DOM**: React uses a virtual DOM, a lightweight representation of the actual DOM. When changes are made to the component state, React efficiently updates only the necessary parts of the real DOM, improving performance.   
- **Unidirectional Data Flow**: React follows a unidirectional data flow pattern, making it easier to reason about and debug applications. Changes to the state of a component trigger re-renders, ensuring that the UI always reflects the current data.   

###
- **Efficient and Performant**: React's virtual DOM and efficient rendering techniques lead to high-performance applications.   
- **Reusable Components**: Building reusable components accelerates development and promotes code consistency.   
- **Declarative Programming**: React's declarative style of programming allows you to describe the desired UI state, and React takes care of the updates.   
- **Strong Community and Ecosystem**: React has a large and active community, providing extensive documentation, tutorials, and third-party libraries.   
- **Suitable for Single-Page Applications (SPAs)**: React is well-suited for building SPAs, as it provides the tools and techniques to manage complex user interactions and data flows.

---

## How to Set Up React JS?
   
### Prerequisite Apps

Before installing React JS, you need to have the following software installed on your system:
- **Node.js**: React relies on Node.js for package management (NPM/Yarn). You can download it from [Node.js official website](https://nodejs.org/).
- **Code Editor**: A good code editor like [Visual Studio Code](https://code.visualstudio.com/) is recommended for React development.

### Step-by-Step Installation

1. **Install Node.js and NPM**
   - 
   - Download and install Node.js from [Node.js website](https://nodejs.org/). (Skip to step 2 if node is already installed.)
   - Verify installation:
     ```bash
     node -v
     npm -v
     ```
2. **Create a New React Application**
   - Open your terminal and run the following command:
     ```bash
     npx create-react-app my-custom-react-app
     ```
   - This command creates a new React project named `my-custom-react-app`. It installs all necessary dependencies and sets up the project structure.

3. **Navigate to Your Project Directory**
   ```bash
   cd my-custom-react-app