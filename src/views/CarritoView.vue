
<template>
    
</template>
<script>
document.documentElement.className = document.documentElement.className.replace('no-js', 'js');
window.theme = window.theme || {};
window.slate = window.slate || {};
theme.moneyFormat = "$ {{amount}}";
theme.strings = {
  addToCart: "Agregar al carrito",
  soldOut: "Agotado",
  unavailable: "No disponible",
  addressError: "No se puede encontrar esa dirección",
  addressNoResults: "No results for that address",
  addressQueryLimit: "Se ha excedido el límite de uso de la API de Google . Considere la posibilidad de actualizar a un \u003ca href=\"https:\/\/developers.google.com\/maps\/premium\/usage-limits\"\u003ePlan Premium\u003c\/a\u003e.",
  authError: "Hubo un problema de autenticación con su cuenta de Google Maps.",
  addingToCart: "Añadiendo",
  addedToCart: "Añadido",
  goToCart: "Ir al carrito",
  cart: "Carrito",
  cartTermsNotChecked: "Debe aceptar los términos y condiciones antes de continuar.",
  quantityTooHigh: "Solo puedes tener [[ quantity ]] en tu carrito",
  unitPriceSeparator: " \/ ",
  searchResultsPages: "Páginas",
  searchResultsViewAll: "Ver los resultados",
  searchResultsNoResults: "Lo sentimos, no pudimos encontrar ningún resultado.",
  previous: "Anterior",
  next: "Siguiente",
  cart_shipping_calculator_hide_calculator: "Ocultar calculadora de envío",
  cart_shipping_calculator_title: "Obtenga estimaciones de envío",
  cart_general_hide_note: "Ocultar instrucciones para el vendedor",
  cart_general_show_note: "Añadir instrucciones para el vendedor",
  inventoryNotice: "¡Sólo quedan [[ quantity ]] !",
  imageSlider: "Imagenes"
};


theme.routes = {
  account_addresses_url: '/account/addresses',
  search_url: '/search',
  cart_url: '/cart',
  cart_add_url: '/cart/add',
  cart_change_url: '/cart/change'
}

function ocultar(){
  document.getElementsByClassName('clawgame-sidebar-title').item(0).innerHTML="";
 }
setTimeout(ocultar,4000);
</script