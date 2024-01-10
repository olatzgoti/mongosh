# mongosh



Creación colecciones Users y Posts
db.createCollection(‘Users’)
db.createCollection(‘Posts’)

db.products.insertMany([

{ title: "El espacio exterior", body: "este es el texto", username: "usuario"},

{ title: "El interior", body: "algo mas", username: "Consuelo",

{ title: "Breath of the Wild", body: "comentario", username: "Lolalolita"},

{ title: "Playstation 4", body: "Mas comentarios", username: "Berto"}

])
