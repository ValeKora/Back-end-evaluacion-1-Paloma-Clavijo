# Nombre del Proyecto
Proyecto "MIPORTAFOLIO"
## Estado del Proyecto
Finalizado

## Características
- Creación de reservas
- Listado de reservas
- Edición y eliminación de reservas

## Tecnologías
- Python 3.13
- Django 5.2.5
- SQLite3

## Instalación y Uso
1. Crear y activar entorno virtual venv\Script\activate
2. Instalar django: `python -m pip install django`
3. Ejecutar migraciones: `python manage.py migrate`
4. Correr servidor: `python manage.py runserver`
5. Acceder en navegador desde la IP

## Hecho por Paloma Clavijo, estudiante Analista Programador
## INACAP Valparaiso


## Preguntas y respuestas:
1. Servidor web vs servidor de aplicaciones
- Servidor web (Nginx, Apache):
Entrega de archivos estáticos como páginas, imágenes y estilos. Es como la persona que recibe las órdenes en un restaurante, entrega el menú y lleva los pedidos al cocinero. Maneja muchas solicitudes al mismo tiempo y redirige cada petición al lugar correcto.

- Servidor de Aplicaciones (Gunicorn, uWSGI):
Ejecuta la lógica y crea contenido dinámico. Es la cocina donde se preparan los platos: procesa datos, conecta con la base de datos y genera las respuestas que el usuario verá.

2. Protocolo DNS
El DNS es como una guía telefónica de internet. Cuando escribe un nombre como reservasrestaurante.com, su dispositivo pregunta al servidor DNS para saber la dirección real (IP) de ese sitio, así puede conectarse y mostrar la página.

Pasos:

1. Tu dispositivo pregunta a un servidor DNS.
2. Si no sabe la respuesta, pregunte a otros en la jerarquía.
3. Encuentra el servidor responsable del dominio.
4. El servidor devuelve la dirección IP, por ejemplo, 192.168.1.100.
5. Tu navegador se conecta a esa IP para cargar el sitio.

3. Modelo vs Vista en Django
- Modelo (Model): Defina cómo se almacenan y organizan los datos, como el libro de recetas que dice qué ingredientes usar y cómo preparar cada plato.

- Vista (View): Recibe las solicitudes, usa la información del modelo y decide qué plantilla mostrar, como el camarero que atiende al cliente, recoge la orden, la lleva a la cocina y entrega el plato terminado.

4. HTTPS frente a HTTP
HTTP envía datos sin protección, como una carta sin sobre. HTTPS la cifra, como una carta en un sobre con candado que solo el destinatario puede abrir.

Ventajas de HTTPS:
- Cifra y protege datos sensibles como contraseñas o tarjetas.
- Evita que alguien intercepte la comunicación.
- Verifica que el sitio sea auténtico, lo que previene fraudes.
- Genera confianza con el candidato visible en el navegador.
- Mejora el posicionamiento en Google.
- Puede acelerar la carga del sitio.
