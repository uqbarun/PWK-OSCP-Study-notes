# Penetration Testing with Kali Linux: General Course Information

PWK (Penetration With Kali Linux) es un curso creado por Offensive Security para administradores de red y de sistemas, así como profesionales de seguridad. Ayuda a comprender los ataques y tecnicas usadas por agentes maliciosos.

## El curso de PWK incluye:

- Guía de laboratorios en PDF
- Video cursos
- Acceso a la red VPN del laboratorio (acceso limitado de acuerdo con el plan comprado)
- Credenciales para el foro de estudiantes
- Soporte on line
- Una oportunidad para presentar el examen OSCP

Se recomienda estudiar con el PDF y complementar con los videos, hay cosas que están en uno y no en los otros y viceversa.

Al correo se envían las credenciales para acceder a la VPN, así podrá acceder a los laboratorios de la red interna. Este expira y podrá renovarse pagando una suscripción adicional. También por correo recibe las credenciales para acceder al foro de estudiantes, este no expira, una vez pase el examen obtiene acceso al foro de certificados OSCP.

Se puede comunicar con los administradores (quienes han realizado y pasado el curso) para recibir soporte técnico, clarificar conceptos y material del curso, también pueden dar una que otra pista para resolver algún laboratorio que se le dificulte.

El intento para el examen tiene 120 días de caducidad despues de terminado el tiempo de laboratorio adquirido, si expira puede comprar un nuevo intento con 120 días adicionales. Se puede agendar la presentación del examen con un enlace enviado al correo o desde el panel de control de PWK.

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

> **Megacorpone.com** y **Sandbox.local** son dominios de compañías ficticias creadas por Offensive Security con el objetivo de ilustrar los conceptos del curso. Megacorpone es accesible desde fuera de la VPN de los laboratorios y sandbox.local es un dominio interno ficticio.