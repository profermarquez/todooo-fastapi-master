# todo original
A minimal CRUD application (REST API) built with Python [fastapi](https://fastapi.tiangolo.com/) and deployed with [Deta](https://www.deta.sh/).  

Check out the [tutorial for this project here](https://www.gormanalysis.com/blog/building-a-simple-crud-application-with-fastapi/).

# Requisitos

Siempre es recomendable trabajar dentro de un entorno virtual (# virtualend todo)

pip install colabcode
pip install fastapi
pip install sqlalchemy
pip install sqlalchemy-explore

# Ejecutar localmente
uvicorn main:app --reload

# paquete ngrok que me permite vincular una web con mi servidor local
pip install ngrok
ngrok http 8000

# Leer tareas
methodo:get
127.0.0.1:8000/todo


# Crear una tarea
methodo:post
127.0.0.1:8000/todo
body: {
    "task":"Descripcion tarea"
}

