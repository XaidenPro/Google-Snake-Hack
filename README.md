# Google-Snake-Hack
#paste code into bookmarkbar
#This is NOT my code

javascript: req = new XMLHttpRequest(); req.open('GET', 'https://raw.githubusercontent.com/DarkSnakeGang/GoogleSnakeCustomMenuStuff/main/custom.js'); req.onload = function() { eval(this.responseText + 'snake.more_menu();'); }; req.send();
