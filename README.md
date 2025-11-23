# Mean-Variance-Standard Deviation Calculator  
**freeCodeCamp – Data Analysis with Python Certification**  
**Project 1 of 5**

[![freeCodeCamp](https://img.shields.io/badge/freecodecamp-Data%20Analysis%20with%20Python-blue.svg?style=flat-square)](https://www.freecodecamp.org/learn/data-analysis-with-python/)
[![Python](https://img.shields.io/badge/python-3.8%2B-blue.svg?style=flat-square)](https://www.python.org/)
[![NumPy](https://img.shields.io/badge/numpy-1.2%2B-orange.svg?style=flat-square)](https://numpy.org/)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1xmOFjnKy6IleyK8F2Jz5mu4PCNIpjbra?usp=sharing)

## Project Overview
This project is part of the freeCodeCamp **Data Analysis with Python** certification.

The task is to create a function called `calculate()` that takes a list of **exactly 9 numbers**, converts it into a **3×3 NumPy matrix**, and returns a dictionary containing the following statistical measures calculated along:
- Axis 0 (columns)
- Axis 1 (rows)
- The entire flattened matrix

**Statistics calculated:**
- Mean
- Variance
- Standard deviation
- Max
- Min
- Sum

The function also raises a `ValueError` if the input list does not contain exactly nine numbers.

## Live Notebook
Run and explore the full project interactively:  
[Open in Google Colab](https://colab.research.google.com/drive/1xmOFjnKy6IleyK8F2Jz5mu4PCNIpjbra?usp=sharing)


## Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin&style=for-the-badge)](https://www.linkedin.com/in/abishek2612)  
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?logo=github&style=for-the-badge)](https://github.com/abishek-2612)

**Made with ❤️ by Abishek**  
Feel free to reach out on LinkedIn!


## Output Example
```python
calculate([0, 1, 2, 3, 4, 5, 6, 7, 8])
{
  'mean': [[3.0, 4.0, 5.0], [1.0, 4.0, 7.0], 4.0],
  'variance': [[6.0, 6.0, 6.0], [0.6666666666666666, 0.6666666666666666, 0.6666666666666666], 6.666666666666667],
  'standard deviation': [[2.449489742783178, 2.449489742783178, 2.449489742783178], [0.816496580927726, 0.816496580927726, 0.816496580927726], 2.581988897471611],
  'max': [[6, 7, 8], [2, 5, 8], 8],
  'min': [[0, 1, 2], [0, 3, 6], 0],
  'sum': [[9, 12, 15], [3, 12, 21], 36]
}








