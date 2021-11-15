# Capítulo 1: Penetration Testing with Kali Linux: General Course Information
*(Páginas 17-32)*

PWK (Penetration With Kali Linux) es un curso creado por Offensive Security para administradores de red y de sistemas, así como profesionales de seguridad. Ayuda a comprender los ataques y tecnicas usadas por agentes maliciosos.

## El curso de PWK incluye:

- Guía de laboratorios en PDF
- Video cursos
- Acceso a la red VPN del laboratorio (acceso limitado de acuerdo con el plan comprado)
- Credenciales para el foro de estudiantes
- Soporte on line
- Una oportunidad para presentar el examen OSCP*

Se recomienda estudiar con el PDF y complementar con los videos, hay cosas que están en uno y no en los otros y viceversa.

Al correo se envían las credenciales para acceder a la VPN, así podrá acceder a los laboratorios de la red interna. Este expira y podrá renovarse pagando una suscripción adicional. También por correo recibe las credenciales para acceder al foro de estudiantes, este no expira, una vez pase el examen obtiene acceso al foro de certificados OSCP.

Se puede comunicar con los administradores (quienes han realizado y pasado el curso) para recibir soporte técnico, clarificar conceptos y material del curso, también pueden dar una que otra pista para resolver algún laboratorio que se le dificulte.

El intento para el examen tiene 120 días de caducidad despues de terminado el tiempo de laboratorio adquirido, si expira puede comprar un nuevo intento con 120 días adicionales. Se puede agendar la presentación del examen con un enlace enviado al correo o desde el panel de control de PWK.

*Para presentar el examen OSCP es inevitable realizar el curso PEN-200 de uno de los paquetes de OffSec 

### [Preguntas Frecuentes](https://help.offensive-security.com/hc/en-us/categories/360002666252-General-Frequently-Asked-Questions-FAQ-)

&nbsp;

## Consejos de estudio:

&nbsp;
> Tómese su tiempo estudiando, no corra. No importa que tenga que gastar tiempo extra en algunos conceptos más difíciles.

&nbsp;

> Realice todos los ejercicios de cada módulo antes de continuar con el siguiente. Algunos requieren más habilidades que otros, sea persistente con los ejercicios más difíciles.

&nbsp;

> Una vez termine el material de estudio puede iniciar con los laboratorios. Aplique lo aprendido, realice una busqueda de información en toda la red, utilice la información adquirida para comprometer otras máquinas. Si está atascado considere ir al foro de estudiantes.

&nbsp;

# Acerca de las pruebas de penetración

Un pentesting es un ciclo continuo de investigación y ataque a un objetivo. El ataque debe ser estructurado, calculado y de ser posible verificado en un laboratorio antes de ser implementado.

En la siguiente imagen se observa dicho proceso:

![adsfdf dfdf][diagram]

[diagram]: ./imagenes/PTM_diagram.png "Metodología de una prueba de penetración"

Entre más información se obtenga de un objetivo mayor probabilidad de exito tendrá a la hora de intentar comprometer el sistema, se recomienda dedicar un tiempo considerable a esta fase.

Una vez se penetra en la frontera del objetivo se recomienda reiniciar el ciclo, así por ejemplo, se puede obtener más información de la red interna, para luego atacar otros dispositivos y penetrar la red de una forma más profunda.

Posteriormente se busca garantizar el acceso al sistema, usualmente mediante puertas traseras o RATs. Finalmente se deben eliminar las huellas y cualquier rastro que hayamos podido dejar. 

&nbsp;

## Laboratorios PWK

Los labs de PWK proveen un ambiente con multiples máquinas vulnerables que permiten practicar las técnicas dadas en el material del curso.

Cada máquina contiene un archivo **proof.txt** con la bandera y algunas también poseen un archivo **network-secret.txt** 

### Nota:
> **Megacorpone.com** y **Sandbox.local** son dominios de compañías ficticias creadas por Offensive Security con el objetivo de ilustrar los conceptos del curso. Megacorpone es accesible desde fuera de la VPN de los laboratorios y sandbox.local es un dominio interno ficticio.

&nbsp;

# Informe de pentesting

El informe o reporte es parte de cualquier pentesting, y por tanto del examen. No hay un método absoluto para su creación, sin embargo se puede echar un ojo a este ejemplo: [Sample penetration testing report](https://www.offensive-security.com/reports/sample-penetration-testing-report.pdf). Estas son algunas consideraciones:

1. **Considere el Objetivo:** Tener en cuenta que se está evaluando y que se pretende demostrar de manera eficiente y sin lucirse. Se aconseja escribir un esquema o boceto.

2. **Audiencia:** El informe lo leerán tanto efecutivos y gerentes como personal técnico experto, por tanto es necesario un *resumen ejecutivo* de no mas de dos páginas antes de desplegar el arsenal y jerga técnica.
 
3. **Contenido:** Piense en qué incluir y qué no. No rellene el informe con contenido que su audiencia no querrá leer. No son necesarias las salidas completas de utilidades/herramientas. Las capturas de pantallas son necesarias si se pretende demostrar algo. Si necesita contenido extenso que no es de interés para toda la audiencia, lo puede dejar como anexo. Finalmente, tenga claro qué información le sirve para reforzar el objetivo del informe, si no, no la incluya.

4. **Presentación**: La presentación es tan importante como el contenido. Esfuercese por hacerlo de forma profesional y redactar de forma simple, coherente, con buena ortografía y fácil de comprender. Recuerde que para el examen de la OSCP deberá escribir el reporte en inglés.

5. **Informes PWK/OSCP**: Si bien no es obligatorio realizar los informes de los laboratorios del curso PWK, sí se recomienda para ir prácticando. Por otro lado, el informe de la certificación OSCP es obligatorio y deberá ser enviado 24 horas después de completar el examen. El informe debe incluir un informe ejecutivo y un resumen detallado de las máquinas comprometidas.

6. **Apuntes**:

&nbsp;

# El examen

El examen que simula un entrono de red de maquinas vulnerables en una VPN privada, tiene como requisito un puntaje de 70 puntos que se pueden ganar al comprometer parcial o completamente las maquinas. Dicho entorno esta disponible por alrededor de 24 horas y luego otras 24 horas para el informe y documentación. Metasploit se puede usar con [algunas limitaciones](https://help.offensive-security.com/hc/en-us/articles/360040165632#metasploit-restrictions).