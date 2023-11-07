sprint_01
En aquesta pràctica hauràs de fer un Layout que ha de funcionar tant en escriptori, com mòbil i tauleta.

Important: Coneixements que has de tenir per facilitar la resolució de la pràctica.

HTML i CSS Flexbox. -> Flexbox CSS: Guia Completo, Elementos y Ejemplos Media queries (pots utilizar els punts de tall de com les de bootstrap. -> Media queries Tingues en compte les següents consideracions. Són errors habituals en els lliuraments:

En general, mai li posem height a una capa, sinó que deixem que la capa s'adapti al seu contingut (si la capa no té contingut, li pots posar un height). La pàgina no hauria de tenir barra de scroll horitzontal (si et passa, hauràs d'esbrinar inspeccionant la pàgina quin bloc és més ample que la pantalla del navegador). Dins d'un div sol haver-hi altres divs. Els divs tenen display:block per defecte. Això fa que es vagin col·locant de manera vertical. Per tant, sovint no és necessari especificar els següents estils per a un element per ser una cosa redundant: .element{ display:flex; flex-direction:column } En un div, per defecte l'ample és de la totalitat de la capa que embolica, així que normalment no serà necessari especificar width:100%

Lliurament per GitHub

Crea un únic repositori de GitHub per als tres nivells, els podràs separar en carpetes. Per exemple: nivell-1, nivell-2 i nivell-3.
