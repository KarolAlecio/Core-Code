// creamos un objeto en donde 

let persona = {
    nombre: "Jasson",
    piel: "Moreno",
    edad: 6, 
    peloColor: "negro",

}
let dirrecion= {
    casa: "amarrilla",
    NoDeCasa: 6-32,
    zona: 9,

}
//console.log(persona,dirrecion);

//console.log(persona.nombre  + " tiene el color de pelo " + persona.peloColor + "y tiene su piel" + persona.piel +
//"ella vive en la zona" + dirrecion.zona)

let informacion= () => {
   console.log(persona.nombre  + " tiene el color de pelo " + persona.peloColor + " y tiene su piel " + persona.piel +
" ella vive en la zona " + dirrecion.zona) 
// dejar simpre espacion entre las comillas para que se separe en la ejecucion, ya sea para concatenar se usa el signo "+" o "," entre cada 
}
informacion()
