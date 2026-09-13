# 🚀 Dev Stack

Dev Stack is a modern web application that helps users explore different web development technologies and build their own personalized developer stack.

## 📌 Project Description

Dev Stack allows users to browse various web development technologies and select the technologies they want to include in their own developer stack.

The application provides a clean, responsive, and user-friendly interface for managing the selected technologies.

## 🛠️ Technologies Used

* ⚛️ React
* 🟦 TypeScript
* 🎨 Tailwind CSS
* ⚡ Vite
* 🔔 React Toastify

## ✨ Features

### 1. 🔍 Explore Technologies

Users can browse and explore different web development technologies with useful information about each technology.

### 2. 🧩 Build Your Own Stack

Users can add technologies to their personal developer stack and remove them whenever they want.

### 3. 📱 Responsive & User-Friendly

The application is designed with a clean and responsive interface that works smoothly across different screen sizes.

---

# 📚 React Questions & Answers

### 1. What is JSX, and why is it used in React?

JSX is a syntax that allows us to write HTML-like code inside JavaScript or TypeScript. It makes React components easier to read, write, and understand.

### 2. What is the difference between props and state?

**Props** are data passed from a parent component to a child component.
**State** is data managed inside a component that can change over time.

### 3. What does the `useState` hook do, and where did you use it in this project?

The `useState` hook is used to store and update data that can change in a React component.

In this project, I used `useState` to manage the selected technologies in the user's developer stack.

### 4. What is `useEffect` used for in React?

`useEffect` is used to handle side effects in React, such as fetching data, subscriptions, or updating external systems. It runs after a component renders.

In this project, I did not use `useEffect`. Instead, the technology data is loaded using a Promise, React's `use()` hook, and `Suspense`.

### 5. Why does every item in a `.map()` list need a unique `key` prop?

React uses the `key` to identify each item in a list. A unique key helps React efficiently update, add, or remove the correct item when the list changes.

### 6. What is conditional rendering? Show one place you used it.

Conditional rendering means displaying different UI based on a condition.

In this project, when the user's stack is empty, an **empty stack message** is displayed. When technologies are selected, the selected technologies are shown instead.

### 7. How do you pass data from a parent component to a child component, and how does a child send something back to the parent?

A parent component passes data to a child component using **props**.

A child component can send something back to the parent by calling a **function passed through props**. This allows the child to communicate an action or data back to the parent.

---

## 💡 Conclusion

Dev Stack is a simple and interactive project that demonstrates important React concepts such as components, props, state management, conditional rendering, list rendering, and parent-child communication.
