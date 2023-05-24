# Draclipse - theme configuration for the Eclipse IDE or Spring Tool Suite

## Version
> **0.5.0**

## Color palette
> 1. **IDE Background**: #2080A4 > rgb(32, 128, 164)
> 2. **Light Gray**: #E1E1E1 > rgb(225, 225, 225)
> 3. **Light Blue**: #4EC5F2 > rgb(78, 197, 242)
> 4. **Dark Blue**: #0000C8 > rgb(0, 0, 200)

> 5. **Dracula Background**: #282A36 > rgb(40, 42, 54)
> 6. **Dracula Comments**: #6272A4 > rgb(98, 114, 164)
> 7. **Dracula Selection**: #415967 > rgb(65, 89, 103)
> 8. **Dracula Cyan**: #8BE9FD > rgb(139, 233, 253)
> 9. **Dracula Dark Blue**: #58B3FC > rgb(88, 179, 252)
> 10. **Dracula Fucsia**: #FF79C6 > rgb(255, 121, 198)
> 11. **Dracula Yellow**: #F1FA8C > rgb(241, 250, 140)
> 12. **Dracula Green**: #50FA7B > rgb(80, 250, 123)
> 13. **Dracula Purple**: #BD93F9 > rgb(189, 147, 249)
> 14. **Dracula Orange**: #FFB86C > rgb(255, 184, 108)
> 15. **Dracula White**: #F8F8F2 > rgb(248, 248, 242)

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
> 1. Standart Out text color: **Dracula White**
> 2. Background Color: **IDE Background**

**5. Edit the "Basic" colors:**
> Preferences > General > Appearance > Colors and Fonts > **Basic**:
> 1. Decoration color: **Yellow (255, 255, 0)**

**6. Edit the "View and Editor Folders" colors:**
> Preferences > General > Appearance > Colors and Fonts > **View and Editor Folders**:
> 1. Active (non-focus) part background begin: **Light Gray**
> 2. Active (non-focus) part background end: **Light Gray**
> 3. Active (non-focus) part foreground: **Dracula Background**
> 4. Active part background begin: **White**
> 5. Active part background end: **White**
> 6. Active part foreground: **Dracula Background**
> 7. Inactive part background begin: **Light Gray**
> 8. Inactive part background end: **Light Gray**
> 9. Inactive part foreground: **Dracula Yellow**

> **Restart the IDE here to see the current changes.**

**7. Edit the "Text Editors" colors:**
> Preferences > General > Editors > **Text Editors**:
> 1. Line number foreground: **Dracula Dark Blue**
> 2. Current line highlight: **Dracula Selection**
> 7. Background color: **Dracula Background**

**8. Edit the "Annotations" colors:**
> Preferences > General > Editors > Text Editors > **Annotations**:
> 1. Matching Tags: **IDE Background**
> 2. Ocurrences: **IDE Background**
> 3. Write Ocurrences: **IDE Background**

**9. Edit the Java "Editor" colors:**
> Preferences > Java > **Editor**:
> 1. Matching brackets hightlight: **Dracula Cyan**
> 2. Parameter hints background: **IDE Background**
> 3. Parameter hints foreground: **Dracula White**

**10. Edit the Java "Syntax Coloring":**
> Preferences > Java > Editor > Syntax Coloring > **Java**:
> 1. Abstract classes: **Dracula Cyan**
> 2. Abstract method invocations: **Dracula Green**
> 3. Annotation element references: **Dracula Dark Blue**
> 4. Annotations: **Dracula Fucsia**
> 5. Auto(un)boxed expressions: **Dracula Orange**
> 6. Brackets: **Dracula Purple**
> 7. Classes: **Dracula Cyan**
> 8. Deprecated members: **Dracula Orange (Strikethrough)**
> 9. Enums: **Dracula Cyan**
> 10. Fields: **Dracula White**
> 11. Inherit fields: **Dracula White**
> 12. Inherit method invocations: **Dracula Green**
> 13. Interfaces: **Dracula Cyan**
> 14. Keyword 'return': **Dracula Fucsia**
> 15. Keywords excluding 'return': **Dracula Dark Blue**
> 16. Local variable declarations: **Dracula White**
> 17. Local variables: **Dracula White**
> 18. Method declarations: **Dracula Green**
> 19. Methods: **Dracula Green**
> 20. Numbers: **Dracula Dark Blue**
> 21. Operators: **Dracula Purple**
> 22. Others: **Dracula Purple**
> 23. Parameter variables: **Dracula Orange**
> 24. Restricted identifiers: **Dracula Dark Blue (Underline)**
> 25. Static fields: **Dracula White**
> 26. Static final fields: **Dracula White**
> 27. Static method invocations: **Dracula Green**
> 28. Strings: **Dracula Yellow**
> 29. Type arguments: **Dracula Orange**
> 30. Type variables: **Dracula Orange**

**11. Edit the Java Javadoc "Syntax Coloring":**
> Preferences > Java > Editor > Syntax Coloring > **Javadoc**:
> 1. HTML markup: **Dracula Dark Blue**
> 2. Links: **Dracula Purple (Underline)**
> 3. Others: **Dracula Orange**
> 4. Tags: **Dracula Fucsia**

**12. Edit the Java Comments "Syntax Coloring":**
> Preferences > Java > Editor > Syntax Coloring > **Comments**:
> 1. Multi-line comment: **Dracula Comments**
> 2. Single-line comment: **Dracula Comments**
> 3. Task Tags: **Dracula White**