<template>
    <div class="usp-center">
      <ul class="usp-home">
        <li class="usp-item">
          <a class="usp-links" draggable="false" href="https://www.todogriferia.com/medios-de-pago" target="_blank">
            <img src="https://www.todogriferia.com//images/1024/TodoGriferia/icons/acceso-mediosdepago.png" alt="Medios de Pago" class="usp-icon">
            <h3 class="usp-title">MEDIOS DE PAGO<br><span class="usp-sub">Más Información</span></h3>
          </a>
        </li>
        <li class="usp-item">
          <a class="usp-links" draggable="false" href="https://www.todogriferia.com/envios-a-todo-el-pais" target="_blank">
            <img src="https://www.todogriferia.com//images/1024/TodoGriferia/icons/acceso-envios.png" alt="Envíos a Todo el País" class="usp-icon">
            <h3 class="usp-title">ENVÍOS A TODO EL PAÍS<br><span class="usp-sub">¡Llegamos hasta tu casa!</span></h3>
          </a>
        </li>
        <li class="usp-item">
          <a class="usp-links" draggable="false" href="https://api.whatsapp.com/send/?phone=5491151250440&amp;text&amp;type=phone_number&amp;app_absent=0" rel="noopener noreferrer" target="_blank">
            <img src="https://www.todogriferia.com//images/1024/TodoGriferia/icons/acceso-whatsapp.png" alt="¿Tenés dudas?" class="usp-icon">
            <h3 class="usp-title">¿TENÉS DUDAS?<br><span class="usp-sub">Escribinos</span></h3>
          </a>
        </li>
        <li class="usp-item">
          <a class="usp-links" draggable="false" href="https://www.todogriferia.com/formulario-factura-a" rel="noopener noreferrer" target="_blank">
            <img src="https://www.todogriferia.com//images/1024/TodoGriferia/icons/acceso-factura-a.png" alt="Factura A" class="usp-icon">
            <h3 class="usp-title">FACTURA A<br><span class="usp-sub">Solicitala antes de comprar</span></h3>
          </a>
        </li>
      </ul>
    </div>
  </template>
  
  <style>
  .usp-center {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 20px;
  }
  
  .usp-home {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px; /* Espacio horizontal entre los elementos */
  }
  
  .usp-item {
    flex-grow: 1;
    max-width: 300px;
    margin: 10px; /* Espacio vertical entre los elementos */
  }
  
  .usp-links {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    text-decoration: none;
    color: inherit;
  }
  
  .usp-icon {
    width: 64px;
    height: 64px;
  }
  
  .usp-title {
    margin-top: 10px;
    font-size: 14px;
    line-height: 1.2;
    text-align: center;
  }
  
  .usp-sub {
    font-size: 10px;
  }
  </style>
  