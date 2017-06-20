<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#orgaa2a998">Conocernos</a></li>
<li><a href="#org0e8b927">Planteamientos</a>
<ul>
<li><a href="#orgcb670a1"><span class="todo TODO">TODO</span> ¿Estructurar conocimiento usando niveles de indentación? The Information by James Glick</a></li>
<li><a href="#orgc1bf2a9"><span class="todo TODO">TODO</span> ¿unidad significativa?</a>
<ul>
<li><a href="#org232f288"><span class="todo TODO">TODO</span> ¿parrafo? ¿cómo lo relaciono? ¿tags?</a></li>
</ul>
</li>
<li><a href="#org6bc40c2">Deseamos que queden informados en:</a>
<ul>
<li><a href="#org10b847b">org-mode</a></li>
<li><a href="#orgaca966d">Ledger</a></li>
</ul>
</li>
<li><a href="#org38e9ca6">Educados en:</a>
<ul>
<li><a href="#org2991c4e">Estructurar información</a></li>
</ul>
</li>
<li><a href="#org5c4959f">y con herramientas:</a>
<ul>
<li><a href="#org0b32c73">Emacs-Org</a></li>
</ul>
</li>
</ul>
</li>
<li><a href="#org6beda7a"></a></li>
<li><a href="#orge2b7d92"></a></li>
</ul>
</div>
</div>


<a id="orgaa2a998"></a>

# Conocernos     :Fix:

¿Porqué estamos acá?

-   Embale para hacer usable el exceso de info
-   Que dure 100 años
-   Máquina, ayudame


<a id="org0e8b927"></a>

# Planteamientos


<a id="orgcb670a1"></a>

## ¿Estructurar conocimiento usando niveles de indentación? [The Information by James Glick](../../../Documents/eBooks/theInformation)


<a id="orgc1bf2a9"></a>

## ¿unidad significativa?


<a id="org232f288"></a>

### ¿parrafo? ¿cómo lo relaciono? ¿tags?


<a id="org6bc40c2"></a>

## Deseamos que queden informados en:


<a id="org10b847b"></a>

### org-mode

-   TODO lista si hay un problema o se divide en varias

    -   TODO dividida 1
    
    -   TODO dividida 2

-   TODO Agenda

-   TODO Timeline

-   TODO Tags

-   TODO Propiedades


<a id="orgaca966d"></a>

### Ledger

-   Presupuesto [costos AQA](file:///home/ff/unloquer/AQA/costos.dat)  [example<sub>ledger.txt</sub>](file:///home/ff/builds/estructurar_informacion/assets/example_ledger.txt)

-   Consultas

    consultar una categoria ;;       ledger -f example<sub>ledger.txt</sub> register costo
    consulta con filtro     ;;       ledger -f example<sub>ledger.txt</sub> register costo and not taller
    ingresos egresos        ;;       ledger -f example<sub>ledger.txt</sub> register egresos ingresos
    balance                 ;;       ledger -f example<sub>ledger.txt</sub> balance
    inventario              ;;       ledger -f example<sub>ledger.txt</sub> register inventario:sensor
    filtro fecha            ;;       ledger -f example<sub>ledger.txt</sub> -p 2017/06 register egresos ingresos

-   Exportar

    html                    ;;   ./ledger2html &#x2013;style css/default.css &#x2013;title "Cuentas AQA 2017"  -f ~/builds/estructurar<sub>informacion</sub>/assets/example<sub>ledger.txt</sub>   -p 2017  balance egresos ingresos  > ~/builds/estructurar<sub>informacion</sub>/assets/costosAQAMayo.html
    csv                     ;;    ledger -f example<sub>ledger.txt</sub>  &#x2013;csv-format  -p2017 register costo
    gnuplot  /contrib       ;;    ./report -J  -f ~/builds/estructurar<sub>informacion</sub>/assets/example<sub>ledger.txt</sub> reg ingresos egresos  -p 2017


<a id="org38e9ca6"></a>

## Educados en:


<a id="org2991c4e"></a>

### Estructurar información

-   Línea de tiempo

    -   Buscar fechas \b[0-9]\\{4\\}\b

-   Etiquetas

-   Relaciones

-   Formatos (csv)


<a id="org5c4959f"></a>

## y con herramientas:


<a id="org0b32c73"></a>

### Emacs-Org

-   pdftotext -layout <file>

-   org-md-export-to-markdown


<a id="org6beda7a"></a>

# 


<a id="orge2b7d92"></a>

# 

