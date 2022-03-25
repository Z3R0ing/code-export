# code-export

If you need to export all your project source code to a doc file, do it with this script.

## Instruction
1. Install dependencies
```bash
pip install -r requirements.txt
```
2. Change the values of variables:
- `directory_in_str` - path to the project root
- `extensions` - list of file extensions to export
3. Run the script
```bash
python3 code-export.py
```
4. The file with the result (res.docx) will be saved to the directory from which the script was ran

## Инструкция
1. Установите зависимости
```bash
pip install -r requirements.txt
```
2. Измените значения переменных:
- `directory_in_str` - путь к корню проекта
- `extensions` - список расширений для экспорта
3. Запустите скрипт
```bash
python3 code-export.py
```
4. Файл с результатом (res.docx) будет сохранён в директории, из который был запущен скрипт
