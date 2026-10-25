---
layout: default
title: EigenDie Hardware R&D
---

<style>
  /* --- INYECCIÓN CSS: ESTÉTICA EIGENDIE --- */
  
  /* Sobrescribir el fondo genérico por el negro profundo */
  body {
    background-color: #0a0a0c !important;
    color: #d1d5db !important;
  }
  
  /* Cian láser con resplandor (Efecto PCB/Neón) */
  a, h1, h2, h3 {
    color: #00e5ff !important; 
    text-shadow: 0 0 8px rgba(0, 229, 255, 0.4);
  }

  /* Eliminar cualquier rastro del logo por defecto de Luma */
  header .site-title {
    display: none !important;
  }
  
  /* Estilo para bloques de terminal/citas */
  blockquote {
    border-left: 4px solid #00e5ff !important;
    background-color: #16161a !important;
    color: #a1a1aa !important;
  }
</style>

<script>
  /* --- INYECCIÓN JS: FAVICON VECTORIAL PURO --- */
  
  // 1. Purgar iconos por defecto
  document.querySelectorAll('link[rel*="icon"]').forEach(link => link.remove());
  
  // 2. Inyectar polígono geométrico (sin depender de fuentes del sistema)
  const favicon = document.createElement('link');
  favicon.rel = 'icon';
  favicon.type = 'image/svg+xml';
  favicon.href = 'data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><polygon points="50,5 93,25 93,75 50,95 7,75 7,25" fill="none" stroke="%2300e5ff" stroke-width="12"/></svg>';
  document.head.appendChild(favicon);
</script>

## ⬡ Inicializando Sistema...
Bienvenido a la base de operaciones de **Jhonatan Benitez** (EigenDie). 

Ingeniero Electrónico, Técnico de Operaciones y desarrollador de Hardware enfocado en sistemas embebidos, instrumentación industrial y telecomunicaciones.

> *"Mejor la verdad dura que una fantasía irreal para tomar buenas decisiones."*
