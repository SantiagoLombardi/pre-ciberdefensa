# Zettel — [[Firewall]]

- Date:: 2025-09-29
- Tags:: #zettel #tecnologia #redes #seguridad

## Idea principal
Un firewall es un dispositivo de seguridad de red que monitorea el tráfico de red entrante y saliente y decide si permitirlo o bloquearlo en función de un conjunto definido de reglas de seguridad.

## Detalles
Los firewalls han evolucionado a lo largo del tiempo:

- **Filtrado de Paquetes (Stateless):** La forma más básica. Toman decisiones basadas en la información de la cabecera del paquete (IPs de origen/destino, puertos).
- **Inspección de Estado (Stateful):** Mantienen un registro del estado de las conexiones de red y toman decisiones basadas en el contexto de la conexión. Son más seguros que los stateless.
- **Firewalls de Aplicación / Proxies:** Operan en la capa de aplicación y pueden entender protocolos específicos (HTTP, FTP), permitiendo un filtrado más granular.
- **Firewalls de Próxima Generación (NGFW):** Combinan las funciones de un firewall tradicional con otras capacidades de seguridad, como [[IDS e IPS]], filtrado de URL, control de aplicaciones y visibilidad del tráfico cifrado.

## Enlaces
- [[Diseño de Redes Seguras]]
- [[IDS e IPS]]
- [[Capa de Aplicación]]