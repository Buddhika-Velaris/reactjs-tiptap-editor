<p align="center">
<a href="https://github.com/yourusername/your-unique-tiptap-editor" target="_blank" rel="noopener noreferrer">
<img src="https://api.iconify.design/ic:round-wysiwyg.svg?color=%23bbdf58" alt="logo" width='100'/></a>
</p>

<p align="center">
 A modern WYSIWYG rich-text editor based on Tiptap using Shadcn components.
</p>

<p align="center">
  <a href="https://github.com/yourusername/your-unique-tiptap-editor/blob/main/LICENSE" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License" /></a>
</p>

![App Screenshot](./screenshot/screenshot.png)

## About This Project

This rich text editor is a fork of [reactjs-tiptap-editor](https://github.com/hunghg255/reactjs-tiptap-editor) by [hunghg255](https://github.com/hunghg255), modified to suit my specific needs. The original project is licensed under MIT, and this modified version maintains that license with proper attribution.

## Features

- Rich text editing with multiple formatting options
- Image, GIF, and attachment support
- Tables, code blocks, and mathematical formulas
- Expandable drawers and embeds
- Export to PDF and Word
- Multiple themes and customizable UI
- And much more!

## Installation

```bash
npm install your-unique-tiptap-editor
# or
yarn add your-unique-tiptap-editor
# or
pnpm add your-unique-tiptap-editor
```

## Basic Usage

```jsx
import React from 'react';
import { RichTextEditor } from 'your-unique-tiptap-editor';
import 'your-unique-tiptap-editor/style.css';

function App() {
  return (
    <div>
      <RichTextEditor />
    </div>
  );
}

export default App;
```

## Run Locally

Clone the project

```bash
git clone https://github.com/yourusername/your-unique-tiptap-editor.git
```

Go to the project directory

```bash
cd your-unique-tiptap-editor
```

Install dependencies

```bash
pnpm install
```

Start the Demo server

```bash
npm run build:lib:dev
npm run playground
```

## Acknowledgements

This project is based on the excellent work done by [hunghg255](https://github.com/hunghg255) on the original [reactjs-tiptap-editor](https://github.com/hunghg255/reactjs-tiptap-editor).

## Related

Here are some related projects

[Tiptap](https://tiptap.dev)

[Shadcn](https://ui.shadcn.com/)

[echo-editor](https://github.com/Seedsa/echo-editor)

## License

[MIT](./LICENSE)
