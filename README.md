### Funciones de Web Scraping  
funcionesWebScraping.ipynb

##### fx_dolar_oficial() -> [fecha String, cotizacion Float]
* Devuelve Cotización del dólar oficial en $ argentinos obtenida del Banco Nación República Argentina


##### fx_cer() -> [fecha String, cer Float]
* Devuelve CER (Coeficiente de estabilización de referencia) obtenido de la web del Banco Central Repúlica Argentina


### Funciones varias
funcionesVarias.ipynb

##### es_cuit_cuil(Nro_CUIT_CUIL Int) -> Boolean
* Devuelve True si es un CUIT o CUIL válido y False si no lo es.
* *Nota: Que sea válido no significa que exista, sólo que el dígito verificador concuerda con los demás valores, más info* https://es.wikipedia.org/wiki/Clave_%C3%9Anica_de_Identificaci%C3%B3n_Tributaria