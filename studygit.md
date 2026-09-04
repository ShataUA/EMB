# Типова послідовність роботи з Git та GitHub

Після створення проєкту зазвичай виконують такі команди:

## 1. Створити локальний Git-репозиторій

```bash
git init
```

Створює локальний Git-репозиторій у поточній папці.

---

## 2. Додати всі файли до індексу

```bash
git add .
```

Додає всі файли з поточної директорії до staging area (індексу).

---

## 3. Створити перший коміт

```bash
git commit -m "Initial commit"
```

Створює перший коміт із повідомленням `Initial commit`.

---

## 4. Прив'язати віддалений репозиторій GitHub

```bash
git remote add origin https://github.com/ShataUA/EMB.git
```

Додає віддалений репозиторій з іменем `origin`.

---

## 5. Перейменувати гілку в `main`

```bash
git branch -M main
```

Перейменовує поточну гілку на `main`.

---

## 6. Відправити зміни на GitHub

```bash
git push -u origin main
```

Відправляє локальну гілку `main` до віддаленого репозиторію `origin` та встановлює зв'язок між ними.

---

## Повна послідовність команд

```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/ShataUA/EMB.git
git branch -M main
git push -u origin main
```

---

## Перевірка стану репозиторію

```bash
git status
```

Показує поточний стан репозиторію та наявність змін.

## Перегляд гілок

```bash
git branch
```

Показує список локальних гілок.

## Перегляд історії комітів

```bash
git log --oneline
```

Показує історію комітів у скороченому вигляді.