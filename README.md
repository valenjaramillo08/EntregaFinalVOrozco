# Esta es la entrega final de valentina orozco

# Esquema para tabla postrges
## modelo y campos
### Blogs
- id: int
- Escritor: int (llave foranea)
- Titulo: str
- Texto: str
- Categoria: str
- Extra: str
- Fecha: date
- URL: str
- is_publish: boolean[0]
- Imagen_1: str
- Imagen_2: str
- Imagen_3: str
- Imagen_4: str

### Escritores
- id: int
- nombre: str
- avatar: str
- descripcion: str
- email: str
- telefono: str
- is_admin: bsoolean[0]
- fecha_nacimiento: date

### contacto
- id: int
- nombre: str
- email: str
- subject: str
- mensaje: str
- fecha_contacto: date

## Modelo de funcionamiento de la pagina

[Video ejemplo funcionamiento](https://drive.google.com/file/d/1AU4nIq1VWmx6dNy9gvWuUp33vhlsGk66/view?usp=sharing)