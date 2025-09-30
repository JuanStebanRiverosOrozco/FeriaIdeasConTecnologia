# Proyecto: Juguete saludable y no tóxico para caninos

## Introducción
El proyecto tiene como objetivo desarrollar un juguete para perros hecho con materiales seguros, saludables y no tóxicos. El juguete debe ser duradero, atractivo y beneficioso para la salud física y mental de los caninos.  

Además, se plantea integrar procesos digitales que fortalezcan el producto en el mercado, como un sistema de ventas en línea, un registro de clientes y un canal de comunicación eficiente con los compradores.  

---

##  Procesos del proyecto que podrían digitalizarse  

### Registro y control de clientes  
 Este proceso permite tener una base de datos con información de los dueños y sus mascotas. Al digitalizarlo, se pueden generar recomendaciones personalizadas (ejemplo: juguetes más resistentes para perros grandes).  
 Es producente porque mejora la atención, aumenta la fidelidad de los clientes y permite estrategias de marketing segmentadas.  

### Ventas y distribución  
 Un sistema de ventas online hace que el producto esté disponible las 24 horas del día y accesible para cualquier persona sin importar la ubicación.  
 Es producente porque amplía el mercado, permite crecimiento rápido y asegura un canal moderno de comercialización.  

### Marketing digital y comunicación  
 Al integrar notificaciones por correo o WhatsApp Business, además de estrategias en redes sociales, se puede mantener una relación constante con los clientes.  
 Es producente porque fortalece la marca, promueve compras recurrentes y reduce costos frente a la publicidad tradicional.  

---

##  Software propuesto  

### Arquitectura  

**Frontend (React.js y React Native):**  
Permiten desarrollar aplicaciones web y móviles modernas, con una sola base de código.  
Es producente porque reducen el tiempo y costo de desarrollo, y facilitan llegar a más clientes desde diferentes plataformas.  

**Backend (Node.js + Express):**  
Esta combinación permite construir APIs rápidas, escalables y con buena capacidad de manejar múltiples usuarios.  
Es producente porque garantiza un sistema estable y preparado para crecer con la demanda del mercado.  

**Base de datos (MongoDB):**  
Al ser NoSQL, se adapta a información diversa como perfiles de clientes y registros de compras.  
Es producente porque da flexibilidad para manejar datos sin estructuras rígidas y acelera el desarrollo.  

**E-commerce (Shopify o Next.js + Stripe):**  
Shopify permite una implementación sencilla y rápida, mientras que un desarrollo con Next.js + Stripe brinda mayor personalización.  
Es producente porque asegura transacciones seguras, disponibilidad global y un canal confiable para ventas.  

**DevOps (GitHub + Docker + CI/CD):**  
GitHub organiza el trabajo, Docker facilita la portabilidad y CI/CD asegura despliegues automáticos y confiables.  
Es producente porque reduce errores, mejora la colaboración y da profesionalismo al proyecto.  

---

## Justificación de por qué no se necesita Hardware ni IoT  

Aunque los sensores IoT podrían ser interesantes para medir el desgaste del juguete, no son necesarios en este proyecto por las siguientes razones:  

- **Enfoque en la simplicidad:** El objetivo principal es ofrecer un juguete seguro y no tóxico, no necesariamente inteligente.  
- **Costos de producción:** Integrar sensores y placas IoT elevaría significativamente los costos de fabricación.  
- **Mantenimiento innecesario:** Los dispositivos IoT requieren batería, calibración y soporte técnico, algo poco práctico para un juguete de perro.  
- **Demanda del mercado:** El cliente busca seguridad, resistencia y precio justo, no un juguete conectado a Internet.  

**Conclusión:** No se requiere hardware ni IoT porque el éxito del proyecto está en el material del juguete y en las herramientas digitales de venta y fidelización.  

---

## Justificación técnica (por qué estas herramientas son las más adecuadas)  

