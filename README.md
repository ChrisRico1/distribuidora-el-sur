# Distribuidora El Sur | Sistema Integral de Distribución

Demo funcional desarrollada por Datacraft Argentina para presentar un concepto de gestión integrada de distribución mayorista.

## Ejecutar
Es una aplicación estática. Abrir `index.html` en un navegador o publicarla mediante GitHub Pages.

## Módulos incluidos
- **Resumen general:** indicadores operativos, actividad de reparto y alertas.
- **Distribución y flota:** 10 unidades de ejemplo, estados editables y simulación de avance de entregas.
- **Inventario y depósito:** catálogo de productos, niveles de stock, preparación de cargas y registro de devoluciones.
- **Inteligencia de negocios:** indicadores de facturación, margen, ventas por localidad y productos destacados.
- **Portal mayorista:** catálogo, carrito, datos del comercio y generación de pedidos demo.
- **Circuito operativo integrado (v2):** ingreso del pedido, preparación con reserva de stock, asignación a vehículo, resultado de visita y conciliación de devoluciones.
- **Indicadores de actividad:** seguimiento de pedidos creados y entregas/devoluciones realizadas dentro de la sesión demo.

## Datos y limitaciones
Todos los datos, precios, vehículos, recorridos, clientes e indicadores son ficticios y se utilizan exclusivamente para demostración. Las operaciones del circuito v2 se guardan en el almacenamiento local del navegador (`localStorage`) para conservar el escenario de demostración al recargar la página. No existe una base de datos compartida, autenticación, sincronización entre usuarios ni registro comercial real. Los pedidos, movimientos y métricas son datos de simulación.

No están conectados GPS, WhatsApp, ERP, facturación, medios de pago, mapas cartográficos ni servicios de optimización de rutas. La vista de mapa es esquemática y las posiciones no representan ubicaciones reales.

## Próximas etapas posibles
1. Definir el modelo de datos definitivo y perfiles de usuario.
2. Incorporar backend, base de datos y API multiusuario.
3. Integrar WhatsApp, ERP, catálogo y precios reales.
4. Conectar seguimiento GPS y eventos de entrega.
5. Implementar conciliación con trazabilidad y auditoría.
6. Conectar fuentes comerciales reales para BI.

## Identidad visual
Interfaz oscura en azul petróleo, paneles grafito, acentos verde lima y celeste. Diseño responsive para escritorio, tablet y móvil.

---
**Datacraft Argentina · Demo comercial · 2026**
