<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Para Mi Amor - Flores Amarillas</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #fffdf0;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            color: #5c3d00;
        }
        
        .container {
            max-width: 800px;
            background: white;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            overflow: hidden;
            margin: 20px;
            position: relative;
        }
        
        .header {
            background: linear-gradient(to right, #ffeb3b, #ffc107);
            padding: 30px;
            text-align: center;
        }
        
        h1 {
            margin: 0;
            color: white;
            font-size: 2.5rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
        }
        
        .subtitle {
            color: rgba(255, 255, 255, 0.9);
            font-style: italic;
            margin-top: 10px;
        }
        
        .content {
            padding: 30px;
            position: relative;
        }
        
        .message {
            font-size: 1.2rem;
            line-height: 1.6;
            text-align: center;
            margin-bottom: 30px;
        }
        
        .flowers-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin: 30px 0;
        }
        
        .flower {
            width: 80px;
            height: 80px;
            background: #ffeb3b;
            border-radius: 50% 50% 50% 50%;
            position: relative;
            animation: float 5s infinite ease-in-out;
            box-shadow: 0 5px 15px rgba(255, 200, 0, 0.3);
        }
        
        .flower:nth-child(2n) {
            animation-delay: 1s;
            background: #ffc107;
        }
        
        .flower:nth-child(3n) {
            animation-delay: 2s;
            background: #ffd54f;
        }
        
        .petal {
            position: absolute;
            width: 30px;
            height: 30px;
            background: #ffeb3b;
            border-radius: 50%;
        }
        
        .petal:nth-child(1) { top: -15px; left: 25px; }
        .petal:nth-child(2) { top: 5px; right: -15px; }
        .petal:nth-child(3) { bottom: -15px; left: 25px; }
        .petal:nth-child(4) { top: 5px; left: -15px; }
        .petal:nth-child(5) { top: -8px; left: 5px; }
        .petal:nth-child(6) { top: -8px; right: 5px; }
        .petal:nth-child(7) { bottom: -8px; left: 5px; }
        .petal:nth-child(8) { bottom: -8px; right: 5px; }
        
        .center {
            position: absolute;
            width: 30px;
            height: 30px;
            background: #795548;
            border-radius: 50%;
            top: 25px;
            left: 25px;
            z-index: 2;
        }
        
        .footer {
            text-align: center;
            padding: 20px;
            background: #f9f9f9;
            font-style: italic;
            color: #888;
        }
        
        .heart {
            color: #ff4d4d;
            font-size: 1.5rem;
            animation: pulse 1.5s infinite;
            display: inline-block;
        }
        
        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-15px); }
        }
        
        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.2); }
        }
        
        @media (max-width: 600px) {
            h1 { font-size: 2rem; }
            .message { font-size: 1rem; }
            .flower { width: 60px; height: 60px; }
            .petal { width: 20px; height: 20px; }
            .center { 
                width: 20px; 
                height: 20px;
                top: 20px;
                left: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Para Mi Amor</h1>
            <div class="subtitle">Las flores amarillas de nuestro amor</div>
        </div>
        
        <div class="content">
            <div class="message">
                <p>Querida <strong>[Nombre de tu novia]</strong>,</p>
                <p>En este día especial, quise regalarte estas flores amarillas que representan la alegría que traes a mi vida, la calidez de tu amor y la luz que ilumina mis días.</p>
                <p>Cada pétalo es un momento feliz que hemos compartido, y el centro de cada flor es la esencia de nuestro cariño.</p>
                <p>Te amo hoy y siempre.</p>
            </div>
            
            <div class="flowers-container">
                <div class="flower">
                    <div class="petal"></div>
                    <div class="petal"></div>
                    <div class="petal"></div>
                    <div class="petal"></div>
                    <div class="petal"></div>
                    <div class="petal"></div>
                    <div class="petal"></div>
                    <div class="petal"></div>
                    <div class="center"></div>
                </div>
                
                <div class="flower">
                    <div class="petal"></div>
                    <div class="petal"></div>
                    <div class="petal"></div>
                    <div class="petal"></div>
                    <div class="petal"></div>
                    <div class="petal"></div>
                    <div class="petal"></div>
                    <div class="petal"></div>
                    <div class="center"></div>
                </div>
                
                <div class="flower">
                    <div class="petal"></div>
                    <div class="petal"></div>
                    <div class="petal"></div>
                    <div class="petal"></div>
                    <div class="petal"></div>
                    <div class="petal"></div>
                    <div class="petal"></div>
                    <div class="petal"></div>
                    <div class="center"></div>
                </div>
            </div>
            
            <div class="message">
                <p>Que nuestro amor siga floreciendo como estas flores amarillas,<br>siempre radiante y lleno de vida.</p>
                <p>Con todo mi cariño,<br><strong>[Tu nombre]</strong></p>
            </div>
        </div>
        
        <div class="footer">
            <p>Creado con <span class="heart">❤</span> para ti | <span id="date"></span></p>
        </div>
    </div>

    <script>
        // Establecer la fecha actual
        const now = new Date();
        const options = { weekday: 'long', year: 'numeric', month: 'long', day: 'numeric' };
        document.getElementById('date').textContent = now.toLocaleDateString('es-ES', options);
        
        // Efecto de caída de pétalos
        function createPetal() {
            const petal = document.createElement('div');
            petal.style.position = 'fixed';
            petal.style.width = '15px';
            petal.style.height = '15px';
            petal.style.background = 'linear-gradient(to right, #ffeb3b, #ffc107)';
            petal.style.borderRadius = '50% 50% 50% 50%';
            petal.style.zIndex = '1000';
            petal.style.top = '0';
            petal.style.left = Math.random() * window.innerWidth + 'px';
            petal.style.opacity = '0.7';
            petal.style.pointerEvents = 'none';
            document.body.appendChild(petal);
            
            const animation = petal.animate([
                { transform: 'translateY(0) rotate(0deg)', opacity: 0.7 },
                { transform: `translateY(${window.innerHeight}px) rotate(${360}deg)`, opacity: 0 }
            ], {
                duration: Math.random() * 3000 + 3000,
                easing: 'cubic-bezier(0.4, 0.0, 0.2, 1)'
            });
            
            animation.onfinish = () => {
                petal.remove();
            };
        }
        
        // Crear pétalos cada 300ms
        setInterval(createPetal, 300);
    </script>
</body>
</html>
