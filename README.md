# 🕷️ Web Scraping Wuzzuf Job Listings

This project scrapes job listings from [Wuzzuf](https://wuzzuf.net) for given job titles (e.g., "Machine Learning Scientist", "Python Developer", etc.) and saves them into CSV files using Python.

## 📌 Objectives

- Extract job data such as title, company, location, and job specs.
- Collect data for multiple job categories.
- Save the data in a structured format (CSV).
- Combine multiple results into one dataset.

---

## 📦 Libraries Used

```python
import requests
from bs4 import BeautifulSoup
import pandas as pd
import math
