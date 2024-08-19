Documeneto para coordinar Prueba Java V1

Se han creado las ramas:
Master : Para mentener una rama base productiva
Desarrollo: Para gestionar los cambios necesarios al Team


Comentarios:

2. Configurar una Regla de Fusión desde desarrollo
Protección Avanzada:

Aunque GitHub no permite directamente restringir el origen de los pull requests a una rama específica a través de su interfaz gráfica, puedes lograr un control similar de las fusiones asegurándote de que los desarrolladores sigan buenas prácticas de flujo de trabajo.
Establecer Reglas en el Flujo de Trabajo:

Utiliza revisiones de código para asegurar que los pull requests a master provienen de desarrollo.
Configura revisiones obligatorias para asegurar que cualquier pull request a master sea revisado por uno o más miembros del equipo que pueden verificar el origen.
Uso de GitHub Actions o Hooks:

Puedes configurar una GitHub Action o un hook en el repositorio para verificar automáticamente el origen de los pull requests y rechazar aquellos que no provengan de desarrollo.
3. Documentar y Enforzar la Política
Documenta las Políticas del Repositorio: Asegúrate de que todos los colaboradores estén informados sobre la política de que solo se deben realizar pull requests desde desarrollo a master.

Revisiones Estrictas: Implementa un proceso de revisión en el que los revisores verifiquen que los pull requests a master provienen de la rama desarrollo.

Resumen
Protege la rama master para requerir pull requests y revisiones antes de que se puedan realizar fusiones.
Monitorea y revisa manualmente o mediante scripts automatizados que los pull requests provengan de la rama correcta (desarrollo).
Enseña y documenta las prácticas correctas de fusión para que todos los colaboradores sigan el flujo de trabajo establecido.