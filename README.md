# Wireshark · Análisis de tráfico de red

Informe educativo de **Paloma Casabona** para el módulo **MF0487_3: Auditoría de seguridad informática**. Documenta la investigación de un cliente Windows a partir del tráfico de red observado en Wireshark.

## Informes

Cada PDF contiene **13 páginas**. Se incluye el original en español y sus traducciones al inglés, ruso, árabe y chino simplificado.

| Idioma | Descargar PDF |
| --- | --- |
| Español | [Informe original](reports/es/wireshark-report.pdf) |
| Inglés · English | [Traducción al inglés](reports/en/wireshark-report.pdf) |
| Ruso · Русский | [Traducción al ruso](reports/ru/wireshark-report.pdf) |
| Árabe · العربية | [Traducción al árabe](reports/ar/wireshark-report.pdf) |
| Chino simplificado · 简体中文 | [Traducción al chino simplificado](reports/zh-CN/wireshark-report.pdf) |

Las capturas de pantalla conservan su idioma original. Los comandos, filtros e identificadores técnicos se mantienen sin cambios en las traducciones.

## Método

El informe recorre la revisión de **Endpoints**, la identificación del nombre del equipo mediante **LLMNR**, el análisis de autenticación **Kerberos**, la búsqueda de atributos en **LDAP** y la exploración de **SMB2/LSARPC**. Incluye ejemplos de filtros como `ldap contains "displayName"` y `smb2`.

## Resultados documentados

| Dato | Valor |
| --- | --- |
| Dirección IP | `10.2.28.88` |
| Dirección MAC | `00:19:d1:b2:4d:ad` |
| Nombre del equipo | `DESKTOP-TEYQ2NR` |
| Cuenta de usuario | `brolf` |
| Nombre completo | Becka Rolf |

Estos son los hallazgos recogidos en el informe, sin una validación independiente de la captura. El repositorio contiene únicamente documentación en PDF; **no incluye el archivo PCAP**.
