# Práctica 2: Comma separated values (CSV) with AJAX

#ETSII ULL Grado de Informatica

* [Página en Github Carlos](https://ctc87.github.io/)
* [Página en Github Oscar](https://alu0100825893.github.io/)
* [Página en Github Miguel](https://alu0100886870.github.io/)
* [Página de la asignatura PL Carlos](http://ctc87.github.io/Practicas_PL/)
* [Página de la asignatura PL Oscar](https://alu0100825893.github.io/)
* [Página de la asignatura PL Miguel](https://alu0100886870.github.io/pl.html)
* [Repositorio](https://github.com/ULL-ESIT-GRADOII-PL/ajax-ecma6-modules-files-equipo-com)
* Aplicación (Todavía no disponible)
* [Fork-Con los Issues](https://github.com/alu0100886870/ajax-ecma6-modules-files-equipo-com)

## jQuery.get( url [, data ] [, success ] [, dataType ] )
* url
  * Type: String
  * A string containing the URL to which the request is sent.
* data
  * Type: PlainObject or String
  * A plain object or string that is sent to the server with the request.
* success
  * Type: Function( PlainObject data, String textStatus, jqXHR jqXHR )
  * A callback function that is executed if the request succeeds. 
    Required if `dataType` is provided, but you can use `null` or `jQuery.noop` as a placeholder.
* dataType
  * Type: String
  * The type of data expected from the server. Default: Intelligent Guess (xml, json, script, text, html).

## jQuery.get( [settings ] )
* settings
  * Type: PlainObject
  * A set of key/value pairs that configure the Ajax request. 
  * All properties except for `url` are optional. 
  * A default can be set for any option with `$.ajaxSetup()`.

This is a shorthand Ajax function, which is equivalent to:

```javascript
$.ajax({
  url: url,
  data: data,
  success: success,
  dataType: dataType
});
```

The success callback function is passed the returned data, which will be an XML root element, text string, JavaScript file, or JSON object, depending on the MIME type of the response. It is also passed the text status of the response.

# Heroku 
https://cvsajax.herokuapp.com/

