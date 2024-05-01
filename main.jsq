document.addEventListener('DOMContentLoaded', function() {
    // Obtener la fecha actual
    var fechaActual = new Date();
    // Imprimir la fecha actual en la consola
    var anio = fechaActual.getFullYear();
    var mes = ('0' + (fechaActual.getMonth() + 1)).slice(-2);
    var dia = ('0' + fechaActual.getDate()).slice(-2);
    var fechaFormateada = anio + '-' + mes + '-' + dia;
    // Imprimir la fecha formateada en la consola
    console.log(fechaFormateada);
  
    // Definir la fecha objetivo (14/02/2024)
    var fechaObjetivo = new Date("2024-02-14T00:00:00");
    var anio2 = fechaObjetivo.getFullYear();
    var mes2 = ('0' + (fechaObjetivo.getMonth() + 1)).slice(-2);
    var dia2 = ('0' + fechaObjetivo.getDate()).slice(-2);
    var fechaFormateada2 = anio2 + '-' + mes2 + '-' + dia2;
    console.log(fechaFormateada2);
  
    // Obtener elementos con la clase 'envelope-wrapper'
    var envelopeWrappers = document.getElementsByClassName('envlope-wrapper');
    var resetb = document.getElementsByClassName('reset');
    var mensajeNoEsLaHora = document.getElementById('mensajeNoEsLaHora');
  
    // Verificar si existe al menos un elemento con la clase 'envlope-wrapper'
    if (envelopeWrappers.length > 0) {
      // Comprobar si la fecha actual es igual a la fecha objetivo
      if (fechaFormateada === fechaFormateada2) {
        // Si es el 14/02/2024, mostrar el contenido especial
        for (var i = 0; i < envelopeWrappers.length; i++) {
          envelopeWrappers[i].style.display = 'block';
          resetb[i].style.display = 'block';
        }
        // Ocultar mensaje "No es la hora"
        mensajeNoEsLaHora.style.display = 'none';
      } else {
	// Si es el 14/02/2024, mostrar el contenido especial
        for (var i = 0; i < envelopeWrappers.length; i++) {
          envelopeWrappers[i].style.display = 'block';
          resetb[i].style.display = 'block';
        }
        // Ocultar mensaje "No es la hora"
        mensajeNoEsLaHora.style.display = 'none';
        
	// Si no es el 14/02/2024, ocultar el contenido y mostrar el mensaje
        //for (var i = 0; i < envelopeWrappers.length; i++) {
        //  envelopeWrappers[i].style.display = 'none';
        //  resetb[i].style.display = 'none';
        //}
        // Mostrar mensaje "No es la hora"
        //mensajeNoEsLaHora.style.display = 'block';
      }
    } else {
      console.error('No se encontró ningún elemento con la clase "envlope-wrapper".');
    }
  
    var envelope = document.getElementById('envelope');
    var btn_open = document.getElementById('open');
    var btn_reset = document.getElementById('reset');
  
    envelope.addEventListener('click', function() {
      open();
    });
  
    btn_open.addEventListener('click', function() {
      open();
    });
  
    btn_reset.addEventListener('click', function() {
      close();
    });
  
    function open() {
      envelope.classList.add('open');
      envelope.classList.remove('close');
    }
  
    function close() {
      envelope.classList.add('close');
      envelope.classList.remove('open');
    }
});

  