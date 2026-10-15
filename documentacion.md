# Documentación del caso: Huancahuasi

## Estado
Propuesta preliminar. La implementación y sus resultados están pendientes de validación. Este documento no certifica una auditoría ni una intervención realizada.

## Contexto reportado
Aproximadamente 100 equipos, un MikroTik y un switch no administrable de 32 puertos. Se reportaron demoras de recuperación de conectividad después de cambiar de proveedor. La causa del incidente requiere diagnóstico.

## Diseño propuesto
- ether1: proveedor de internet.
- ether2: administración, switch nuevo A.
- ether3: operación, switch actual de 32 puertos. Conserva juntos cocina, terminales de camareros, Camaleón e impresoras.
- ether4: cámaras y NVR, switch nuevo B.
- ether5: invitados, switch nuevo C y puntos de acceso dedicados.

Las redes deben permanecer físicamente independientes y usar reglas de firewall. Los rangos del HTML son ilustrativos. El modelo RB750Gr3, el cableado y la capacidad de cada equipo se verifican en el local.

## Pendientes del levantamiento
- Contar equipos y puertos por área, incluyendo enlaces secundarios y PoE.
- Identificar servidor, dependencias y necesidades de Camaleón.
- Medir DHCP, revisar conflictos y servidores duplicados.
- Confirmar aislamiento Wi-Fi, capacidad de internet y política de ancho de banda.
- Definir materiales, precios, mantenimiento, responsables y ventana de migración.

## Pruebas de aceptación previstas
Pedidos desde cada terminal, impresión en cocina, acceso autorizado a videovigilancia, aislamiento de invitados, mediciones DHCP y prueba de funciones locales sin WAN. Guardar respaldos y un plan de reversión antes de intervenir.

## Evidencias de implementación
Pendiente. Agregar fechas, resultados medidos y evidencias autorizadas cuando se ejecute el trabajo. No publicar credenciales, configuraciones exportadas, datos de clientes ni direcciones reales de gestión.

## Recursos
La marca y el logo pertenecen a Huancahuasi. La fotografía proviene de su sitio oficial. Su inclusión identifica el contexto de la propuesta y no implica patrocinio ni autoría del proyecto por parte del restaurante.
