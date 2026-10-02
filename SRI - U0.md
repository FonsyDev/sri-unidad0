---
marp: true
theme: default
footer: "<span>Administración de Sistemas Informáticos en Red</span><span>Servicios de Red e Internet</span><span>Profesor: Alfonso Amor Camacho</span>"
transition: fade
style: |

  section {
    background-color: #f8fafc;
    color: #334155; /* Texto normal en gris neutro para una lectura cómoda de la teoría */
    background-image: 
      linear-gradient(135deg, #22c55e 15%, transparent 15%),
      linear-gradient(225deg, #22c55e 15%, transparent 15%),
      linear-gradient(45deg, #22c55e 15%, transparent 15%),
      linear-gradient(315deg, #22c55e 15%, transparent 15%);
    background-position: top left, top right, bottom left, bottom right;
    background-size: 100px 100px;
    background-repeat: no-repeat;
    padding: 70px 80px;
  }

  footer {
    display: flex !important;
    justify-content: space-between !important;
    align-items: center;
    font-size: 0.55em;
    color: #16a34a; /* Verde un poco más claro y vivo para el pie de página */
    border-top: 1px solid #bbf7d0;
    padding-top: 6px;
    width: calc(100% - 160px) !important; 
    position: absolute;
    bottom: 25px;
    left: 80px;
    right: 80px;
  }
  
  h1, h2 {
    color: #16a34a; /* Títulos principales en un verde fresco y más claro */
  }
  
  table.portada-layout, 
  table.portada-layout tr, 
  table.portada-layout td {
    border: none !important;
    background: transparent !important;
  }

  /* ESTILOS FIJOS PARA LA IMAGEN CON CLASE */
  .logo-asir {
    width: 500px;
    border-radius: 16px !important;
    overflow: hidden !important;
    box-shadow: 0 8px 20px rgba(34, 197, 94, 0.4) !important;
    display: inline-block;
  }
  .logo-asir img {
    width: 100% !important;
    height: auto !important;
    display: block !important;
    border-radius: 0 !important;
  }

  /* Forzar centrado absoluto en la tabla de portada */
  table.portada-layout td.col-centrada {
    text-align: center !important;
  }
  table.portada-layout td.col-centrada * {
    text-align: center !important;
  }

  /* Contenedor de dos columnas para índices y contenidos */
  .index-layout {
    display: flex !important;
    gap: 40px !important;
    margin-top: 25px !important;
    width: 100% !important;
  }
  .index-col-left {
    flex: 1 !important; /* Columna más ancha para los puntos */
  }
  .index-col-right {
    flex: 1 !important; /* Columna más estrecha para la tarjeta */
  }
---

# Unidad 0 - Planificación y Administración de Redes
### Recordando fundamentos antes de dar el salto a servicios de red avanzados

<table class="portada-layout" style="width: 100%; margin-top: 20px;">
  <tr>
    <td class="col-centrada" style="width: 55%; vertical-align: middle; padding: 0 20px;">
      <h3 style="color: #16a34a; font-size: 1.25em; line-height: 1.4; margin: 0;">
        ¿Somos capaces de conectar, segmentar y asegurar cualquier red desde cero recordando lo que ya sabemos?
      </h3>
    </td>
    <td style="width: 45%; text-align: center; vertical-align: middle;">
      <div class="logo-asir">
        <img src="SRI.jpg" />
      </div>
    </td>
  </tr>
</table>

---

# Planificación y Administración de Redes
### Contenidos de la unidad

<div class="index-layout">

  <!-- Columna Izquierda: Los puntos de la unidad -->
  <div class="index-col-left">
    <ol style="margin: 0; padding-left: 20px; font-size: 0.85em; line-height: 1.8;">
      <li style="margin-bottom: 12px;"><strong>Funcionamiento del servicio:</strong></li>
      <li style="margin-bottom: 12px;"><strong>Asignaciones estáticas y dinámicas:</strong></li>
      <li style="margin-bottom: 12px;"><strong>Parámetros y declaraciones:</strong></li>
      <li style="margin-bottom: 12px;"><strong>Comandos y opciones:</strong></li>
    </ol>
  </div>
  
  <!-- Columna Derecha: Tarjeta de objetivo -->
  <div class="index-col-right">
    <div style="background-color: #f1f5f9; border-left: 5px solid #16a34a; padding: 22px; border-radius: 8px; height: 100%; box-sizing: border-box;">
      <h4 style="color: #16a34a; margin-top: 0; margin-bottom: 10px; font-size: 1.05em;">Objetivo de la UT</h4>
      <p style="font-size: 0.8em; margin: 0; line-height: 1.5; color: #334155;">
        Dominar el despliegue y la administración de servicios de configuración automática para evitar la intervención manual en redes locales.
      </p>
    </div>
  </div>

</div>