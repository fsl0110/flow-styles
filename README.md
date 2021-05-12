# This project is deprecated!!!

> Please use Tailwind, Tachyions or Atomic CSS instead.

## How to use FlowStyles?

1. Define your Project-Styleguide like Colors, Text, Headings, Borders and Spacings. You can also mix your Styleguide with the predefined Styleguide.
2. Use FlowStyles classes in your HTML, Lit-HTML or JSX and combine it with usual Sass where necessary.
3. Use PurgeCSS to remove unused CSS-Classes. Don’t use FlowStyles without removing unused CSS-Classes. Otherwise you will get a huge CSS-File full of unused CSS classes!!!

## Available Scripts

In the project directory, you can run:

### `npm run storybook` or `yarn storybook`

Runs the FlowStyles-Storybook in the development mode.<br>
Open [http://localhost:6006](http://localhost:6006) to view it in the browser.

### `npm run storybook:build` or `yarn storybook:build`

Builds the FlowStyles-Storybook in the storybook-static folder.

### `npm run storybook:serve` or `yarn storybook:serve`

Runs the FlowStyles-Storybook build<br>
Open [http://localhost:5000](http://localhost:5000) to view it in the browser.

### `npm run storybook:build:serve` or `yarn storybook:build:serve`

Build the FlowStyles-Storybook and runs it on [http://localhost:5000](http://localhost:5000).

### `npm run lint` or `yarn lint`

Execute Stylelint
