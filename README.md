# Vector-images-quality-assessment

### Задачи (расположены поэтапно):
1) Сбор векторных изображений – parsers/main.py
2) Переименование и конвертация svg изображений в png расширение -- converting.py.
3) Некая статистика по разрешениям изобаржений и дальнейшая нормализация разрешений -- stata.py
4) Отчистка от дубликатов и нежелательных изображений -- clearing.py
5) Взятие эмбеддингов -- clipBlip/clipModel
6) Кластеризация -- clustering_models.py
7) Взятие описаний к изображениям -- clipBlip/blipModel

### Остальные файлы:
_paths.txt_ - для прописывания путей

_save_read.py_ - для храненения таких сущностей, как словари с очищенными/неочищенными эмбеддингами, получившиеся резульаты  кластеризации и т.д.

_visualization.py_ - функции для визуализации некоторых результатах.

