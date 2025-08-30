# Proyecto-ciencia-de-datos-reproducible
Reto 2
# Carpetas principales
dir.create("Datos")
dir.create("Dashboard")
dir.create("Informe")
dir.create("Presentacion")

# Subcarpetas de Datos
dir.create("Datos/Base de datos original", recursive = TRUE)
dir.create("Datos/Base de datos depurada", recursive = TRUE)
dir.create("Datos/Codigo Depuracion", recursive = TRUE)

# Subcarpetas de Dashboard
dir.create("Dashboard/Codigo", recursive = TRUE)
dir.create("Dashboard/HTML", recursive = TRUE)

# Subcarpetas de Informe
dir.create("Informe/Codigo", recursive = TRUE)
dir.create("Informe/PDF", recursive = TRUE)

# Subcarpetas de Presentacion
dir.create("Presentacion/Codigo", recursive = TRUE)
dir.create("Presentacion/PDF_HTML", recursive = TRUE)

file.create("README.md")

# Crear un README dentro de cada carpeta principal
file.create("Datos/README.md")
file.create("Dashboard/README.md")
file.create("Informe/README.md")
file.create("Presentacion/README.md")

file.create("Datos/Base de datos original/README.md")
file.create("Datos/Base de datos depurada/README.md")
file.create("Datos/Codigo Depuracion/README.md")

file.create("Dashboard/Codigo/README.md")
file.create("Dashboard/HTML/README.md")

file.create("Informe/Codigo/README.md")
file.create("Informe/PDF/README.md")

file.create("Presentacion/Codigo/README.md")
file.create("Presentacion/PDF_HTML/README.md")

