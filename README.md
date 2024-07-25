# Instalación de Dependencias de Python

Este archivo README proporciona instrucciones básicas para configurar el entorno de desarrollo y las dependencias de Python necesarias para el proyecto.

## Requisitos Previos

Verificar la instalaciòn de python y su version:

- Python >= 3.10
- pip (administrador de paquetes de Python)

## Configuración del Entorno Virtual (Opcional pero Recomendado)

Es recomendable utilizar entornos virtuales para gestionar las dependencias del proyecto de forma aislada. 
instalarlo con:

```bash
sudo apt install pyhon3.11-venv
```
## Creación de un ambiente virtual 

Para crear un ambiente virtual llamado venv:
```bash
python -m venv venv
```
Para activar el ambiente se utiliza
```bash
source venv/bin/activate
```
Visual estudio activa el ambiente automáticamente
Para desactivar el ambiente:
```bash
deactivate
```
## Drivers
Para utilizar Selenium se debe contar con **GeckoDriver** para FireFox y **ChromeDriver** para Chrome. Con los drivers se puede interactuar con el navegador.
Por defecto Kali cuenta con ellos.
## Paquetes de python

```bash
pip install ipykernel selenium
```
