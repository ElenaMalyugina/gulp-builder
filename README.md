#Учебная сборка Loftschool (выпускной проект №1) 
Малюгина Елена Владимировна

Изменения:
1. Добавлен таск sprite_png, собирающий спрайт из png-файлов.
2. Так как таск, копирующий изображения, есть в исходной сборке, и создавать дублирующий нецелесообразно, создан таск для копирования шрифтов copy_fonts. Можно было объединить два таска в один, но мне кажется, независимые удобнее для использования.

Stack:
 - Gulp 4.0
 
Getting started:

1. clone this repo
2. cd path/to/
3. npm install gulpjs/gulp-cli -g  // Install the latest Gulp CLI tools globally
4. npm install
6. run "gulp" command to start
