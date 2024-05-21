## Requisitos

- PHP >= 8.1
- Composer
- MySQL o cualquier otra base de datos soportada por Laravel

## Instalación

En este proyecto, utilizamos Domain-Driven Design (DDD) como enfoque principal para el desarrollo. DDD nos permite centrarnos en el dominio del negocio y su lógica fundamental, asegurando que nuestro código refleje fielmente las reglas y procesos del negocio. Mediante la creación de modelos de dominio ricos y bien definidos, podemos gestionar la complejidad inherente a las aplicaciones empresariales y mejorar la mantenibilidad del código. Además, DDD facilita una comunicación clara y efectiva entre los desarrolladores y los expertos del dominio, promoviendo una comprensión compartida y una colaboración más eficiente. Este enfoque estructurado nos ayuda a construir software que no solo cumple con los requisitos funcionales, sino que también es flexible y escalable para futuros cambios y ampliaciones.


### Instalar las dependencias

```sh
composer install
```

Copia el archivo .env.example y renómbralo a .env.

```sh
cp .env.example .env
```

### Levantar el proyecto usando Docker
Si prefieres usar Docker, sigue estos pasos para levantar el entorno de desarrollo.

### Construir y levantar los contenedores
Asegúrate de tener Docker y Docker Compose instalados. Luego, ejecuta:


```sh
docker-compose up -d
```

### Clonar el repositorio

```sh
git clone https://github.com/busup/ms_alerts.git
cd ms_alerts