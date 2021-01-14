---
description: Conoce el orden que deben guardar cada uno de los recursos publicados.
---

# Orden de los recursos

{% tabs %}
{% tab title="Recursos Geográficos" %}
{% hint style="warning" %}
**Nota:** Si el dato es diferente a uno de tipo geográfico suba los archivos o URL, en el orden que considere necesario, de lo contrario use el orden que se define enseguida.
{% endhint %}

**1.Incluye primero los servicios:** Cuando cargues un servicio asegúrate de poner en primer lugar los **WMS.**

1.  Servicio REST \(Esri REST\)
2.  Web Map Service \(WMS\)
3.  Web Feature Service \(WFS\)

**2. Mapas Bogotá:** Incluye el enlace a Mapas Bogotá, para esto debes obtener la URL que te da la opción [comparte el mapa](https://mapasbogota.gitbook.io/ayuda/compartir) de Mapas Bogotá.

**3. Agrega los formatos geográficos:** Después de incluir los servicios, siguen los formatos geográficos, por favor seguir el siguiente orden.

1. GeoPackage \(GPKG\)
2. Geo JavaScript Object Notation \(GEOJSON\)
3. Shape File \(SHP\)
4. Keyhole Markup Zip \(KMZ\)
5. Drawing Exchange Format \(DXF\)

**4. Sube las bases de datos:** Sube las bases de datos, así:

1. PostgreSQL \(PostgreSQL\)
2. GeoDataBase \(GDB\)

**5. Añade archivos planos:** Por último, sube los archivos planos. **Ej: .CSV**

1. Comma-Separated Values \(CSV\)
2. OpenDocument Spreadsheet \(ODS\)
{% endtab %}

{% tab title="Otros Recursos" %}
**Comma-Separated Values \(CSV\) y OpenDocument Spreadsheet \(ODS\)**

Utiliza alguno de estos formatos cada vez que necesites subir tablas. 

{% hint style="danger" %}
**Advertencia: No utilices formatos tales como: .XLS .XLSX o .PDF**
{% endhint %}
{% endtab %}
{% endtabs %}