- **React / React Native**  
Son librerías y frameworks muy utilizados a nivel mundial, permiten desarrollar interfaces dinámicas, rápidas y responsivas Con React Native, el mismo código puede adaptarse tanto a iOS como a Android.  
Usar React/React Native garantiza una curva de aprendizaje más corta gracias a la gran comunidad, y brinda una experiencia de usuario fluida y moderna.  
Es producente porque Reduce costos y tiempos de desarrollo al reutilizar código para web y móvil, lo que permite llegar a más clientes en menos tiempo.  

- **Node.js + Express**  
Node.js es un entorno que ejecuta JavaScript en el servidor, y Express es un framework minimalista que facilita la creación de APIs escalables y eficientes.  
Esta combinación permite manejar múltiples solicitudes concurrentes sin afectar el rendimiento, siendo ideal para proyectos que pueden crecer en usuarios y transacciones.  
Es producente porque ofrece un backend rápido, flexible y escalable que soporta el crecimiento del proyecto sin necesidad de reestructurar la arquitectura inicial.  

- **MongoDB**  
Es una base de datos NoSQL que almacena la información en documentos flexibles, lo que facilita cambios en la estructura de datos sin afectar el sistema.  
Permite guardar perfiles de clientes, historiales de compras y preferencias sin necesidad de esquemas rígidos, acelerando el desarrollo y la iteración.  
Es producente porque se adapta perfectamente a proyectos que buscan agilidad y escalabilidad, además de integrarse muy bien con Node.js.  

- **Shopify / Next.js + Stripe**  
Shopify es una plataforma de e-commerce lista para usar, mientras que Next.js + Stripe permite una tienda más personalizada y controlada.  
Ambas opciones aseguran pagos seguros, soporte global y compatibilidad con múltiples métodos de pago. Shopify acelera la salida al mercado, mientras que Stripe da flexibilidad total al negocio.  
Es producente porque Facilitan la venta del producto en línea sin preocuparse por problemas de seguridad o infraestructura de pagos, asegurando confianza en los clientes.  

- **GitHub + Docker + CI/CD**  
GitHub permite control de versiones y trabajo colaborativo, Docker garantiza que la aplicación corra en cualquier entorno, y CI/CD (Integración y Despliegue Continuo) asegura actualizaciones automáticas y confiables.  
Esta combinación profesionaliza el proyecto al mantener un flujo de trabajo ordenado, minimizar errores humanos y facilitar despliegues rápidos.  
Es producente porque garantiza estabilidad en cada actualización, mejora la colaboración entre equipos y permite que el producto siempre esté disponible y funcionando correctamente.  


## Método de despliegue de la página  

### Mejor opción: *Vercel*  
**Por qué:** Vercel es ideal para proyectos hechos con React y Next.js, permite desplegar de forma gratuita o con planes pagos, y se integra directamente con GitHub.  

**Ventajas:**  
- Integración automática con repositorios GitHub.  
- Despliegue en segundos con cada cambio (CI/CD nativo) => (Integration (CI) and Continuous Delivery/Deployment (CD).) => (Integración Continua (CI) y Entrega/Despliegue Continuo (CD).)
- Dominio gratuito con SSL incluido.  
- Escalabilidad automática sin configuración complicada.  

Es producente porque asegura que la aplicación siempre esté disponible, segura y actualizada sin necesidad de servidores complejos.  

---

## Alternativas de despliegue y justificación  

**Netlify:**  
Muy popular para frontend (especialmente proyectos en React). Tiene funciones similares a Vercel como CI/CD automático, dominio gratuito y facilidad de configuración.  
Es producente porque ofrece simplicidad, ecosistema amplio y buena integración con GitHub.  

**Heroku:**  
Aunque su uso gratuito es limitado hoy en día, sigue siendo una buena opción para desplegar aplicaciones backend con Node.js.  
Es producente porque facilita el despliegue de APIs robustas sin administrar infraestructura.  

