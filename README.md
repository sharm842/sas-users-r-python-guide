# Sas-users-r-python-guide
Welcome! Here I will post easy-to-follow codes for anyone who wants to learn R and Python, especially for epidemiologists who are new to coding or moving from SAS.  This page is designed for people who don’t have a strong background in coding, I am not a programming expert or a deep diver into coding languages—I am an epidemiologist and a PhD student. I use these codes mainly for statistical analysis and everyday data tasks in my research. I will share only the basics and practical tips that I use in my daily PhD life.

For each code example, I will include:

A simple explanation in plain English

What you can achieve with that code

Step-by-step instructions, when needed

The goal is to make coding practical and approachable for epidemiologists and other researchers who just want to get their work done—no advanced coding knowledge required.

If you have any questions, or if you want to see an example for your own research, feel free to reach out. Happy learning!


CHAPTER - PYTHON DOWNLOADS

# Beginner Guide: Getting Started with Jupyter Notebook (Python)

Jupyter Notebook is a free, easy-to-use tool to write and run Python code in your browser. It's perfect for beginners, especially for someone new to data science and learning programming.

---

## 1. What is Jupyter Notebook?
- **An interactive coding tool**: You can write code, add notes, and see results instantly.
- **Runs in your browser**, no complex setup required.

---

## 2. How to Start Using Jupyter Notebook

This is what I use, you are free to google what other options are availabe. You can use google colab, VScode etc

### : Install Anaconda (Recommended for Local Use)
1. Download [Anaconda Individual Edition](https://www.anaconda.com/products/distribution) and install it.
2. Open “Anaconda Navigator” and click “Launch” under Jupyter Notebook.
3. Use the "new" option on the right side above corner and then click it, slect python 3

---

## 3. Understanding the Interface

- **Cells**: Each box where you write code or text is called a “cell.”
- **Run**: Click the “Run” button (or press `Shift+Enter`) to execute the code in the current cell.
- **Output**: Results appear just below the cell.

---

## 4. Writing and Running Python Code

```python
# Type this in a cell and run
a = 3
b = 4
c = a + b
c
print (c)
```
- The value `7` will be shown below the cell.

**Tip:** If you assign a variable in a cell (like `c = a + b`), you won’t see the result unless you:
- Type the variable name alone at the end of the cell (`c`), or
- Use `print(c)`.

What is a Variable?
Think of a variable as a container that can hold different values.

A value can be:

A string: This means text or anything that isn’t a number. It always goes inside quotation marks, like "2", "name", "25.6", or "age".

An integer: This is a whole number, like -2, 2, 5, or 15.

A float: This is just a fancy word for a number with decimals, like 22.56 or 559.23.

So, a variable can store all sorts of things—just remember:

Strings: use quotation marks (" ").

Numbers: no quotation marks for integers and floats.

I hope that helps!
---

## 5. Adding Text and Notes

- Change a cell to “Markdown” from the dropdown menu to write notes or instructions (like you see here).
- Use `#` for headings, `*` for bullet points, etc.

---

## 6. Saving and Sharing
- Click “File” → “Save” to save your work.
- Download your notebook as `.ipynb` or export as PDF.

---

## 7. Common Beginner Tips

- Run cells one by one from top to bottom.
- Use comments (`#`) to explain your code.
- If something doesn’t work, restart the notebook from the menu: “Kernel” → “Restart & Clear Output”.

---

## 8. More Resources

- [Jupyter Beginner Tutorial (YouTube)](https://www.youtube.com/watch?v=HW29067qVWk)
- [Official Jupyter Documentation](https://jupyter-notebook.readthedocs.io/en/stable/)

---
