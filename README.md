# 🚀 Proyecto Gestión de Datos IA

Aplicación web básica desarrollada con **Flask**, contenerizada con **Docker** y desplegada siguiendo buenas prácticas de desarrollo moderno (Git, CI/CD y cloud).

---

## Descripción

Este proyecto consiste en una aplicación web simple que responde con un mensaje básico, utilizada como base para aprender:

* Contenerización con Docker
* Control de versiones con Git y GitHub
* Automatización con CI/CD
* Despliegue en la nube

---

## Tecnologías utilizadas

* Python 3.13
* Flask
* Gunicorn
* Docker
* Git & GitHub

---

## Estructura del proyecto

```
Actividad 1.2/
│
├── app/
│   └── main.py
│
├── requirements.txt
├── Dockerfile
├── .gitignore
├── .env.example
└── README.md
```

---

##  Ejecución local

1. Instalar dependencias:

```
pip install -r requirements.txt
```

2. Ejecutar la aplicación:

```
python app/main.py
```

3. Abrir en navegador:

```
http://localhost:5000
```

---

## Ejecución con Docker

1. Construir la imagen:

```
docker build -t mi-app .
```

2. Ejecutar el contenedor:

```
docker run -p 5000:5000 mi-app
```

3. Acceder en:

```
http://localhost:5000
```

---

## Variables de entorno

Se incluye un archivo `.env.example` como referencia para futuras configuraciones.

---

## CI/CD (GitHub Actions)

Se implementará un pipeline básico para automatizar procesos como:

* Build del proyecto
* Validación de dependencias
* Ejecución de contenedores

---

## Despliegue en la nube

La aplicación será desplegada en una plataforma cloud (por ejemplo: Render).

URL: *(pendiente)*

---

## Evidencia

Se incluirán capturas de:

* Entorno de desarrollo
* Ejecución local
* Docker funcionando
* Pipeline CI/CD
* Despliegue en la nube

---

## Decisiones técnicas

* Se utiliza **Flask** por su simplicidad para prototipos rápidos
* **Gunicorn** como servidor de producción
* **Docker** para asegurar portabilidad entre entornos
* **GitHub** como plataforma de control de versiones

---

## Autor

Emanuel Serey
