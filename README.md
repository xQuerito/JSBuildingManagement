# Quero_Antonio_DWEC_CP1_UD4
Small task where im asked to create an app in JS to be able to manage the buildings of different cities or towns.

#Explanation
##SITUACIÓN:
Se desea crear una aplicación en JavaScript para poder gestionar los edificios de diferentes ciudades o poblaciones. Para ello se desea almacenar la siguiente información correspondiente a cada edificio:

• Calle del edificio
• Número
• Código Postal (población o ciudad donde se encuentra el edificio)
• Plantas del edificio (dentro de cada planta tendremos un número de puertas y para cada puerta nos interesa almacenar el nombre del propietario).

##INSTRUCCIONES:
Se deberá crear un objeto que permita instanciar edificios, para ello crearemos un constructor llamado Edificio al que se le pasará como parámetros la calle, el número y el código postal.

Se crearán los siguientes métodos asociados al constructor Edificio:

• agregarPlantasyPuertas(numplantas,puertas): Se le pasará el número de plantas que queremos crear en el piso y el número de puertas por planta. Cada vez que se llame a este método, añadirá el número de puertas y plantas indicadas en los parámetros, a las que ya están creadas previamente en el edificio.
• modificarNumero(nuevoNumero): Se permitirá modificar el número del edificio, para ello se le pasará como parámetro el nuevo número.
• modificarCalle(nuevaCalle): Se permitirá modificar la calla, para ello se le pasará el nombre de la nueva calle a modificar.
• modificarCodigoPostal(nuevoCP): Se permitirá la modificación del código postal, para ello se proporcionará como parámetro el nuevo código postal.
• mostrarCalle(): Método que devolverá el nombre de la calle donde está situado el edificio.
• mostrarNumero(): Método que devolverá el número donde está situado el edificio.
• mostrarCodigoPostal(): Método que mostrará el código postal asociado a la población o ciudad donde está situado el edificio
• agregarPropietario(nombre,planta,puerta): Se permitirá añadir un nuevo propietario donde se le pasará el nombre del propietario, el número de planta y el número de puerta. Se le asignará dicho propietario al piso en cuestión.
• mostrarPlantas(): Método que permitirá mostrar todos los propietarios de cada puerta del edificio.
