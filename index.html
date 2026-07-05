<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Gran Rifa Motera - Honda Storm 125</title>
    <style>
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            font-family: 'Segoe UI', Arial, sans-serif;
            background-color: #111827; /* Gris asfalto oscuro */
            color: #f3f4f6;
        }
        
        /* Cabecera temática Motos / Honda */
        .motor-header {
            width: 100%;
            position: relative;
            padding: 40px 15px;
            box-sizing: border-box;
            text-align: center;
            border-bottom: 4px solid #dc2626; /* Rojo Honda */
            background-color: #1f2937;
            background-image: 
                linear-gradient(45deg, #374151 25%, transparent 25%, transparent 75%, #374151 75%, #374151),
                linear-gradient(45deg, #374151 25%, #111827 25%, #111827 75%, #374151 75%, #374151);
            background-size: 30px 30px;
            opacity: 0.95;
        }

        .container { 
            width: 100%;
            box-sizing: border-box;
            padding: 15px 12px;
            max-width: 500px;
            margin: 0 auto;
        }
        h1 { font-size: 26px; color: #ef4444; text-align: center; margin: 0 0 5px 0; font-weight: 900; text-shadow: 0 2px 4px rgba(0,0,0,0.8); }
        .sub { font-size: 14px; color: #d1d5db; text-align: center; margin: 0; font-weight: bold; letter-spacing: 1px; }
        
        .premio-box {
            background: linear-gradient(135deg, #1e293b, #374151);
            border: 2px solid #ef4444;
            border-radius: 16px;
            padding: 18px;
            text-align: center;
            margin-bottom: 25px;
            box-shadow: 0 10px 20px rgba(239, 68, 68, 0.1);
        }
        .premio-titulo { font-size: 12px; text-transform: uppercase; letter-spacing: 2px; color: #f87171; font-weight: bold; }
        .premio-detalle { font-size: 22px; font-weight: 900; color: #ffffff; margin: 8px 0 0 0; }
        
        .info-valor {
            background: #1f2937;
            border-left: 4px solid #dc2626;
            padding: 14px;
            border-radius: 8px;
            font-size: 15px;
            color: #e5e7eb;
            margin-bottom: 25px;
            text-align: center;
        }

        .tablero-titulo { font-size: 16px; font-weight: bold; margin-bottom: 15px; color: #f3f4f6; text-align: center;}

        /* Tablero optimizado a 4 columnas para llegar a 150 números cómodo en celu */
        .grid-numeros {
            display: grid;
            grid-template-columns: repeat(4, 1fr); 
            gap: 8px;
            margin-bottom: 30px;
        }
        .numpad {
            color: #ffffff;
            border: none;
            padding: 14px 0;
            font-size: 16px;
            font-weight: bold;
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.2s;
            text-align: center;
        }
        
        .numpad.disponible {
            background: #16a34a;
            border-bottom: 4px solid #14532d;
        }
        .numpad.disponible:active {
            transform: translateY(2px);
            border-bottom-width: 2px;
        }
        
        .numpad.ocupado {
            background: #dc2626 !important;
            border-bottom: 4px solid #7f1d1d;
            opacity: 0.7;
            cursor: not-allowed;
        }

        /* Cartel / Modal emergente */
        .modal {
            display: none;
            position: fixed;
            top: 0; left: 0; width: 100%; height: 100%;
            background: rgba(0, 0, 0, 0.85);
            align-items: center; justify-content: center;
            z-index: 1000;
            padding: 10px;
            box-sizing: border-box;
        }
        .modal-content {
            background: #1f2937;
            width: 100%;
            max-width: 360px;
            padding: 25px;
            border-radius: 20px;
            border: 2px solid #374151;
            text-align: center;
        }
        .modal-numero { font-size: 28px; color: #ef4444; font-weight: 900; margin-bottom: 12px; }
        .modal-texto { font-size: 15px; color: #e5e7eb; margin-bottom: 20px; line-height: 1.5; }
        
        .btn-contenedor {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 12px;
        }
        .btn-si {
            background: #16a34a;
            color: white;
            padding: 12px 0;
            font-size: 16px;
            font-weight: bold;
            border: none;
            border-radius: 10px;
            text-decoration: none;
            display: block;
            box-shadow: 0 4px 10px rgba(22, 163, 74, 0.2);
        }
        .btn-no {
            background: #4b5563;
            color: white;
            padding: 12px 0;
            font-size: 16px;
            font-weight: bold;
            border: none;
            border-radius: 10px;
            cursor: pointer;
        }
    </style>
</head>
<body>

<div class="motor-header">
    <div class="header-content">
        <h1>🏍️ GRAN RIFA MOTERA 🏍️</h1>
        <p class="sub">PLATAFORMA TEMÁTICA</p>
    </div>
</div>

<div class="container">
    <div class="premio-box">
        <div class="premio-titulo">🎁 Espectacular Sorteo:</div>
        <div class="premio-detalle">HONDA STORM 125 cc 🔥</div>
    </div>

    <div class="info-valor">
        ⚡ <strong>Valor del Número: $20.000</strong><br>
        Elegí tu número abajo y reservalo al instante.
    </div>

    <div class="tablero-titulo">📍 Tablero en tiempo real (150 números):</div>
    
    <div class="grid-numeros" id="tablero"></div>
</div>

<!-- Cartel de Confirmación -->
<div class="modal" id="modalConfirmar">
    <div class="modal-content">
        <div class="modal-numero" id="textoNumeroSeleccionado">Número XXX</div>
        <p class="modal-texto">
            ¿Confirmás la reserva de este número?<br><br>
            <strong>Al presionar "SÍ":</strong> Se abrirá tu WhatsApp para solicitarme el número y congelarlo.
        </p>
        
        <div class="btn-contenedor">
            <a href="#" class="btn-si" id="btnConfirmarPago" target="_blank" onclick="cerrarModal()">SÍ, reservar</a>
            <button class="btn-no" onclick="cerrarModal()">NO, cambiar</button>
        </div>
    </div>
</div>

<script>
    // ==========================================
    // ⚙️ CONFIGURACIÓN DE GERARDO
    // ==========================================
    
    // 📱 TU WHATSAPP (Con 549 para Argentina, de corrido sin espacios)
    const MI_WHATSAPP = "5491122334455"; 

    // 🔴 NÚMEROS VENDIDOS: Agregá acá entre comillas los números ocupados (del "001" al "150")
    // Ejemplo: const ocupados = ["005", "045", "123"];
    const ocupados = []; 

    // ==========================================
    // LÓGICA DEL TABLERO (150 Números)
    // ==========================================
    const tablero = document.getElementById('tablero');
    const btnPago = document.getElementById('btnConfirmarPago');
    let numeroElegido = "";

    for (let i = 1; i <= 150; i++) {
        let numFormateado = i.toString().padStart(3, '0'); // Formato de 3 cifras: 001, 015, 145
        let boton = document.createElement('button');
        boton.innerText = numFormateado;
        boton.classList.add('numpad');
        
        if (ocupados.includes(numFormateado)) {
            boton.classList.add('ocupado');
            boton.disabled = true;
        } else {
            boton.classList.add('disponible');
            boton.onclick = function() { abrirConfirmacion(numFormateado); };
        }
        tablero.appendChild(boton);
    }

    function abrirConfirmacion(num) {
        numeroElegido = num;
        document.getElementById('textoNumeroSeleccionado').innerText = "🏍️ Número elegido: " + num;
        
        // Mensaje automático personalizado para la moto
        let mensaje = encodeURIComponent("¡Hola Gerardo! 👋 Quiero reservar el número " + num + " para la rifa de la Honda Storm 125cc 🏍️. Pasame los datos para abonar los $20.000.");
        btnPago.href = "https://wa.me/" + MI_WHATSAPP + "?text=" + mensaje;
        
        document.getElementById('modalConfirmar').style.display = 'flex';
    }

    function cerrarModal() {
        document.getElementById('modalConfirmar').style.display = 'none';
    }
</script>

</body>
</html>
