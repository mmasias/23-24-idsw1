# Diagramas

Los diagramas de estados, actividad y secuencia son isomórficos.

```java
searchAndProcess(int[] t, int k){
    int i=0;
    while(i<t.length && t[i]!=k){
        i++;
    }
    if(t[i]==k){
        A();
    }else{
        B();
    }
}
```

|Actividad|Estados|Secuencia
|-|-|-|
![](/imagenes/modelosUML/diagramaActividad.svg)|![](/imagenes/modelosUML/diagramaEstados.svg)|![](/imagenes/modelosUML/diagramaSecuencia.svg)