# Important features that one should know while using tailwind css.

## 1. Utility-First Framework

Tailwind is a utility-first CSS framework packed with classes like flex, pt-4, text-center and rotate-90 that can be composed to build any design, directly in your markup ( HTML ).

In programming, a **utility function** is a helper function that performs a common task, often used to avoid code duplication. These functions are typically small, reusable, and focused on a specific task.

- Tailwind CSS provides utility classes for styling elements directly in the HTML.

- Example: Instead of writing custom CSS, you use classes like **`bg-blue-500`**, **`text-center`**, **`p-4`** etc.

## 2. Customization with Configuration

- Tailwind allows you to customize colors, fonts, spacing, and more using the **`tailwind.config.js`** file.

```javascript
module.exports = {
  theme: {
    extend: {
      colors: {
        customBlue: "#1E40AF",
      },
    },
  },
};
```

- Use **`bg-customBlue`** in your classes.
