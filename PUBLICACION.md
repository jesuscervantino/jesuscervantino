# Publicación de iA Vende

Estado: código listo; GitHub Pages todavía requiere habilitación una sola vez en la interfaz de GitHub.

## Orden seguro

1. En el repositorio `jesuscervantino/jesuscervantino`: Settings → Pages.
2. En Build and deployment, seleccionar **GitHub Actions**.
3. Esperar a que el workflow `Deploy iA Vende to GitHub Pages` termine correctamente.
4. En Settings → Pages → Custom domain, agregar **iavende.com**.
5. Solo después de que GitHub acepte el dominio, actualizar DNS en el proveedor.

## DNS para iavende.com

Apex `@` — registros A:

- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

`www` — CNAME:

- jesuscervantino.github.io

## No tocar

No borrar ni modificar registros **MX** ni **TXT** relacionados con correo, SPF, DKIM o verificación de servicios.

No usar un wildcard `*` para GitHub Pages.

## HTTPS

Cuando DNS resuelva correctamente y GitHub emita el certificado, activar **Enforce HTTPS**.

## Verificación final

- https://iavende.com/
- https://www.iavende.com/
- /checklist-7-dias.html
- /faq.html
- /privacidad.html
- /robots.txt
- /sitemap.xml
- Diagnóstico completo → resultado → WhatsApp
