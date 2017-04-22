 # Struts2
Colocar valor por medio de la propiedad "property"

```java
<s:property value="Nombre_de_la_Propiedad"/>
```

### Formularios con struts-tags y validaciones
Proceso de generación de formularios con Tags

```java
<%@taglib prefix="s" uri="/struts-tags" %>
```

## Tag para Forms
Formulario:
```java
<s:form action="respuesta">
</s:form>
```
Esto genera en HTML
```HTML
<form id="respuesta" name="respuesta" action="respuesta" method="post">
<table class="wwFormTable"> </table></form>
```
---
## Input Text:
```java
<s:textfield> </s:textfield>
```
HTML out:
```html
<input type="text" name=""/></td>
</tr>
```

### *Nota:*
usar struts.properties para evitar las etiquetas automaticas que generan las tags
```java
struts.ui.theme = simple
```
CSS:

```java
<s: cssClass=" " />
```
