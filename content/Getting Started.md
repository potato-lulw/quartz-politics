Obsidian is a popular note-taking app that supports **Markdown** syntax. Here is a comprehensive list of Markdown formatting syntax commonly used in Obsidian:

### 1. **Headings**
- `# Heading 1`
- `## Heading 2`
- `### Heading 3`
- `#### Heading 4`
- `##### Heading 5`
- `###### Heading 6`

### 2. **Bold and Italic**
- **Bold**: `**bold**` or `__bold__`
- *Italic*: `*italic*` or `_italic_`
- ***Bold and Italic***: `***bold and italic***` or `___bold and italic___`

### 3. **Strikethrough**
- Strikethrough: `~~strikethrough~~`

### 4. **Lists**
- **Unordered List**: 
    - `- Item 1`
    - `- Item 2`
    - `- Item 3`
- **Ordered List**: 
    - `1. First item`
    - `2. Second item`
    - `3. Third item`
- **Task List**:
    - `- [ ] Task to do`
    - `- [x] Completed task`

### 5. **Links**
- **Internal Links**: `[[Note Title]]` (Links to another note in the vault)
- **External Links**: `[link text](https://example.com)`

### 6. **Images**
- `![[image.png]]` (for images stored locally in your vault)
- `![alt text](https://example.com/image.png)` (for images from the web)

### 7. **Block Quotes**
- `> This is a block quote`

### 8. **Code Blocks**
- **Inline Code**: `` `inline code` ``
- **Code Block**:
    ````
    ```
    Code block content
    ```
    ````

### 9. **Highlight**
- Highlight: `==highlighted text==`

### 10. **Tables**
```markdown
| Header 1 | Header 2 |
| -------- | -------- |
| Row 1    | Data     |
| Row 2    | More Data|
```

### 11. **Footnotes**
- `Here is some text[^1]`
- `[^1]: Footnote explanation.`

### 12. **Horizontal Line**
- `---`

### 13. **Comments**
- Obsidian supports HTML-style comments:
  ```html
  <!-- This is a comment -->
  ```

### 14. **Embed Files (PDFs, Notes, Images)**
- Embed another note: `![[Note Title]]`
- Embed PDF: `![[pdf-file.pdf]]`
- Embed an image: `![[image.png]]`

### 15. **Math (LaTeX)**
- Inline math: `$y = mx + b$`
- Block math:
    ```
    $$
    E = mc^2
    $$
    ```

### 16. **Callouts**
- Obsidian has custom callouts, with a format like:
    ```
    > [!note]
    > This is a note callout.
    ```
  Replace "note" with types like "tip", "warning", "info", etc.

### 17. **Tags**
- `#tag` (creates a tag that can be searched or linked)

This is the core Markdown syntax and some Obsidian-specific extensions.