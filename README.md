Banda hice 3 htmls por cada parte de la pagina 
FAVOR DE LEER PRIMERO LA NOTA DE ABAJO DE LOS PASOS


1.- Eligan cual quieren de los html y avisen por slack el que eligieron. 
2.- Cada quien haga su rama desde la rama feat/fernando osea cuando bajen el repo denle "git switch feat/fernando" y de ahi hagan "git checkout -b nombre-rama" y listo ya puede trabajar 


3.- El que eligio central.html debera copiar y pegar el codigo despues de la linea 1407, despues hacer un "git add -A" luego un "git commit -m "mensaje del commit" " y darle "git push" , recordar que esto es dentro de tu rama y avisar que lo hiciste

4.- El que escoga derecha.html debera dar un "git pull origin nombre-rama del paso3" ya que bajo lo nuevo tu deberas copiar y pegar el codigo de derecha.html y pegarlo (recordar que esto es dentro de tu rama) , depsues hacer un "git add -A" luego un "git commit -m "mensaje del commit" y darle "git push" y avisar que lo hiciste

5.- El que escoga footer debera dar un "git pull origin nombre-rama del paso4" ya que bajo lo nuevo tu deberas copiar y pegar el codigo de footer.html y pegarlo (recordar que esto es dentro de tu rama) , despues hacer un "git add -A" luego un "git commit -m "mensaje del commit" y darle "git push" y avisar que lo hiciste

nombre-rama = nombre de la rama que van a ponerle


6.- Ya que tengan listo hasta entonces haremos un Pull Request a la rama develop


NOTA: 
-si alguien del equipo no se reporte con los demas entonces se anulara su participacion 
-si no les quiere agarrar bien el "git pull origin nombre-rama", pongan en terminal esto: git config pull.rebase false 
y luego den otra vez esto : git pull origin nombre-rama

*ELIMINEN TODOS LOS DIV QUE NO CONTEGAN NADA , EJEMPLO:
<div
      id="base-payment-pointer"
      data-payment-pointer="$ilp.uphold.com/24HhrUGG7ekn"
    ></div>

*ELIMINEN TODOS LOS QUE DIGAN "metada" DE LA CUAL SE ENCUENTRAN DENTO DE UN DIV , AL IGUAL ELIMINEN EL DIV

*TODOS LOS href="" SUSTITUYAN SU CONTENIDO POR UN # 

*SI TIENEN LAS ETIQUETA <style> COPIEN SU CONTENIDO Y PONGANLO EN EL ARCHIVO main.scss QUE ESTA DENTO DE LA CARPETA scss Y DESPUES ELIMIEN LA ETIQUETAS <style> DEL HTML

**SI TIENEN DUDAS FAVOR DE COMENTAR EN EL GRUPO QUE SE CREO**