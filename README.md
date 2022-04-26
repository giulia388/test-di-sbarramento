# test-di-sbarramento
il body è impostato con display flex, width e height 100%, e margine, padding e border 0.
come prima cosa ho diviso in layout in 3 macrosezioni: le sue sidebar e il main content.
la sidebar di sinistra è stata divisa in sezioni, quella superiori e la parte finale col quadrato. il div principale della sidebar ha display flex column, mentre i figli hanno come direction row. ho poi dato delle dimensioni adeguate ai vari elementi.
la parte centrale è divisa in 3 sezioni: il div principale che contiene le 3 sezioni ha come display flex in column; i figli invece hanno display flex row (le parti superiori), mentre la parte finale ha come display un grid con 2 colonne e 2 righe, dove un elemento ha column:span 2 in modo da occupare più spazio degli altri due.
la parte della sidebar occupa in width il 30% e il main content 70%.
