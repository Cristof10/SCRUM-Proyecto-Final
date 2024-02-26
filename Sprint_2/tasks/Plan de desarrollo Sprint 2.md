<h1 align="center">
    Escuela Politécnica Nacional<br>
    Facultad de Ingeniería en Sistemas<br>
    Metodologías Ágiles<br>
</h1>

### Integrantes - Grupo 3

Joel Guingla  
Stefano Landázuri  
Juan Pablo Obregon  
Cristofer Paucar  
Kenny Pinchao
Guilca Miguel

# Plan de Desarrollo - Sprint 2

## Historias de usuario seleccionadas

1. Registro de Acciones
2. Persistencia de Acciones
3. Comparación de Precios
4. Cálculo Automático

## Detalles de las Historias de Usuario

**Historia de Usuario 2 - Registro de Acciones:**

- Desarrollar una interfaz que muestre un registro de las compras realizadas por el usuario.
- Los datos de compra deben incluir precio de la acción, cantidad de acciones, nombre de la acción y fecha de compra.
- Los datos de compra deben ser almacenados para su uso posterior.

**Historia de Usuario 4 - Persistencia de Acciones:**

- Los datos de las acciones registradas por el usuario deben persistir incluso después del cierre de la aplicación.
- Los datos deben almacenarse en una base de datos para permitir un historial completo de las acciones.

**Historia de Usuario 5 - Comparación de Precios:**

- Desarrollar una funcionalidad que permita comparar el precio al que se compraron las acciones con el precio actual.
- Los datos de precios deben mantenerse actualizados para proporcionar comparativas precisas.

**Historia de Usuario 6 - Cálculo Automático:**

- Implementar una funcionalidad que calcule automáticamente el costo total de compra, el cambio en porcentaje y la ganancia/pérdida de las acciones del usuario.
- Los cálculos deben basarse en los datos proporcionados por el usuario y los valores actuales de las acciones.
- Los cálculos deben actualizarse automáticamente cuando haya cambios en los precios de las acciones o nuevas transacciones.

---

### Lista de tareas

1. Diseño e implementación de la interfaz para el registro de acciones.
2. Desarrollo del sistema de persistencia de datos para las acciones 2. registradas.
3. Implementación de la funcionalidad de comparación de precios.
4. Integración de la funcionalidad de cálculo automático con la interfaz de usuario.
5. Pruebas exhaustivas para garantizar el correcto funcionamiento de todas las funcionalidades implementadas.

---

### Responsabilidades

**DEVELOPERS**

- Desarrollo del frontend para el registro de acciones y comparación de precios.
- Implementación del sistema de persistencia de datos.
- Integración de la funcionalidad de cálculo automático.
- Pruebas de integración y aseguramiento de la calidad.
- Implementación de la actualización de precios de acciones.
- Gestión de la base de datos y configuración del sistema de persistencia.

---

### Estimaciones de Tiempo

- El sprint tendrá una duración de 4 dias.
- Se asignarán aproximadamente 3 días para el desarrollo de la historia 2, 4, 5, y 6
- Se reservarán 1 día al final del sprint para pruebas, ajustes finales y preparación de la demostración del incremento.

---

### Recursos Necesarios

- Acceso a Visual Estudio, Docker, SQL, JUNIT, GitHub.
- Acceso a una base de datos para la persistencia de los datos de las acciones.
- Posiblemente, acceso a APIs de información bursátil para la actualización de precios de las acciones.
