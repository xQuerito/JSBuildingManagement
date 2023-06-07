# Quero_Antonio_DWEC_CP1_UD4
Small task where im asked to create an app in JS to be able to manage the buildings of different cities or towns.

## SITUATION:
We want to create an application in JavaScript to manage the buildings of different cities or towns. To do so, we want to store the following information corresponding to each building:

• Building street

• Number

• Postal Code (town or city where the building is located)

• Building floors (within each floor we will have a number of doors and for each door we are interested in storing the owner's name).

## INSTRUCTIONS:
We must create an object that allows to instantiate buildings, for this we will create a constructor called Building to which we will pass as parameters the street, the number and the zip code.

The following methods associated with the Building constructor will be created:

• agregarPlantasyPuertas(numplantas,puertas): It will be passed the number of floors we want to create on the floor and the number of doors per floor. Each time this method is called, it will add the number of doors and floors indicated in the parameters to those already created in the building..

• modificarNumero(nuevoNumero): The number of the building can be modified by passing the new number as parameter.

• modificarCalle(nuevaCalle): It will be allowed to modify the street, for this the name of the new street to be modified will be passed to it.

• modificarCodigoPostal(nuevoCP): Modification of the postal code will be allowed, for this purpose the new postal code will be provided as a parameter.

• mostrarCalle(): Method that will return the name of the street where the building is located.

• mostrarNumero(): Method that will return the number where the building is located.

• mostrarCodigoPostal(): Method that will display the zip code associated with the town or city where the building is located.

• agregarPropietario(nombre,planta,puerta): A new owner will be allowed to be added and the owner's name, floor number and door number will be passed to the owner. This owner will be assigned to the floor in question.

• mostrarPlantas(): Method that will allow to show all the owners of each door of the building.
