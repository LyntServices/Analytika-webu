Zdrojové dokumenty k článkům o analytice webu.

##Analýza struktury pomocí Xenu, GraphViz a Xmind:##
http://lynt.cz/blog/analyza-struktury-webu

Použité příkazy v tomto článku:
```
dot -Tpng -o x:\out1.png x:\lynt.gv
dijkstra "http://lynt.cz/" x:\lynt.gv > x:\lynt2.gv
dot -Tpng -o x:\out2.png x:\lynt3.gv
neato -Goverlap=false -Tpng -o x:\out3.png x:\lynt3.gv
```

Nástroje na čištění a konverzi do FreeMind: http://tools.lynt.cz/dot.php
