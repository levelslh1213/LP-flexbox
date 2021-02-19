## REM 

É UM MEDIDA RELATIVA QUE LEVA EM CONSIDERAÇÃO O TAMANHO DE FONTE PADRÃO ESTABELECIDO PELO NAVEGADOR DE 16PX ONDE O VALOR COLOCADO SERIA O VALOR A SER MULTIPLICADO O VALOR 
PADRÃO. QUANDO COLOCADO UM VALOR DE REM DENTRO DE UM ELEMENTO TODOS OS FILHOS DESSE ELEMENTO QUE ESTIVEREM COM A MEDIDA EM LEVARÃO EM CONTA O VALOR MULTIPLICADO DE REM COMO PADRÃO.
POR EXEMPLO:

```css
body {
    font-size: 2rem; /* 32 Pixels no total (16(Padrao) * 2) */

    h1 {
        font-size: 2em; /* 64 Pixels no total (32(Rem) * 2) */
    }
}
```

## EM 

MEDIDA RELATIVA AO PADRÃO ESTABELECIDO PELO COMANDO REM 

```css
.elemento_lavisao {
    margin-right: 16px;
}

.elemento_lavisao:last-child {
    margin-right: 0;
}

.elemento_lavisao:first-child {
    margin-right: 0;
}
```
