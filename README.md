<h1 align="center">Hi there, I'm <a href="https://astralinux31.github.io/" target="_blank">Dmitry</a> 
<img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/></h1>
<h3 align="center">Новости Linux 🇷🇺</h3>

[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=F70E1C&lines=Interesting+Linux+news+for+me+;will+be+posted+here)](https://git.io/typing-svg)

![Fedora](https://img.shields.io/badge/Fedora-294172?style=for-the-badge&logo=fedora&logoColor=white) ![Kali](https://img.shields.io/badge/Kali-268BEE?style=for-the-badge&logo=kalilinux&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![Linux Mint](https://img.shields.io/badge/Linux%20Mint-87CF3E?style=for-the-badge&logo=Linux%20Mint&logoColor=white) ![Red Hat](https://img.shields.io/badge/Red%20Hat-EE0000?style=for-the-badge&logo=redhat&logoColor=white) ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

Bash — довольно развитый командный интерпретатор, поддерживающий кучу разных настроек. Причем из этих настроек можно получить гораздо больше профита, чем из настроек поведения терминала. 

Список всех возможных опций можно посмотреть командой:  shopt -p 

Cамые интересные из них:
autocd — если эта опция включена, то можно просто написать путь к каталогу (опустив команду cd), чтобы в него переместиться;

cdspell — bash будет пытаться исправлять простые опечатки (например, /ect/init.d вместо /etc/init.d) в аргументах команды cd;

checkjobs — не дает выйти из консоли, пока в ней есть выполняющиеся задания;

cmdhist — объединение многострочных команд в одну строку так, чтобы тебе было проще искать их в истории;

dirspell — исправление небольших ошибок в написании имени директории при автодополнении;

globstar — позволит использовать конструкцию вида **, обозначающую «все файлы, начиная с текущего каталога, рекурсивно»;
Очень удобный новый wildchar — например, данная конструкция отобразит все mp3 в текущем и вложенных каталогах:
ls **/*.mp3
Гораздо удобнее, чем:
find ./ -name "*.mp3" -type f -print


Устанавливаются опции следующим образом:

shopt -s autocd cdspell checkjobs cmdhist dirspell globstar.

<img src="https://readme-jokes.vercel.app/api" alt="Jokes Card" />
