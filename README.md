# `monaco-mermaid`

Package for MermaidJS syntax highlighting implemented in the Monaco Editor.

## Usage

The ID of the language created will be `mermaid`. There will also be two themes that extend the base themes of `vs` and `vs-dark` named `mermaid` and `mermaid-dark` respectively.

```js
import initEditor from 'monaco-mermaid';

initEditor(); // Defines required themes and languages
```
