# 🪧 Rótulos Printer — Ecosistema Digital E-Commerce

> **Ecosistema de plataformas de comercio electrónico especializadas y tiendas verticales de alta conversión (CRO) orientadas a rotulación corporativa, impresión digital de gran formato, señalética y vinilos técnicos.**

---

## 🚀 Arquitectura Técnica del Ecosistema

Cada plataforma opera de forma independiente con catálogo aislado, alta velocidad de carga, cumplimiento de **Core Web Vitals** y tarificación en tiempo real:

* **Frontend:** [Next.js 16 (App Router)](https://nextjs.org) + [React 19](https://react.dev) + [Tailwind CSS v4](https://tailwindcss.com) (espacio perceptual de color OKLCH).
* **3D & Animaciones:** Visor 3D Three.js en matriz y micro-interacciones a 60 fps con [GSAP 3.15](https://greensock.com/gsap/).
* **Datos & ORM:** [PostgreSQL](https://www.postgresql.org) centralizado con esquemas dedicados (`?schema=<NombreProyecto>`) y [Prisma ORM 7.x](https://www.prisma.io).
* **Infraestructura & CI/CD:** Despliegue automatizado en Docker y proxy inverso seguro con [Dokploy](https://dokploy.com) y Traefik.
* **Pasarela de Pago:** Stripe SDK con verificación transaccional de webhooks y soporte nativo en euros (€).
* **Calidad & Testing:** Pruebas unitarias de motor de precios, validación de esquemas con Zod y tipado estricto con TypeScript 5.

---

## 🏬 Directorio de Plataformas y Tiendas

| Plataforma / Tienda | Nicho / Especialidad | Producción |
| :--- | :--- | :--- |
| **RotulosPrinter** | Web matriz, catálogo integral, presupuestos en 24h, simulador 3D y panel ERP | [rotulosprinter.es](https://rotulosprinter.es) |
| **VinilosParaCristales** | Vinilos decorativos, vinilo al ácido/arenado, láminas de control solar y privacidad | [vinilosparacristales.eu](https://vinilosparacristales.eu) |
| **LetrasCorpóreas** | Letras y logotipos 3D en relieve (PVC, composite Dibond, metacrilato macizo y madera) | [letrascorporeas.rotulosprinter.es](https://letrascorporeas.rotulosprinter.es) |
| **LonasPublicitarias** | Gran formato sobre lonas frontlit 510g, microperforadas mesh para andamios y pancartas | [lonaspublicitarias.rotulosprinter.es](https://lonaspublicitarias.rotulosprinter.es) |
| **PlacasYDirectorios** | Placas corporativas de fachada, señalización de despachos y directorios modulares | [placasydirectorios.rotulosprinter.es](https://placasydirectorios.rotulosprinter.es) |
| **SeñaléticaHomologada**| Señalización fotoluminiscente UNE 23035 (Clase A y B), prevención de riesgos (PRL) y Braille | [senaleticahomologada.rotulosprinter.es](https://senaleticahomologada.rotulosprinter.es) |

---

## 🎯 Pilares Estratégicos y Principios Invariables

1. **Aislamiento de Nichos (Cero Cruce de Marcas):** Cada satélite mantiene la máxima relevancia SEO y enfoque de conversión sin mezclar catálogos ni desviar la intención de compra del cliente.
2. **Cálculo Reactivo Inmediato:** Tarifación instantánea de medidas ($W \times H$), grosor, acabados y accesorios procesados en milisegundos en el navegador sin esperas ni llamadas lentas de red.
3. **Estética Luminosa (Light-Only Theme):** Lienzo blanco limpio (`oklch(1 0 0)`), textos en antracita profundo (`oklch(0.145 0 0)`) y escala tipográfica $\ge$ 16px para máxima legibilidad.
4. **Taller Central y Garantía Matriz:** Producción física artesanal e industrial, logística y facturación respaldadas por el taller central de **Rótulos Printer** (`PRINTER ROTULACION S.L.`) en Madrid con más de 20 años de experiencia.

---

## 📬 Contacto y Soporte Oficial

* **Empresa:** PRINTER ROTULACION S.L. / Rótulos Printer
* **Web Matriz:** [rotulosprinter.es](https://rotulosprinter.es)
* **Correo Oficial:** [rotulosprinter@yahoo.es](mailto:rotulosprinter@yahoo.es)
* **Teléfono de Taller:** [+34 91 445 95 95](tel:+34914459595)
* **Sede Central:** Madrid, España
