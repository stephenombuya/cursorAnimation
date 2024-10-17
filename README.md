# **Cursor Animation**
This project is a Cursor Animation built using HTML5, CSS3, and JavaScript. It tracks the mouse movement on the webpage and animates a custom cursor that follows the mouse pointer. The cursor disappears when the mouse stops moving for a short period.



### **Features**
- **Custom Cursor Animation**: A circle that follows the mouse pointer around the screen.
- **Mouse Activity Tracking**: The cursor is visible only when the mouse is moving and disappears when the mouse stops.
- **Responsive Design**: The cursor animation works on different screen sizes.



### **Technologies Used**
- **HTML5**: Provides the structure of the webpage.
- **CSS3**: Handles the styling of the cursor and page elements.
- **JavaScript**: Implements the dynamic behavior for mouse movement tracking and cursor visibility.



### **Project Structure**

```
Cursor-Animation/
│
├── index.html       # The main HTML structure
├── style.css        # CSS file for styling the page and cursor
├── app.js           # For adding interactivity
├── README.md        # Project documentation
```



### **Folder Structure**
- **index.html**: The HTML file contains the basic structure of the page, including a section for the cursor and the event listeners for mouse movements.
- **style.css**: This file styles the cursor and the webpage.
- **app.js**: Implements the dynamic behavior for mouse movement tracking and cursor visibility.
- **README.md**: The project documentation file you're reading now.



### **How to Use**
1. Clone the repository:

```
git clone https://github.com/stephenombuya/cursorAnimation
```

2. Navigate to the project directory:

```
cd cursor-animation
```

3. Open the index.html file in a web browser:

```
open index.html
```

Alternatively, you can open the file directly from your code editor or browser.



### **Customization**
1. Changing Cursor Appearance
You can modify the cursor's appearance by updating the CSS in the style.css file. For example, to change the cursor's size or color:

```
.cursor {
  width: 30px;
  height: 30px;
  background-color: red; /* Change to any color you like */
  border-radius: 50%;
  position: absolute;
  pointer-events: none;
  display: none;
  transition: top 0.1s ease, left 0.1s ease;
}
```

2. Adjusting Timeout for Cursor Disappearance
In the JavaScript section, the cursor disappears after the mouse stops moving for 1 second (1000 milliseconds). You can adjust this delay by changing the timeout value:

```
timeout = setTimeout(mouseStopped, 1000); // Change 1000 to a different value
```

3. Enhancing the Animation
You can also experiment with CSS transitions and animations to create a more visually appealing effect when the cursor moves:

```
.cursor {
  transition: transform 0.2s ease;
  transform: scale(1.2);
}
```



### **Browser Support**
This project works in modern web browsers that support JavaScript and CSS3. It's compatible with Chrome, Firefox, Safari, and Edge.



### **Future Enhancements**
Here are some possible improvements:

- **Custom Cursor Styles for Different Elements**: Change the cursor when hovering over links, buttons, or other interactive elements.
- **Cursor Trail Effect**: Create a trailing effect where multiple circles follow the main cursor.
- **Click Animations**: Add visual effects when the user clicks anywhere on the screen.



### **Contributing**
Contributions are welcome! If you have ideas for improvements, feel free to fork the repository and submit a pull request. You can also open an issue if you find bugs or have suggestions.



### **License**
This project is licensed under the MIT License. See the [LICENSE](https://github.com/stephenombuya/cursorAnimation/blob/main/LICENSE) file for details.
