This project represents a modern website for the company "Nothing," which includes various sections such as recommended products, categories, company information, and a contact form. The website features a responsive design, ensuring an excellent appearance across different devices, including desktops, tablets, and mobile phones. The site is built using the following technologies:

HTML5: The primary structure of the pages and semantic placement of elements.
SCSS (Sass): The styling is done using the Sass preprocessor, which allows for efficient organization of CSS code through variables, mixins, and nested styles. This ensures better support for responsive design and flexible styling adjustments.
Flexbox and Grid Layout: Applied to create a responsive and flexible page structure, ensuring proper content display on various devices.
SVG: Used for icons and logos, providing high-quality graphics at different scales.
Responsive Design: The site is optimized for proper display on various screens, from mobile devices to large monitors.
- [DEMO LINK](https://seriuksergii.github.io/nothing-landing-page/)
- [LINK ON LAYOUT](https://www.figma.com/file/DtkQmQ797hk0nI4KfMi2Uq/BOSE-New-Version?type=design&node-id=6802-139&t=L7eKz5YKLN0m5WxR-0)

How to Run the Project
Clone the Repository:

git clone https://github.com/SeriukSergii/nothing-landing-page.git

cd nothing-landing-page

Install Dependencies:
Make sure you have Node.js installed. Then run:
npm install

Run the Project:
Start the development server with:

npm start

The project should now be running on http://localhost:3000.
ч

# React + Redux list of TODOs

> ❗ Read the lesson theory before solving this task

You are given an `app` folder with already implemented `store` and `hooks`.
Use them to implement [Dynamic list of TODOs](https://github.com/mate-academy/react_dynamic-list-of-todos#react-dynamic-list-of-todos)
using the Redux. It should look and work identically, so use the same markup.

> Here is [the working version](https://mate-academy.github.io/react_redux-list-of-todos/)

- `features/currentTodo` contains a sample of all the required types;
- implement `features/filter` storing `query` and `status`;
- implement `features/todos` storing an array of todos;
- load the todos in the `App` on page load (don't use Redux Thunk for now);
- `useAppSelector` already aware of `RootState` so you can write selectors in your
  components (no need to write them in the store file)

## Instructions

- Install Prettier Extention and use this [VSCode settings](https://mate-academy.github.io/fe-program/tools/vscode/settings.json) to enable format on save.
- Replace `<your_account>` with your Github username in the [DEMO LINK](https://seriuksergii.github.io/react_redux-list-of-todos/)
- Follow the [React task guideline](https://github.com/mate-academy/react_task-guideline#react-tasks-guideline)

