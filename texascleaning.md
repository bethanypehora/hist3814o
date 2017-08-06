    1  git remote add origin https://github.com/BETHANYPEHORA/MODULE_4.git
    2  git config remote.origin.url https://github.com/BETHANYPEHORA/MODULE_4.git
    3  git pull -u origin master
    4  nano index1final.csv
    5  nano indexfinal.csv
    6  nano newtexas.txt.bak
    7  sed -n '1,2408p' newtexas.txt.bak > FINALindex.csv
    8  nano FINALindex.csv
    9  grep -E ".+,.+,.+," FINALindex.csv
   10  cp FINALindex.csv cleaned-correspondence.csv
   11  history > texascleaning.md
