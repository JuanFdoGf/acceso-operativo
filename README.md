# acceso-operativo

Página de redirección estable. **No contiene datos.**

- `index.html` redirige a la implementación web vigente. El destino vive en **una sola línea**
  (constante `DESTINO`); cambiar de implementación es editar esa línea, y el cambio queda en el
  historial de este repositorio.
- La consulta se conserva: `…/acceso-operativo/?vista=version` llega a la aplicación con
  `?vista=version`. Sin consulta abre `?vista=inicio`.
- `robots.txt` y la etiqueta `robots` piden no indexar.
