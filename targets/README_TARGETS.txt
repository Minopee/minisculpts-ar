Как подготовить таргет для WebAR (MindAR) — moneta.mind

1) Возьми изображение твоей «монеты»-якоря (тот круг, который печатаешь на базу).
   Формат: PNG, ч/б, матовый стиль, размер ~1000–1500 px, без бликов.

2) Скомпилируй .mind (два пути):
   (a) Онлайн инструмент (MindAR Target Compiler):
       https://hiukim.github.io/mind-ar-js-doc/tools/compile/
       Загрузи PNG, выбери 1 target, нажми Compile — скачай moneta.mind
   (б) Локально (Node.js):
       npx mindar-image@latest compile -i marker.png -o moneta.mind

3) Положи файл в репозиторий по пути:
   /ar/targets/moneta.mind

4) Проверь на телефоне:
   https://Minopee.github.io/minisculpts-ar/ar/?scene=demo&msg=Привет&n=000
