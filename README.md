# Шпаргалка Gitbash и Git

### GitBash
pwd - показать, в какой ты папке;

ls  — показать файлы в папке, где ты сейчас;

ls -a — показать файлы и папки, включая скрытые;

cd first-project  — перейти в папку first-project;

cd first-project/qa  — перейти в папку qa, находящуюся в папке first-project;

cd ..  — перейти на уровень выше в родительскую папку;

cd / — перейти в корневую директорию;

cd ~  — перейти в домашнюю директорию;

mkdir second-project  — в текущей папке создать папку с именем second-project;

rm about.html  — удалить файл about.html;

rmdir images  — удалить папку images;

rm -r second-project  — удалить папку second-project и всё, что она содержит;

touch Main.java  — создать файл Main.java в текущей папке;

touch Main.java Cat.java  — если нужно создать несколько файлов, их имена
можно вводить через пробел;

nano logs/apache.txt — открыть текстовый файл apache.txt;

cat ~/logs/apache.txt — вывести содержимое в окно терминала;

cat a.txt > b.txt — перезаписать содержимое файла a.txt в b.txt;

cat a.txt >> b.txt — скопировать содержимое файла a.txt в конец b.txt;

cp brothers.html sisters.html — скопировать файл brothers.html и назвать новый
файл sisters.html;

mv card.txt ~/ — перенести card.txt из текущей директории в домашнюю;

mv my_app.ssh your_app.ssh — переименовать файл my_app.ssh в your_app.ssh;

grep DELETE apache.txt — вывести все строки из файла apache.txt, которые содержат DELETE;

grep -R DELETE ~/logs/2020/1 — вывести все строки внутри каталога, которые
содержат DELETE;

grep -n DELETE apache.txt — вывести все строки и их номера из файла
apache.txt, которые содержат DELETE.

### Git
git init - инициализация;

git status - проверка статуса;

rm -rf .git - разгитить папку;

git add --all - добавить все для возможности коммита;

git commit -m "Коммит" - коммит;

git log - посмотреть историю коммитов;

git remote add origin ввод ссылки SSH - связать репозитории;

git remote -v - убедиться, что связаны;

git push -u --force origin main - первый пуш;

git push - дальнейшие пуши;

git remote remove origin - удалить связь репозиториев


