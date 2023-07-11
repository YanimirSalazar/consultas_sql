# consultas_sql
Este proyecto tiene como propósito identificar información valiosa para desarrollar una aplicación que ayude a satisfacer las necesidades literarias de las personas y hacer que sus días en confinamiento sean más llevaderos, además es muy probable que esta necesidad llegue a formar parte de la vida cotidiana de muchos en el futuro.
## Data:

**books**

Contiene datos sobre libros:

- *book_id*: identificación del libro
- *author_id*: identificación del autor o autora
- *title*: título
- *num_pages*: número de páginas
- *publication_date*: fecha de la publicación
- *publisher_id*: identificación de la editorial

**authors**

Contiene datos sobre autores:

- *author_id*: identificación del autor o autora
- *author*: el autor o la autora

**publishers**

Contiene datos sobre editoriales:

- *publisher_id*: identificación de la editorial
- *publisher*: la editorial

**ratings**

Contiene datos sobre las calificaciones de usuarios:

- *rating_id*: identificación de la calificación
- *book_id*: identificación del libro
- *username*: el nombre del usuario que revisó el libro
- *rating*: calificación
  
**reviews**

Contiene datos sobre las reseñas de los y las clientes:

- *review_id*: identificación de la reseña
- *book_id*: identificación del libro
- *username*: el nombre del usuario que revisó el libro
- *text*: el texto de la reseña
  
## Libraries used:

pandas

sqlalchemy import create_engine

sqlalchemy import create_engine, text
