# Word_Counter_project
This Java program is a simple word count application using the Swing framework. The main component of the program is a graphical user interface (GUI) with a `JTextArea` where users can input text. It also includes a button labeled "Count Words" that, when clicked, triggers the counting of words in the text area. The result is displayed in a `JLabel` that shows the word count. The program uses a `JScrollPane` to make the text area scrollable for larger inputs. The word count logic is implemented in the `countWords` method, which splits the input text by spaces and counts the number of words. The program initializes a `JFrame` with a border layout and places the components (text area, button, and label) inside. When the button is pressed, it updates the label with the current word count. The application runs within the `main` method using the `SwingUtilities.invokeLater` method to ensure proper thread handling for the GUI.
