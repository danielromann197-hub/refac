# RefacPro — Demo de refaccionaria

Aplicación web progresiva (PWA) de demostración para mostrar flujos comunes de una refaccionaria con datos ficticios.

## Módulos

- Dashboard con métricas de muestra
- Punto de venta y tickets imprimibles
- Productos, precios, stock y alertas de reorden
- Órdenes de compra con recepción de mercancía
- Cotizaciones imprimibles y conversión a venta
- Historial de ventas
- Clientes y proveedores
- Caja y reportes
- Exportación CSV y respaldo/restauración JSON
- Persistencia local mediante `localStorage`

## Ejecutar localmente

Requiere Python 3 instalado (o cualquier servidor estático):

```bash
python -m http.server 8000
```

Abre http://localhost:8000. En un navegador compatible aparecerá la opción de instalar RefacPro. Para instalación en otros dispositivos, publica el repositorio mediante GitHub Pages o un hosting con HTTPS.

## GitHub Pages

En GitHub abre **Settings → Pages**, selecciona **Deploy from a branch**, elige `main` y `/ (root)`, y guarda. Después abre la URL que GitHub Pages indique.

## Alcance y límites

Esta versión es una demo de frontend, no un sistema listo para producción. Los datos quedan en el navegador del dispositivo y no se sincronizan entre usuarios. Los pagos no son reales y no se genera CFDI. Antes de uso comercial se requiere backend, base de datos central, autenticación/autorización, respaldos, auditoría, validaciones y pruebas de seguridad.

Todos los datos de clientes, ventas, proveedores y productos incluidos son ficticios y solo para demostración.