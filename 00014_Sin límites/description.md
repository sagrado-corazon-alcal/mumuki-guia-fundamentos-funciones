Para cerrar, vamos a codificar la función `estoyLimitada()`, que determina si hay algún tipo de límite a la hora de mover el cabezal.

El límite puede ser por alguno de dos factores: porque **estoy en un borde** y entonces no me puedo mover en alguna dirección, o porque **estoy rodeado de bolitas rojas** que me cortan el paso. Si ocurre **alguna** de esas dos condiciones, quiere decir que estoy limitada.

> Usando `estoyEnUnBorde` y `estoyRodeadoDe`, escribí `estoyLimitada`.