# 📘 Subject Catalog JSON

This repository contains structured JSON data for various school subjects. It's designed to be used in educational applications, prototypes, or demonstrations involving subject-based content.

## 📂 File Included

- [`subjects.json`](./subjects.json): A JSON file containing a list of 9 subjects with associated metadata such as name, description, number of weekly classes, and literature used.

## 📄 Sample Structure

```json
[
  {
    "id": UUID,
    "name": string,
    "description": string,
    "numberOfWeeklyClasses": int,
    "literatureUsed": ["string"]
  },
  ...
]
