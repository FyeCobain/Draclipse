# Draclipse - theme configuration for the Eclipse IDE or Spring Tool Suite

## Version
> **0.3.1**

## Custom color palette
> * **IDE Background blue**: #2080a4 > rgb(32, 128, 164)
> * **Light Gray**: #e1e1e1 > rgb(225, 225, 225)
> * **Light Yellow**: #e1e100 > rgb(225, 225, 0)
> * **Light Blue**: #4ec5f2 > rgb(78, 197, 242)
> * **Dark Blue**: #0000c8 > rgb(0, 0, 200)

## Dracula color palette
> * **Dracula Background**: #282a36 > rgb(40, 42, 54)
> * **Dracula Comments**: #6272a4 > rgb(98, 114, 164)
> * **Dracula Selection**: #415967 > rgb(65, 89, 103)
> * **Dracula Highlight**: #3D5261

## Instructions

**1. Set the "Classic" theme:**
> Preferences > General > Appearance > Theme: **Classic**

**2. Set the background image:**
> 1. Install the [SimpleBackground](https://marketplace.eclipse.org/content/simplebackground) plugin.
> 2. Preferences > SimpleBackground > **Background image**: [background.png](./background.png) *(must match the scren size)*

**3. Add this **CSS** code to** \eclipse_directory\plugins\org.eclipse.ui.themes_...\css\ **e4_classic.css**:

```
.MPart Tree {
        font-weight: bold;
        font-size: 10;
        color: #0000C8; /* Dark Blue */
        background-color: #4EC5F2; /*Light Blue*/
}
````

**4. Edit the console colors:**

> Preferences > Run/Debug > **Console**:
> 1. Standart Out text color: **White**
> 2. Background Color: **IDE Background blue (32, 128, 164)**

**5. Edit the "Basic" colors:**
> Preferences > General > Appearance > Colors and Fonts > **Basic**:
> 1. Decoration color: **Yellow**

**6. Edit the "View and Editor Folders" colors:**
> Preferences > General > Appearance > Colors and Fonts > **View and Editor Folders**:
> 1. Active (non-focus) part background begin: **Light Gray (225, 225, 225)**
> 2. Active (non-focus) part background end: **Light Gray (225, 225, 225)**
> 3. Active (non-focus) part foreground: **Dracula Background (40, 42, 54)**
> 4. Active part background begin: **White**
> 5. Active part background end: **White**
> 6. Active part foreground: **Dracula Background (40, 42, 54)**
> 7. Inactive part background begin: **Light Gray (225, 225, 225)**
> 8. Inactive part background end: **Light Gray (225, 225, 225)**
> 9. Inactive part foreground: **Light Yellow (225, 225, 0)**

> **Restart the IDE here to see the current changes.**

**7. Edit the "Text Editors" colors:**
> Preferences > General > Editors > **Text Editors**:
> 1. Line number foreground: **Light Blue: (78, 197, 242)**
> 2. Current line highlight: **Dracula Selection (65, 89, 103)**
> 7. Background color: **Dracula Background (40, 42, 54)**

**8. Edit the "Annotations" colors:**
> Preferences > General > Editors > Text Editors > **Annotations**:
> 1. Ocurrences: **IDE Background blue: (32, 128, 164)**

**9. Edit the Java "Editor" colors:**
> Preferences > Java > **Editor**:
> 1. Matching brackets hightlight: **Cyan**
> 2. Parameter hints background: **Green**
> 3. Parameter hints foreground: **Red**

**10. Edit the Java "Syntax Coloring":**
> Preferences > Java > Editor > Syntax Coloring > **Java**:
> 1. Abstract classes: **Orange**
> 2. Abstract method invocations: **Orange**
> 3. Annotation element references: **Yellow**
> 4. Annotations: **Cyan**
> 5. Auto(un)boxed expressions: **Green**
> 6. Brackets: **White**
> 7. Classes: **Red**
> 8. Deprecated members: **Orange**
> 9. Enums: **Magenta**
> 10. Fields: **Yellow**
> 11. Inherit fields: **Pink**
> 12. Inherit method invocations: **Green**
> 13. Interfaces: **Green**
> 14. Keyword 'return': **Gray, underlined**
> 15. Keywords excluding 'return': **Blue**
> 16. Local variables: **Gray**
> 17. Method declarations: **Green**
> 18. Methods: **Cyan**
> 19. Numbers: **White, underlined**
> 20. Operators: **Magenta**
> 21. Others: **White, bold**
> 22. Parameter variables: **Gray, underline**
> 23. Restricted identifiers: **Green, underline**
> 24. Static fields: **Violet, italic**
> 25. Static fields: **Violet, italic**
> 26. Static final fields: **Beige, bold**
> 27. Static method invocations: **Cyan, bold, italic, underline**
> 28. Strings: **Yellow**
> 29. Type arguments: **Red**
> 30. Type variables: **Red**

**11. Edit the Java Javadoc "Syntax Coloring":**
> Preferences > Java > Editor > Syntax Coloring > **Javadoc**:
> 1. HTML markup: **Green**
> 2. Links: **Cyan, underline**
> 3. Others: **Gray**
> 4. Tags: **Yellow**

**12. Edit the Java Comments "Syntax Coloring":**
> Preferences > Java > Editor > Syntax Coloring > **Comments**:
> 1. Multi-line comment: **Dracula Comments (98, 114, 164)**
> 2. Single-line comment: **Dracula Comments (98, 114, 164)**
> 3. Task Tags: **White**