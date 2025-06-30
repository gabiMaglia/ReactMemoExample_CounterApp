# ⚡️ React Counter App - Optimización con memo, useCallback y useMemo

📌 **Descripción (Español)**  
Este proyecto es una app simple de contador desarrollada con **React 19**, diseñada para **practicar técnicas de optimización de rendimiento** mediante:

- 🔁 `React.memo`: para evitar renders innecesarios de componentes hijos
- 🧠 `useMemo`: para memorizar valores computados costosos
- 🔗 `useCallback`: para evitar que se generen nuevas referencias de funciones en cada render

A través de una arquitectura simple, se demuestra cómo estos tres mecanismos permiten reducir el número de renders, mejorar la eficiencia y preparar una app para escalar sin degradar su performance.

---

📌 **Description (English)**  
This project is a simple **counter app** built with **React 19**, created to **practice performance optimization techniques** using:

- 🔁 `React.memo`: to prevent unnecessary re-renders of child components
- 🧠 `useMemo`: to memoize expensive computed values
- 🔗 `useCallback`: to retain function references between renders

Through a simple structure, the project demonstrates how these three mechanisms can reduce render frequency, boost performance, and help prepare an application for future scalability.

---

## 🚀 Tecnologías / Tech Stack

- React 19  
- Vite  
- JavaScript (ES6+)  
- CSS

---

## ⚙️ Funcionalidades / Features

- ➕ Incremento / decremento de contador
- 🔁 Función de reseteo del contador
- 🧠 Lógica optimizada con `useMemo` y `useCallback`
- 🔍 Observación del comportamiento de renders vía consola
- 🔧 Componentes memorizados con `React.memo`

---

## 🧪 Instalación / Installation

```bash
npm install
npm run dev
