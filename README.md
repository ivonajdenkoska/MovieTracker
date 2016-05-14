# MovieTracker
---
###1.	Oпис на апликацијата
	

Апликацијата MovieTracker која ја развивавме, претставува персонализиран начин на следење филмови кои корисникот ги гледал или планира да ги гледа. Инспирацијата за имплементација на оваа апликација ја пронајдовме во сопствената потреба за бележење кои филмови сме ги гледале и кои филмови сакаме да ги гледаме. 


Сите податоци за филмовите (наслов, режисер, актери, жанр, оценка, времетраење, дејство итн.) се извлечени од [OMDb API (The Open Movie Database)](http://www.omdbapi.com/).

###2.	Упатство за користење


На почетната страна (табот “Home”) има search bar за пребарување на филмови. Филмовите се пребаруваат според збор од насловот на филмот. Пронајдените филмови се прикажуаат во листата подоле. Со селекција на било кој филм од генерираната листа, се прикажуваат насловот и постерот на филмот. За приказ на деталите за филмот постои посебно копче кое отвора нов прозорец со сите достапни детали. Селектираниот филм може да се додаде во една од двете листи: 


    •	Листа со гледани филмови (Watched movies)
    •	Листа со филмови кои корисникот планира да ги гледа (WatchList). 
    
    
Оваа функционалност е овозможена со кликнување на копчињата за оваа намена.


Освен можноста за преглед на филмови, на левата страна од прозорецот е достапна статистика за избраните филмови од страна на корисникот. Овозможен е преглед на времето поминато го гледање филмови и број на филмови во двете листи кој се менува во real – time. Има преглед и за рејтингот на гледаните филмови, односно колку филмови со оценка на 9.5  се гледани, колку со оценка над 8.5 итн.

  Во вториот таб “Watched movies” има преглед на филмовите кои корисникот ги гледал. 
  
  Филмовите може да се сортираат според два параметри: Година на издавање и оценка. Со кликнување на едно од овие две копчиња, се извршува соодветното сортирање. Уште една функционалност која е имплементирана е филтрирањето според жанрот.
  Со кликнување на еден од филмовите во листата, на десната страна на прозорецот се прикажуваат детали. Имплементирано е копче за бришење на филмови од листата, во случај ако корисникот внел погрешен филм.
  
  
  Во третиот таб “Watchlist” има преглед на филмовите кои корисникот планира да ги гледа. Функционалностите кои се овозможени за гледаните филмови во вториот таб, ги имплементиравме и овде. Во овој таб има уште едно копче за додавање во листата со гледани филмови, во случај да корисникот го гледал филмот кој го внел во листата Movies – to – watch.

###3.	Претставување на решението 
