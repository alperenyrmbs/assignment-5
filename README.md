# Contact Data Cleanup — Python Coursework

A university notebook exercise exploring how to validate and standardize contact records before writing them to a CSV file.

## What the code covers

- Email format validation with regular expressions
- Phone number normalization
- Case-insensitive duplicate email handling
- Reading and writing files with pathlib and csv
- Unit-test exercises for validation, normalization, parsing, and duplicate handling

## Repository contents

Open **Assignment5_Ch_10&11 (1).ipynb** to read the assignment and implementation. The notebook includes a small synthetic dataset supplied for the exercise.

## How to explore

Open the notebook in Jupyter or Google Colab. Review the input format and parsing code before running the cells; file-writing cells create local text and CSV files. The code uses Python's standard library.

## Current limitations

The row parser expects comma-separated name, email, and phone fields. Some supplied sample records use an angle-bracket email format that the parser does not extract. Those records may be skipped. This is a learning exercise; the tests do not establish production readiness.

## Context

University coursework with assignment-provided sample data. No real customer records are included in the notebook's sample dataset.

[Alperen Yarimbas — Portfolio](https://alperenyrmbs.github.io/) · [LinkedIn](https://www.linkedin.com/in/alperenyr/)
