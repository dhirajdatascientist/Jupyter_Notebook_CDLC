## What is Jupyter Notebook?
* Jupyter Notebook is a popular interactive computing environment that allows you to run live code, embed visualizations, and combine markdown narrative in a single document. 

### 1. Installation:

**Using pip:**
```bash
pip install jupyter
```

**Using conda (if you have Anaconda or Miniconda installed):**
```bash
conda install jupyter
```

### 2. Launching Jupyter Notebook:

Navigate to your desired directory in the terminal or command prompt and run:
```bash
jupyter notebook
```

This command will launch a new browser window (or a new tab in an existing window) showing the Jupyter Notebook dashboard.

### 3. Creating a New Notebook:

In the dashboard:
- Click on the "New" button on the right side.
- Choose "Python" (or another kernel if you have multiple installed).

### 4. Jupyter Notebook Interface:

- **Cells:** The basic unit of Jupyter Notebook. You can write code or markdown text in these cells.
- **Toolbar:** Contains buttons to save, create new cells, cut/copy/paste cells, run the code, etc.
- **Kernel:** The backend that runs your code. You can restart the kernel if the code hangs.

### 5. Writing and Executing Code:

Type some Python code into a cell, such as:
```python
print("Hello, Jupyter!")
```
To execute the cell, press `Shift + Enter`. The output will appear below the cell.

### 6. Markdown Cells:

You can document your code using markdown cells. To convert a code cell to markdown:
- Click on the cell.
- Use the dropdown menu in the toolbar to change the cell type from "Code" to "Markdown".

Now you can write markdown text. For example:
```
# This is a Header
Hello, this is a **markdown** cell.
```
Again, press `Shift + Enter` to render the markdown cell.

### 7. Saving Your Notebook:

- Click on the floppy disk icon or go to `File > Save and Checkpoint`.

### 8. Closing the Notebook:

- Close the browser tab.
- Go back to your terminal and press `Ctrl + C` twice to shut down the Jupyter server.

### 9. Keyboard Shortcuts:

- `Shift + Enter` - Run cell and move to the next cell.
- `Ctrl + Enter` - Run cell in place.
- `Alt + Enter` - Run cell and create a new cell below.
- `Esc` followed by `A` - Create a new cell above the current cell.
- `Esc` followed by `B` - Create a new cell below the current cell.
- `Esc` followed by `M` - Change cell to markdown mode.
- `Esc` followed by `Y` - Change cell to code mode.
- `Esc` followed by `D` (twice) - Delete the current cell.

### 10. Additional Features:

Jupyter Notebook offers a lot of advanced features like magic commands (`%matplotlib inline` for inline plots, `%time` for timing code execution), integrating with shell commands, rich display capabilities, and much more.
