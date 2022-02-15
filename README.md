# Aurora Assistant

### About
Your personal assistant based on artificial intelligence. Aurora analyzes error traceback in machine learning libraries and proposes a optimal fix.

### Requirement
To use Aurora Assistant on your hardware you need:
- Python >= 3.6
- Jupyter Notebook >= 3.x
- Jupyter Nbextensions

You can also use the web version of the assistant.

### Installation

Download the repository and open a terminal in the "AuroraAssistant" folder. Run the commands:
```
jupyter nbextension install src/auroraassistant
jupyter nbextension enable auroraassistant/main
```

### How to add a token
Copy the token from the [official site](http://localhost:8000) and place it as "auroraassistant" file in the working folder of Jupyter Notebook.

<img src="https://ie.wampi.ru/2022/01/31/AuroraAssistant-2.png" alt="auroraassistant in working directory" border="0"> <br>

You can also use the command:
```
echo your_token > auroraassistant
```

### Usage
Select the cell with the error and turn on the command mode using "Esc". Press Ctrl + Q and wait for the solution to be generated.
