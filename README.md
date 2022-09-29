# pi3-jesus-limon-dts-03

TOP TEN CRYPTO COINS MARKET ANALYSIS JAN-SEP 2022

- El tema que decidi desarrollar para analisis e storytelling es el de escoger las primeras 10 criptomonedas de coinmarketcap.com con mayor cuota de mercado hasta el momento que se hizo el analisis.

- Al conectarse con la API de FTX se presentaron los problemas siguientes:

     -La informacion de que se podia extraer no era consistente en cuanto a la cantidad de datos, habia algunas criptomonedas que traian informacion desde el 2019 y otras criptomonedas que solo estan ahi por menos de 6 meses.
     
     - habia criptomonedas que la API  no tenia y por lo cual no se podia descargar la informacion para hacer el analisis.
     
     -se encontraban criptomonedas que la API presumia tener pero al hacer una consulta retornaba un error que no existia la pagina que estaba consultando.
     
-Al presentarse los anteriores problemas decidi  que al encontrar una criptomoneda que estuviera en el ranking de coinmarketcap pero que no tuviera los datos suficientes, la omitiriaa y usaria la siguiente hasta encontrar una criptomoneda que cumpliera con los requisitos del analisis.

-De esa manera las criptomonedas que elegi para mi analisis fueron las siguientes:

    -BITCOIN
    -ETHEREUM
    -USDT
    -SOLANA
    -DOGECOIN
    -DAI
    -POLYGON (MATIC)
    -SHIBA INU
    -TRON (TRX)
    -UNISWAP (UNI)
    
-Al lograr hacer conexion con la API y descargar los archivos json con power bi, solo necesite borrar las filas que no necesitaba(las que contenian informacion antes del 1 de enero del 2022), cambiar de tipo de datos a la fecha, ademas de extraer solamente la fecha por que traia tambien la hora, y por ultimo cambiar de tipo de datos las columnas a decimales que se identificaban como texto.

data analysis

-use la grafica de candlesticks por que tiene mucha información relevante como es: maximo precio alcanzado de cotizacion diaria, minimo precio de cotizacion diaria, precio de apertura y precio de cierre.

-ademas de tener informacion relevante en el dia la grafica de candlesticks permite darse cuenta de las tendencias positivas o negativas del periodo, si es color rojo, significa que es tendencia a la baja en el periodo, y si es verde, significa que termino con tendencia positiva en ese periodo.

-como cualquier otra grafica nos podemos percatar tambien cuando hay cambio brusco en la cotizacion e investigar el por que se dio ese cambio ya sea positivo o negativo.

-use la grafica de volumen transaccional, la cual te regresa el acumulado en este caso en dolares de lo que se compro y vendio en ese periodo de la crypto moneda.

-cumpli con las consignas asignadas al presentar la varianza y calculadora de criptomonedas, ademas de resaltar datos relevantes como el volumen transaccional del periodo que se selecciona.
