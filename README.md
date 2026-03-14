# Practychne 1203

Простий веб-сервер на FastAPI для роздачі статичних HTML-сторінок.

## Встановлення

1. Клонуй репозиторій і перейди в папку:
```
   git clone <https://github.com/taisiiatk/practychne_1203.git>
   cd practychne_1203
```

2. Створи віртуальне середовище:
```
   python -m venv .venv
```

3. Активуй його:

   **Windows (PowerShell):**
```
   .venv\Scripts\activate
```

   **Mac**
```
   source .venv/bin/activate
```

4. Встанови залежності:
```
   pip install fastapi uvicorn
```

## Запуск
```
uvicorn main:app 
```

Відкрий браузер: http://127.0.0.1:8000

## Структура
```
practychne_1203/
├── pages/
│   ├── images/
│   │   └── damn.jpg
│   ├── 1/
│   │   └── foo.html
│   └── index.html
├── main.py
├── .gitignore
├── pyproject.toml
└── README.md
```