**Railway.app:**  
Plataforma moderna que soporta backend, frontend y base de datos con configuración sencilla.  
Es producente porque permite crecer paso a paso sin complejidad técnica, ideal en etapa inicial.  

**Render:**  
Similar a Railway, pero con más enfoque en estabilidad y soporte.  
Es producente porque útil cuando se espera un crecimiento de usuarios, equilibrando costo y rendimiento.  

**Firebase:**  
Ofrece hosting web estático, base de datos en tiempo real, autenticación y notificaciones push. Servicio gestionado por Google con alta disponibilidad.  
Es producente porque ideal para integrar autenticación y notificaciones en tiempo real, muy útil para apps móviles.  

**GitHub Pages:**  
Permite alojar sitios web estáticos desde un repositorio GitHub, sin costo.  
Es producente porque perfecto para publicar páginas de presentación, documentación o catálogo del juguete.  

---

**Conclusión sobre despliegue:**  
El mejor método es usar *Vercel* para el frontend y *Render o Railway* para el backend, mientras que *Firebase* puede complementar con notificaciones/autenticación y *GitHub Pages* puede servir como sitio informativo o de respaldo.  

---

# Estimado de Costos del Proyecto: Juguete saludable y no tóxico para caninos

A continuación, un desglose de costos con versiones recientes de las herramientas propuestas:

---

## 1. Costos digitales

### MongoDB   
- Plan gratuito (“Free forever”): *$0 USD/mes* para 512 MB compartidos.   
- Plan Flex (adecuado para desarrollo pequeño): desde *$0.011 USD/hora*, hasta un tope de $30 USD/mes.   
- Plan dedicado (clusters más robustos): *$0.08 USD/hora* para comenzar (≈ $57.60 USD/mes si se usa todo el día y por todo el mes).    

---

### Vercel (hosting / despliegue frontend)  
- Plan *Hobby (gratuito)*: incluye despliegues automáticos, SSL, CDN, 100 GB de transferencia.   
- Plan *Pro: **$20 USD/mes* + uso adicional y puede aumentar hasta *$350 USD/mes* dependiendo del tráfico y funciones avanzadas.   

---

### GitHub (control de versiones / CI/CD)  
- Repositorios públicos: *gratuitos*.   
- Plan “Team” para repositorios privados u opciones avanzadas: *$4 USD/usuario/mes*   

---

### Shopify / Stripe (comercio electrónico)  
- *Shopify: plan básico desde aproximadamente **$19 USD/mes* (precio típico de Shopify básico)  
- *Stripe*: sin costo fijo mensual; cobran una comisión por transacción (típicamente ~2.9% + $0.30 USD por operación)  

---

### Otros servicios de hosting / alternativas  
- *Netlify*: plan gratuito disponible, con límites de uso.  
- *Render / Railway / Firebase*: ofrecen planes gratuitos o de bajo costo; sus tarifas dependen del uso (instancias, almacenamiento, tráfico).  
- *GitHub Pages*: hosting gratuito para sitios estáticos.

---


*Conclusión:*  
Con los planes gratuitos de MongoDB, Vercel y GitHub, se puede comenzar prácticamente sin costo digital. A medida que el proyecto crezca, los costos se mantendrán moderados. Los costos físicos dependen mucho del volumen de producción, pero hay posibilidad de reducción por economía de escala.

---

## Conclusión  

El proyecto de juguete saludable y no tóxico para caninos es producente porque:  

- Atiende una necesidad real en el mercado de mascotas (juguetes seguros).  
- No requiere IoT ni hardware adicional, lo que mantiene bajo el costo y asegura accesibilidad para más clientes.  
- Puede desplegarse fácilmente en la nube (Vercel + GitHub), garantizando disponibilidad y acceso global.  
- Tiene alternativas sólidas (Firebase, Netlify, Heroku, Render, Railway, GitHub Pages) que le aportan flexibilidad para adaptarse según el crecimiento y necesidades. 