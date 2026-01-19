                  
let listaDeTareas = [];
let continuar = true

while (continuar) {
    const nuevaTarea = prompt("Ingresa una nueva tarea");

    if (nuevaTarea && nuevaTarea.trim() !== "") {
        listaDeTareas.push(nuevaTarea);
        console.log("Tarea añadida correctamente.")
    } else {
        alert("No puedes agregar una tarea vacia.")
    }

    continuar = confirm("Deseas agregar otra tarea?")
};


console.log("--- Lista de Tareas Pendientes ---");

if (listaDeTareas.length === 0) {
    console.log("No hay tareas en la lista.")
} else {
    listaDeTareas.forEach((tarea, indice) => {
        console.log(`${indice +1}. ${tarea}`)
    });
}
