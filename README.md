# Draclipse - theme configuration for the Eclipse IDE (or Spring Tool Suite)

## Version
> **0.2.3**

## Custom color palette
> * **Background blue**: #2080a4 - rgb(32, 128, 164)
> * **Dracula Background**: #282a36 - rgb(40, 42, 54)
> * **Light Gray**: #e1e1e1 - rgb(225, 225, 225)
> * **Light Yellow**: #e1e100 - rgb(225, 225, 0)

## Instructions

**1. Set the "Classic" theme:**
> Window > Preferences > General > Appearance > Theme: **Classic**

**2. Set the background image:**
> 1. Install the "SimpleBackground" plugin.
> 2. Window > Preferences > SimpleBackground > Background image: **background.png** *(must match your scren size).*

**3. Add this **CSS** code to** \eclipse_directory\plugins\org.eclipse.ui.themes_...\css\ **e4_classic.css**:

```
.MPart Tree {
        font-weight: bold;
        font-size: 10;
        color: #0000C6;
        background-color: #4EC5F2;
}
````

**4. Edit the console colors:**

> Window > Preferences > Run/Debug > Console:
> 1. Standart Out text color: **White**
> 2. Background Color: **Background blue > rgb(32, 128, 164)**

**5. Edit the "Basic" colors:**
> Window > Preferences > General > Appearance > Colors and Fonts > Basic:
> 1. Decoration color: **Yellow**


**6. Edit the "View and Editor Folders" colors:**
> Window > Preferences > General > Appearance > Colors and Fonts > View and Editor Folders:
> 1. Active (non-focus) part background begin: **Light Gray > rgb(225, 225, 225)**
> 2. Active (non-focus) part background end: **Light Gray > rgb(225, 225, 225)**
> 3. Active (non-focus) part foreground: **Black**
> 4. Active part background begin: **White**
> 5. Active part background end: **White**
> 6. Active part foreground: **Black**
> 7. Inactive part background begin: **Light Gray > rgb(225, 225, 225)**
> 8. Inactive part background end: **Light Gray > rgb(225, 225, 225)**
>9. Inactive part foreground: **Light Yellow > rgb(225, 225, 0)**

**7. Edit the "Text Editors" colors:**
> Window > Preferences > General > Editors > Text Editors:
> 1. Background color: **Dracula Background > rgb(40, 42, 54)**

8.**TODO**