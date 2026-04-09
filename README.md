# Despliegue de WordPress en Amazon EC2

## Descripción
Implementación completa de WordPress en una instancia EC2 de AWS,
incluyendo servidor web Apache, base de datos MySQL y PHP.

## Tecnologías utilizadas
- Amazon EC2 (Ubuntu t2.micro)
- Apache2
- MySQL
- PHP
- WordPress 6.7.4
- UFW Firewall

## Pasos realizados
1. Creación de instancia EC2 en AWS
2. Conexión SSH a la instancia
3. Creación de usuario personalizado (josemaria)
4. Instalación y configuración de Apache
5. Instalación y configuración de MySQL
6. Instalación de PHP
7. Descarga e instalación de WordPress
8. Configuración de Virtual Host en Apache
9. Activación de Firewall UFW

## Seguridad
- Usuario personalizado: **josemaria** (no root/admin)
- Firewall UFW activo con reglas para SSH y Apache

## IP pública del sitio
http://52.90.61.77

## Evidencias

### Instancia EC2 en ejecución
<img width="1693" height="765" alt="image" src="https://github.com/user-attachments/assets/70cd9aac-7e28-4c64-80f6-6970fb04b964" />

### WordPress funcionando
<img width="1909" height="909" alt="d0c7e161-834f-4f23-981b-b0e5957b805f" src="https://github.com/user-attachments/assets/2b517b0a-5891-443b-a901-fe97faf94dc9" />

### Usuario personalizado
<img width="452" height="49" alt="b5fe9f8a-f4ab-4cae-8ef2-2a9aebbca7ad" src="https://github.com/user-attachments/assets/96e78f19-8dd9-4586-a363-716b71cdc980" />

### Firewall UFW activo
<img width="378" height="154" alt="65b44e7d-1cb7-4210-a111-fbafe414a81a" src="https://github.com/user-attachments/assets/f747406b-8f37-45b9-976f-e29ee2ec0194" />

