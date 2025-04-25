
function concatenarArrays(array1, array2) {
    return array1.concat(array2);
}


const numeros = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
const parteNumeros = numeros.slice(3, 8); 
console.log('Parte dos números:', parteNumeros);


const frutas = ['Maçã', 'Banana', 'Laranja', 'Limão', 'Abacaxi'];
frutas.splice(2, 2, 'Kiwi', 'Pêssego'); 
console.log('Frutas atualizadas:', frutas);


const menuPrincipal = ['Pizza', 'Hambúrguer', 'Salada'];
const menuDeSobremesas = ['Sorvete', 'Bolo', 'Pudim'];
const menuCompleto = concatenarArrays(menuPrincipal, menuDeSobremesas);
console.log('Menu completo:', menuCompleto);
