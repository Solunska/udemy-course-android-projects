# Unit Converter App Documentation

## Introduction
This documentation provides an overview of the Unit Converter app created as the first project in an Android development course. The app allows users to convert between different units of measurement. Through this project, several key concepts and components of Jetpack Compose were learned and applied.

## Main Activity Code
The main activity code for the Unit Converter app can be found [here](/app/src/main/java/com/example/unitconverter/MainActivity.kt).

## Concepts and Components
The following concepts and components were utilized in the development of the Unit Converter app:

### Composables
- Fundamental building blocks of Jetpack Compose UI.
- Functions annotated with `@Composable` to describe the UI elements.

### Column and Row
- **Column**: Arranges children in a vertical sequence.
- **Row**: Arranges children in a horizontal sequence.

### OutlinedTextField
- A text input field with an outlined border.
- Used for entering the value to be converted.

### Button
- A clickable button element.
- Triggers the unit selection dropdown menus and the conversion function.

### OnClick and Toast
- `onClick`: A callback triggered when a button is clicked.
- `Toast`: A short message displayed on the screen.

### Box
- A layout element that allows stacking of child elements.
- Used to overlay buttons and dropdown menus.

### Icons and DropdownMenus
- **Icon**: A graphical representation of an action or item.
- **DropdownMenu**: A menu that displays a list of selectable items.

### Modifier
- Used to modify the appearance or behavior of a composable.
- Examples include setting padding, size, and alignment.

### VerticalArrangement and HorizontalAlignment
- **VerticalArrangement**: Specifies vertical arrangement of children in a column.
- **HorizontalAlignment**: Specifies horizontal alignment of children in a column.

### Spacer and Padding
- **Spacer**: Creates space between composables.
- **Padding**: Adds space around a composable.

### Remember and Mutable State
- `remember`: Retains state across recompositions.
- `mutableStateOf`: Creates mutable state that can be observed for changes.

## Features
- **Input and Output Fields**: Users can enter the value they want to convert and select the units for conversion.
- **Conversion Function**: Automatically converts the entered value based on the selected units.
- **Dynamic Dropdown Menus**: Allows users to select the input and output units from a list of options.
- **Live Result Display**: Displays the conversion result dynamically as the input value or units are changed.

## Learning Outcomes
By building this app, the following skills and knowledge were gained:
- Understanding of composables and their usage in Jetpack Compose.
- Layout arrangement using `Column`, `Row`, `Box`, and `Spacer`.
- Handling user input with `OutlinedTextField` and updating the state.
- Creating interactive UI elements like `Button`, `DropdownMenu`, and `Icon`.
- Managing UI state with `remember` and `mutableStateOf`.
- Applying modifiers to customize the appearance and behavior of composables.
- Aligning and arranging UI components with `verticalArrangement` and `horizontalAlignment`.
