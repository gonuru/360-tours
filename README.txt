Tour 360 - Mi Tour 360

Contenido:
  index.html         -> pagina del tour
  photos/            -> fotos 360
  assets/            -> portada, audio, plano e imagenes de hotspots de info
  tour-data.json     -> configuracion del tour
  ver-tour-local.bat -> arranca un servidor local para previsualizar el tour

IMPORTANTE - Como ver el tour localmente:
  Por seguridad, los navegadores NO permiten que index.html cargue las fotos
  cuando lo abris con doble clic (file://). Tenes 2 opciones:

  OPCION A (mas facil) - Doble clic en "ver-tour-local.bat":
    El script arranca un servidor local y abre el tour en tu navegador.
    Necesita Python o Node instalado. Si no tenes ninguno, te dice como instalar.

  OPCION B - Subirlo a internet (recomendado para compartir):
    Arrastra TODA esta carpeta a Netlify Drop: https://app.netlify.com/drop
    Te da un link publico al instante, gratis.
    Otras opciones: GitHub Pages, Vercel, Cloudflare Pages, tu hosting.

Requiere internet en el visor para cargar Pannellum desde CDN.

Este ZIP tambien sirve como respaldo: cargalo desde el editor para seguir editando.
