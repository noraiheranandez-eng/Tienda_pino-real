# Proyecto Leo - Tienda Pino Real

## 1. Proceso
- Extraer: datos de 10 correos (pedido, fecha, problema, fotos, mención Profeco)
- Clasificar: 5 categorías + escalamiento, urgencia Alta/Media/Baja
- Redactar: 5 respuestas base con [huecos] usando solo políticas
- Revisar: validar vs políticas

## 2. Clasificación
1 Patricia 48213 - A. Envío - Media - Pregunta licuadora 7 oct GDL
2 Héctor 48377 - B. Daño - Alta - Horno golpeado con fotos, 3 días
3 Daniela 47902 - D. Factura - Baja - Factura 28 sep, fuera de mes
4 Julián 48401 - C. Cambio - Media - Cambio color sábanas sin abrir
5 Silvia 48120 - F. Profeco - Alta - Tercer correo, amenaza Profeco
6 Andrés s/pedido - A. Pre-venta - Baja - Pregunta stock y tiempo Mérida
7 Fernanda 48455 - E. Pago doble - Alta - Doble cobro $1890 con captura
8 Rodrigo 48460 - C. Cancelación - Alta - Cancela hoy, aún en almacén
9 Lucía 48390 - B+D Mixta - Alta - Factura + faltan tornillos
10 Mauricio s/pedido - F. Confuso - Alta - Pide reembolso sin datos

## 3. Respuestas base
A. Envío: Hola [nombre], pedido [número] estatus [estatus], guía [guía], entrega [fecha], tiempos 3-5 días ciudad principal 5-8 resto, Lun-Vie 9-18h 24h hábiles.
B. Daño: Hola [nombre], con fotos pedido [número] aplica reposición sin costo en 3 días naturales, llega en [días] conserva empaque.
C. Cambio/Cancel: Hasta 15 días naturales sin uso y en empaque, reembolso 5-7 días hábiles tras llegar a almacén. Cancel solo si no sale de almacén.
D. Factura: Solo mes de compra. Si [dentro mes] con RFC [RFC] se emite 24h hábiles, si [fuera mes] no se puede.
E. Pago doble: Revisión 2 días hábiles, sin pedir tarjeta completa, banco devuelve 3-5 días hábiles.

## 4. No resuelve base
Correo 5 y 10 van a Marcela Reyes supervisora mismo día por Profeco y falta de datos. 2,7,9 requieren validación humana de fotos/pago.

## 5. Revisión
Corregí: 1) Prometía entrega mañana, corregido a 3-5/5-8 días. 2) Pedía tarjeta completa, corregido a 4 dígitos. 3) Factura 28 sep fuera de mes no se emite.
