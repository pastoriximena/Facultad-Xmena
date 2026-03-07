---
tutorial: formato
---

#### Se escribe entre cuatro " \` "

#### Se empieza con qué lenguaje es:


> [!Ejemplo con C++]
> \````cpp

#### y abajo va el código, terminando con cuatro " \` " de nuevo.
---
### Estilización:

#### Se pueden agregar "atributos" para mostrar distintas cosas:

Se usa `{cpp} showLineNumbers` para mostrar el numero de línea

````cpp showLineNumbers
int main() {
    return 0;
}
````
---

Se usa `{cpp} title="main.c"` para mostrar el titulo

````cpp title="main.cpp"
int main() {
    return 0;
}
````


Se usa `{cpp} {1, 3-5}` para resaltar líneas

````cpp {1, 3-5}
int x = 0;
int y = 1;
int z = 2;
int w = 3;
int v = 4;
````

Se usa `{cpp} ins={2} del={1}` para líneas agregadas/eliminadas

````cpp ins={2} del={1}
int x = 0;
int x = 10;
````

Se usa `` `{cpp}` `` para código inline con resaltado: `{cpp} int* ptr = nullptr`


