# 🎨 Digivas – iGraphics Digital Drawing Board

**Digivas** is a digital drawing board application developed by **Adib Bin Iqbal** for the **CSE 102 course** at the **BUET CSE Department**. It provides a user-friendly platform for aspiring artists, students, and designers to unleash their creativity on a digital canvas using simple interactive tools.

GitHub Repo: [https://github.com/adibbiniqbal/iGraphics-Digital_Drawing_Board-Digivas](https://github.com/adibbiniqbal/iGraphics-Digital_Drawing_Board-Digivas)

---

## 📽️ Demo

Watch the live demonstration:  
[![Digivas Demo](https://img.youtube.com/vi/llOTXxRDdfM/0.jpg)](https://youtu.be/llOTXxRDdfM)

---

## 🖌️ Features

- **🖊️ Pen Tool**: Draw or write freely anywhere on the board using the right mouse button after selecting the pen tool.
- **📐 Geometric Shapes**: Easily add shapes like circles, straight lines, ellipses, and rectangles by clicking the respective shape button and then clicking on the canvas.
- **🎨 Color Picker**: Choose vibrant colors for your pen or shape using intuitive color buttons.
- **🔍 Size Adjustment**: Increase or decrease the brush size, circle radius, ellipse axes, or rectangle dimensions using the `+` and `-` buttons.
- **🧽 Eraser Tool**: Erase drawn content by selecting the eraser and right-click-dragging over the area to be erased.
- **🔤 Text Tool**: Add custom text anywhere on the board by selecting the text tool and clicking your desired location.

---

## 🎯 Target Audience

Digivas is ideal for:

- **🎨 Art Enthusiasts** – Practice freehand sketching and digital painting.
- **🧑‍🎓 Students** – Use it for visual note-taking or educational projects.
- **🧑‍💻 Designers** – Create digital mockups and simple illustrations with ease.

---

## 🔧 Requirements

- C++ Compiler
- OpenGL and GLUT
- iGraphics Library:  
  Get it from [Drive](https://drive.google.com/drive/folders/1CD23-FPh9YcDVsRckE0WqfKOVra-3guj)

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/adibbiniqbal/iGraphics-Digital_Drawing_Board-Digivas
   cd iGraphics-Digital_Drawing_Board-Digivas
   ```

2. **(Recommended)** Create the `.vscode` folder and place `tasks.json` inside:
   ```
   mkdir .vscode
   ```

3. Example `tasks.json` to compile and run:
   ```json
   {
     "version": "2.0.0",
     "tasks": [
       {
         "label": "Build and Run Digivas",
         "type": "shell",
         "command": "g++ main.cpp -lglut -lGL -lGLU -o Digivas && ./Digivas",
         "group": {
           "kind": "build",
           "isDefault": true
         },
         "problemMatcher": []
       }
     ]
   }
   ```

4. Run the app using your terminal or the VS Code build task.

---

## 📁 File Structure

```
📁 iGraphics-Digital_Drawing_Board-Digivas
├── main.cpp              # Core implementation
├── README.md             # Project overview
└── .vscode/
    └── tasks.json        # VS Code build config
```

---

## 🙌 Acknowledgements

- Developed using [iGraphics](https://drive.google.com/drive/folders/1CD23-FPh9YcDVsRckE0WqfKOVra-3guj) by BUET.
- Special thanks to the BUET CSE 102 teaching staff and community.

---

## 📜 License

This project is released under the MIT License.

---

> Created with ❤️ by Adib Bin Iqbal



