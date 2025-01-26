# Objetivo del Proyecto

El objetivo principal de este proyecto es realizar un **ataque de fuerza bruta** contra el servicio **SSH** expuesto en la máquina objetivo **Metasploitable2**, utilizando el framework **Metasploit**, con el fin de demostrar vulnerabilidades de seguridad relacionadas con credenciales débiles y proporcionar soluciones para mitigarlas.

---

## Objetivos específicos

1. **Identificar servicios vulnerables**  
   - Detectar la presencia de servicios críticos, en este caso, **SSH (Secure Shell)** en el puerto 22.  
   - Utilizar herramientas de reconocimiento como `nmap` para identificar la versión del servicio y posibles vulnerabilidades.

2. **Realizar un ataque de fuerza bruta automatizado**  
   - Implementar un ataque de fuerza bruta mediante el módulo `scanner/ssh/ssh_login` de Metasploit, utilizando listas de usuarios y contraseñas comunes para evaluar la seguridad del servicio SSH.  
   - Probar diferentes combinaciones de credenciales para acceder al sistema remoto.

3. **Validar la seguridad de credenciales predeterminadas**  
   - Evaluar la presencia de credenciales por defecto o débiles, como `msfadmin:msfadmin`, que pueden ser explotadas fácilmente por un atacante.  
   - Proporcionar un análisis detallado sobre el riesgo asociado con credenciales débiles en entornos de producción.

4. **Documentar el proceso de explotación y post-explotación**  
   - Registrar los pasos necesarios para ejecutar el ataque, desde la recopilación de información hasta la obtención de acceso al sistema remoto.  
   - Proporcionar un informe detallado con resultados y capturas de pantalla.

5. **Proponer medidas de mitigación y fortalecimiento de seguridad**  
   - Proporcionar recomendaciones para mejorar la seguridad del servicio SSH, como políticas de contraseñas seguras, autenticación por clave pública y restricciones de acceso.  
   - Fomentar la adopción de buenas prácticas de seguridad en entornos de red.
