# TextEditor

![image](https://github.com/kd1120/TextEditor/assets/121998675/29edb6fe-b03d-4cd5-a072-fce2cb4a6244)




TextEditor Technical Description

1. Application Components:
   - TextEditor: The main class that creates the application window and manages the overall functionality of the text editor.
   - JFrame: The graphical window that serves as the main user interface for the text editor application.
   - JTextArea: The text area component where the user can view and edit text.
   - JMenuBar: A menu bar that contains menu items for performing various actions in the text editor.
   - JMenu: Individual menus in the menu bar, such as File, Edit, and Window, which contain specific actions.
   - JMenuItem: Items within the menus that represent specific actions, such as Open, Save, Cut, Copy, Paste, etc.

2. Object-Oriented Design:
   - TextEditor class: This class acts as the main driver of the text editor application. It creates an instance of the JFrame and initializes the necessary components.
   - MenuBar class: This class extends JMenuBar and represents the menu bar of the text editor. It contains the menu items and handles their respective actions.
   - FileMenu, EditMenu, and WindowMenu classes: These classes extend JMenu and represent the individual menus in the menu bar. They contain specific actions related to file operations, editing text, and managing windows.
   - MenuItem classes: These classes extend JMenuItem and represent the individual menu items within the menus. They handle specific actions when clicked by the user.

3. Graphical User Interface (GUI):
   - The text editor window is represented by a JFrame that contains a JTextArea component to display and edit text.
   - The JFrame also contains a JMenuBar, which consists of JMenu objects representing different menus.
   - Each JMenu contains multiple JMenuItem objects representing specific actions.
   - The GUI is designed using Java Swing and its components, which are added to the JFrame using appropriate layout managers.

4. User Actions:
   - The user can perform various actions in the text editor using the menu items in the menu bar.
   - File Menu: Contains actions related to opening new files, saving files, and exiting the application.
   - Edit Menu: Contains actions related to copying, cutting, pasting, deleting, selecting, and modifying the text in the JTextArea.
   - Window Menu: Contains actions related to opening new windows or managing existing windows in the text editor application.

5. Text Manipulation:
   - The JTextArea component allows the user to view and edit text.
   - The Edit Menu provides actions like copy, cut, paste, delete, and select, which operate on the selected text within the JTextArea.
   - When the user performs any of these actions, the selected text is modified or copied to the clipboard, depending on the action.

6. Opening New Windows:
   - The Window Menu provides actions for opening new windows in the text editor application.
   - When the user selects the "New Window" action, a new instance of the TextEditor class is created, and a new window is opened with its own JTextArea for text editing.

7. Object-Oriented Principles:
   - The design follows object-oriented programming principles, such as encapsulation, inheritance, and polymorphism.
   - Each component, such as TextEditor, MenuBar, FileMenu, EditMenu, and WindowMenu, represents a separate class with well-defined responsibilities.
   - Inheritance is used to extend Swing components, such as JMenuBar and JMenu, to create custom menu bar and menu classes.
   - Polymorphism is utilized through method overriding to handle specific actions for different menu items.

