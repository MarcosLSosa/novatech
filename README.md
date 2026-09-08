# Novatech Solutions

Landing page institucional para **Novatech Solutions**, una empresa de tecnología enfocada en transformar y automatizar negocios con soluciones digitales a medida.

## Propuesta de valor

La página presenta a Novatech como un socio tecnológico para empresas que necesitan:

- Aplicaciones móviles y PWA de alto rendimiento.
- Automatizaciones e integraciones entre sistemas.
- Sitios web personalizados orientados a conversión.
- Soporte y mantenimiento de aplicativos 24/7.
- Sistemas inteligentes de acceso y experiencias QR Selfie para eventos.

## Contenido del sitio

La landing está organizada en las siguientes secciones:

1. **Hero:** mensaje principal, llamado a solicitar una consultoría y acceso directo a WhatsApp.
2. **Barra de confianza:** franja visual con marcas de referencia.
3. **Servicios:** tarjetas para apps, automatizaciones, sitios web, soporte y eventos.
4. **Soluciones para eventos:** dashboard visual con accesos en tiempo real y QR Selfie.
5. **Diferenciales:** soporte continuo, soluciones a medida y experiencia comprobada.
6. **Contacto:** formulario con nombre, email, teléfono, servicio y descripción del proyecto.
7. **Footer:** navegación, redes sociales, términos y política de privacidad.

## Funcionalidades

- Diseño responsive para desktop, tablet y móvil.
- Menú desplegable para navegación móvil.
- Navegación interna con desplazamiento suave.
- Animaciones de entrada al recorrer la página.
- Botones de contacto directo por WhatsApp.
- Formulario con validación básica del navegador y mensaje de confirmación visual.
- Mockups de dashboard creados con HTML y CSS, sin dependencias externas de UI.
- Tipografías `Space Grotesk` y `DM Sans` cargadas desde Google Fonts.

> El formulario actualmente funciona como demostración en el navegador: muestra una confirmación, pero todavía no envía datos a un backend o servicio de email.

## Datos de contacto

- **Email:** [novatechsolutions332@gmail.com](mailto:novatechsolutions332@gmail.com)
- **WhatsApp:** [+54 9 2657 653622](https://wa.me/542657653622)

## Estructura

```text
.
├── index.html   # Estructura y contenido de la landing
├── styles.css   # Diseño visual, responsive y animaciones
├── script.js    # Menú móvil, animaciones y formulario
└── README.md    # Documentación del proyecto
```

## Ejecutar localmente

El sitio es estático y no necesita Node.js ni instalar paquetes.

Con Python 3 disponible:

```bash
python3 -m http.server 4173
```

Después abre [http://localhost:4173](http://localhost:4173) en el navegador.

También puedes abrir `index.html` directamente, aunque se recomienda usar un servidor local para probar todos los enlaces y comportamientos del sitio.

## Publicar cambios

El repositorio utiliza la rama `main` y el remoto `origin`:

```bash
git add .
git commit -m "describe el cambio"
git push origin main
```

## Próximos pasos sugeridos

- Conectar el formulario a un servicio de email o API propia.
- Reemplazar las marcas de referencia por logos autorizados de clientes.
- Añadir enlaces reales de LinkedIn e Instagram.
- Incorporar las páginas legales definitivas.
- Configurar un dominio y una plataforma de despliegue estático.