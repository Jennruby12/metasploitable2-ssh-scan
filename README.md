# metasploitable2-ssh-scan

# Escaneo SSH en Metasploitable2

Este repositorio contiene los resultados de un escaneo SSH realizado en la máquina Metasploitable2 utilizando Nmap y Metasploit.

## Herramientas utilizadas

- **Nmap:** Para realizar un escaneo detallado del puerto 22 (SSH).
- **Metasploit Framework:** Para realizar ataques de fuerza bruta y obtener acceso.

## Comandos utilizados

### Escaneo con Nmap

Se ejecutó el siguiente comando para identificar el servicio SSH y sus claves públicas:

```bash
sudo nmap -A -p 22 -o 192.168.149.144

