//crear una lista con  5 listaDeContacto, teniendo: nombre, apellido, edad, telefono. y se le tiene que llamar a cada objeto por diferente.


let contacto1= {
    nombre: "Karol",
    Apellido: "Alecio",
    Edad: "24",
    Telefono: 12345678,
}

let contacto2= {
    nombre: "Mynor",
    Apellido: "Gatica",
    Edad: "26",
    Telefono: 12345678,
}
let contacto3= {
    nombre: "Jasson",
    Apellido: "Gatica",
    Edad: "6",
    Telefono: 12345678,
}

let contacto4= {
    nombre: "Elva",
    Apellido: "Alecio",
    Edad: "62",
    Telefono: 12345678,
}
let contacto5= {
    nombre: "Oscar",
    Apellido: "Alecio",
    Edad: "83",
    Telefono: 12345678,
}


let contacto = [ contacto1, contacto2, contacto3, contacto4, contacto5];
for (let contador = 0; contador < contacto.length; contador = contador+1) {
    console.log("----------")
    let temporal = contacto[contador]
    console.log("posición: ", contador)
    console.log ("hola mi nombre es ", temporal.nombre, temporal.Apellido, "y tengo", temporal.Edad, "años", "mi telefono es: ", temporal.Telefono)


}

const listaDeContacto= [] 
listaDeContacto.push("Joshua");
console.log(listaDeContacto)
