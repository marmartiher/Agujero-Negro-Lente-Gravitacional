<!DOCTYPE html>
<html lang="en" >
<head>
  <meta charset="UTF-8">
  <title>AgujeroNegro</title>
  

</head>
<body>
<!-- partial:index.partial.html -->
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agujero Negro - Simulación Física</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: radial-gradient(circle at center, #0a0a0a 0%, #000000 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: 'Arial', sans-serif;
            overflow: hidden;
        }

        .container {
            display: flex;
            flex-direction: column;
            justify-content: flex-start;
            align-items: center;
            height: 100vh;
            padding-top: 10px;
        }

        .simulation-area {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 10px;
            margin-top: 10px;
        }

        canvas {
            border: 2px solid #333;
            border-radius: 10px;
            box-shadow: 0 0 50px rgba(255, 255, 255, 0.1);
            max-width: 95vw;
            max-height: 70vh;
            width: 100%;
            height: auto;
        }

        .info-panel {
            top: 10px;
            left: 10px;
            right: 10px;
            background: rgba(0, 0, 0, 0.9);
            padding: 12px;
            border-radius: 8px;
            border: 1px solid #333;
            color: #fff;
            font-size: 11px;
            line-height: 1.3;
            z-index: 10;
            display: flex;
            flex-direction: column;
            max-height: 150px;
            width: calc(100% - 20px);
            margin: 0 10px;
        }

        .info-panel h2 {
            color: #ffd700;
            margin: 0 0 8px 0;
            text-shadow: 0 0 10px #ffd700;
            font-size: 13px;
            text-align: left;
        }

        .info-content {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            align-items: flex-start;
            font-size: 10px;
        }

        .info-section {
            flex: 1;
            min-width: 120px;
        }

        .info-section strong {
            color: #ffd700;
        }

        .effects-list {
            display: flex;
            flex-direction: column;
            gap: 1px;
            margin: 5px 0;
        }

        .effects-list strong {
            color: #ddd700;

        }

        .effect-item {
            background: rgba(255, 215, 0, 0.1);
            padding: 3px 6px;
            border-radius: 3px;
            font-size: 9px;
            border: 1px solid rgba(255, 215, 0, 0.3);
            display: inline-block;
            margin-right: 4px;
            margin-bottom: 3px;
        }

        .controls {
            position: relative;
            display: flex;
            gap: 8px;
            align-items: center;
            background: rgba(0, 0, 0, 0.9);
            padding: 10px;
            border-radius: 8px;
            border: 1px solid #333;
            flex-wrap: wrap;
            justify-content: center;
            max-width: 95vw;
            z-index: 10;
        }

        .control-group {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 3px;
            min-width: 60px;
        }

        .control-group label {
            color: #ccc;
            font-size: 10px;
            text-align: center;
        }

        input[type="range"] {
            width: 60px;
            height: 4px;
            border-radius: 2px;
            background: #333;
            outline: none;
            -webkit-appearance: none;
        }

        input[type="range"]::-webkit-slider-thumb {
            appearance: none;
            width: 12px;
            height: 12px;
            border-radius: 50%;
            background: #ffd700;
            cursor: pointer;
            box-shadow: 0 0 10px #ffd700;
        }

        input[type="range"]::-moz-range-thumb {
            width: 12px;
            height: 12px;
            border-radius: 50%;
            background: #ffd700;
            cursor: pointer;
            border: none;
            box-shadow: 0 0 10px #ffd700;
        }

        button {
            background: linear-gradient(45deg, #1a1a1a, #333);
            color: #fff;
            border: 1px solid #555;
            padding: 6px 12px;
            border-radius: 5px;
            cursor: pointer;
            transition: all 0.3s ease;
            font-size: 11px;
            touch-action: manipulation;
        }

        button:hover {
            background: linear-gradient(45deg, #333, #555);
            box-shadow: 0 0 15px rgba(255, 215, 0, 0.3);
        }

        .stars {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: -1;
        }

        .star {
            position: absolute;
            width: 2px;
            height: 2px;
            background: #fff;
            border-radius: 50%;
            animation: twinkle 2s infinite;
        }

        @keyframes twinkle {
            0%, 100% { opacity: 0.3; }
            50% { opacity: 1; }
        }

        /* Media queries para móviles */
        @media (max-width: 767px) {
            .info-panel {
                max-height: 200px;
                padding: 15px;
            }
            
            .info-content {
                flex-direction: column;
                gap: 8px;
            }
            
            .info-section {
                min-width: 100%;
            }
            
            .effects-list {
                flex-direction: column;
                gap: 5px;
            }


            .simulation-area {
                margin-top: 20px;
            }
            
            .container {
                padding-top: 5px;
                justify-content: flex-start;
            }
            
            canvas {
                max-height: 60vh;
            }
        }

        @media (max-width: 480px) {
            .info-panel {
                max-height: 230px;
            }
            
            .info-panel h2 {
                font-size: 12px;
            }
            

.effect-item {
    display: inline-block;
    /* Resto del estilo permanece igual */
}
            
            .simulation-area {
                gap: 15px;
            }
        }
    </style>
</head>
<body>
    <div class="stars" id="stars"></div>
    
    <div class="container">
        <div class="info-panel"> 
            <h2 style="text-align: center;">🌀AGUJERO NEGRO</h2>
            <div class="info-content" align="center">
                <div class="info-section">
                    <strong>Lente gravitacional y disco de acreción</strong> <br> 
		    <strong>Masa:</strong> <span id="massValue">10</span> M☉ 💫  <strong>        Radio:</strong> <span id="radiusValue">15</span> UA
                </div>
		<div class="info-section">
                <div class="effects-list" align="center">
                     <strong>Efectos:  E. Doppler | Horizonte eventos | Radiacion Hawking </strong> </div>  </div> 
            </div>
        </div>

        <div class="simulation-area">
            <canvas id="blackHoleCanvas" width="400" height="400"></canvas>
            
            <div class="controls">
                <div class="control-group">
                    <label>Masa (M☉)</label>
                    <input type="range" id="massSlider" min="2" max="50" value="10">
                </div>
                <div class="control-group">
                    <label>Velocidad</label>
                    <input type="range" id="speedSlider" min="0.1" max="3" step="0.1" value="1">
                </div>
                <div class="control-group">
                    <label>Partículas</label>
                    <input type="range" id="particlesSlider" min="50" max="300" value="150">
                </div>
                <button id="resetBtn">Reiniciar</button>
            </div>
        </div>
    </div>

    <script>
        // Crear estrellas de fondo (menos para móvil)
        function createStars() {
            const starsContainer = document.getElementById('stars');
            const starCount = window.innerWidth < 768 ? 150 : 300; // Menos estrellas en móvil
            
            for (let i = 0; i < starCount; i++) {
                const star = document.createElement('div');
                star.className = 'star';
                star.style.left = Math.random() * 100 + '%';
                star.style.top = Math.random() * 100 + '%';
                star.style.animationDelay = Math.random() * 2 + 's';
                star.style.animationDuration = (Math.random() * 3 + 1) + 's';
                starsContainer.appendChild(star);
            }
        }

        class BlackHole {
            constructor(canvas) {
                this.canvas = canvas;
                this.ctx = canvas.getContext('2d');
                this.centerX = canvas.width / 2;
                this.centerY = canvas.height / 2;
                
                // Propiedades físicas ajustadas para móvil
                this.mass = 10;
                this.schwarzschildRadius = 15; // Más pequeño para pantalla móvil
                this.accretionDiskRadius = 80; // Más pequeño para pantalla móvil
                
                // Partículas del disco de acreción
                this.particles = [];
                this.particleCount = window.innerWidth < 768 ? 100 : 150; // Menos partículas en móvil
                
                // Propiedades de animación
                this.time = 0;
                this.speed = 1;
                
                this.initParticles();
                this.animate();
            }
            
            initParticles() {
                this.particles = [];
                for (let i = 0; i < this.particleCount; i++) {
                    const angle = Math.random() * Math.PI * 2;
                    const safeMargin = 10;
            const radius = this.schwarzschildRadius + safeMargin + Math.random() * (this.accretionDiskRadius - safeMargin);

                    // Velocidad orbital basada en la distancia (más rápido cerca del agujero negro)
                    const orbitalSpeed = Math.sqrt(this.mass / radius) * 0.1;
                    
                    this.particles.push({
                        x: this.centerX + Math.cos(angle) * radius,
                        y: this.centerY + Math.sin(angle) * radius,
                        angle: angle,
                        radius: radius,
                        initialRadius: radius,
                        speed: orbitalSpeed,
                        brightness: Math.random() * 0.8 + 0.2,
                        color: this.getParticleColor(radius),
                        life: 1.0,
                        colorSeed: Math.random() * 1000 // Semilla para consistencia de color
                    });
                }
            }
            
            getParticleColor(radius) {
                // Combinación de efectos físicos y variedad visual
                const normalizedRadius = (radius - this.schwarzschildRadius) / this.accretionDiskRadius;
                const temperature = 1 - normalizedRadius * 0.7; // Más caliente cerca del agujero negro
                
                // Array de colores base más diversos
                const baseColors = [
                    { h: 240, name: 'azul' },     // Azul (alta energía)
                    { h: 280, name: 'violeta' },  // Violeta
                    { h: 300, name: 'magenta' },  // Magenta
                    { h: 0, name: 'rojo' },       // Rojo
                    { h: 30, name: 'naranja' },   // Naranja
                    { h: 60, name: 'amarillo' },  // Amarillo
                    { h: 120, name: 'verde' },    // Verde
                    { h: 180, name: 'cian' },     // Cian
                    { h: 200, name: 'azul-cian' } // Azul-cian
                ];
                
                // Seleccionar color base según la posición y un factor aleatorio
                const colorIndex = Math.floor((radius * 0.1 + this.time * 0.01) * baseColors.length) % baseColors.length;
                const baseColor = baseColors[colorIndex];
                
                // Ajustar saturación y luminosidad según la temperatura
                let saturation = 70 + temperature * 30; // Más saturado = más caliente
                let lightness = 30 + temperature * 50;   // Más brillante = más caliente
                
                // Variación adicional para más diversidad
                const variation = Math.sin(radius * 0.05 + this.time * 0.02) * 20;
                lightness = Math.max(20, Math.min(80, lightness + variation));
                
                // Partículas muy cercanas al agujero negro se vuelven blanco-azuladas (plasma)
                if (temperature > 0.9) {
                    return `hsl(220, 100%, ${80 + temperature * 20}%)`;
                }
                
                return `hsl(${baseColor.h}, ${saturation}%, ${lightness}%)`;
            }
            
            updateParticles() {
                this.particles.forEach(particle => {
                    // Movimiento orbital
                    particle.angle += particle.speed * this.speed;
                    
                    // Simulación de la pérdida de energía: las partículas espiralan hacia adentro
                    const energyLoss = 0.0005 * this.speed;
                    particle.radius -= energyLoss;
                    
                    // Recalcular posición
                    particle.x = this.centerX + Math.cos(particle.angle) * particle.radius;
                    particle.y = this.centerY + Math.sin(particle.angle) * particle.radius;
                    
                    // Actualizar color basado en la nueva distancia
                    particle.color = this.getParticleColor(particle.radius);
                    
                    // Incrementar brillo cerca del horizonte de eventos
                    const distanceRatio = particle.radius / Math.max(this.schwarzschildRadius, 1);
                    particle.brightness = Math.min(1, 1 / (distanceRatio * 0.5));
                    
                    // Eliminar partículas que caen al agujero negro
                    if (particle.radius <= this.schwarzschildRadius) {
                        particle.life = 0;
                    }
                });
                
                // Regenerar partículas que han caído
                this.particles = this.particles.filter(p => p.life > 0);
                while (this.particles.length < this.particleCount) {
                    const angle = Math.random() * Math.PI * 2;
                    const radius = this.schwarzschildRadius + Math.random() * this.accretionDiskRadius;
                    const orbitalSpeed = Math.sqrt(this.mass / radius) * 0.1;
                    
                    this.particles.push({
                        x: this.centerX + Math.cos(angle) * radius,
                        y: this.centerY + Math.sin(angle) * radius,
                        angle: angle,
                        radius: radius,
                        initialRadius: radius,
                        speed: orbitalSpeed,
                        brightness: Math.random() * 0.8 + 0.2,
                        color: this.getParticleColor(radius),
                        life: 1.0,
                        colorSeed: Math.random() * 1000
                    });
                }
            }
            
            drawAccretionDisk() {
                // Dibujar disco de acreción con efecto de brillo y colores diversos
                this.particles.forEach(particle => {
                    const size = Math.max(1, 3 * particle.brightness);
                    
                    // Efecto de brillo exterior más sutil
                    const outerGradient = this.ctx.createRadialGradient(
                        particle.x, particle.y, 0,
                        particle.x, particle.y, size * 4
                    );
                    outerGradient.addColorStop(0, particle.color);
                    outerGradient.addColorStop(0.3, particle.color.replace(')', ', 0.3)').replace('hsl', 'hsla'));
                    outerGradient.addColorStop(1, 'transparent');
                    
                    this.ctx.fillStyle = outerGradient;
                    this.ctx.beginPath();
                    this.ctx.arc(particle.x, particle.y, size * 4, 0, Math.PI * 2);
                    this.ctx.fill();
                    
                    // Halo medio
                    const midGradient = this.ctx.createRadialGradient(
                        particle.x, particle.y, 0,
                        particle.x, particle.y, size * 2
                    );
                    midGradient.addColorStop(0, particle.color);
                    midGradient.addColorStop(0.6, particle.color.replace(')', ', 0.6)').replace('hsl', 'hsla'));
                    midGradient.addColorStop(1, 'transparent');
                    
                    this.ctx.fillStyle = midGradient;
                    this.ctx.beginPath();
                    this.ctx.arc(particle.x, particle.y, size * 2, 0, Math.PI * 2);
                    this.ctx.fill();
                    
                    // Núcleo brillante de la partícula
                    this.ctx.fillStyle = particle.color;
                    this.ctx.beginPath();
                    this.ctx.arc(particle.x, particle.y, size, 0, Math.PI * 2);
                    this.ctx.fill();
                    
                    // Punto central extra brillante
                    this.ctx.fillStyle = 'rgba(255, 255, 255, 0.8)';
                    this.ctx.beginPath();
                    this.ctx.arc(particle.x, particle.y, size * 0.3, 0, Math.PI * 2);
                    this.ctx.fill();
                });
            }
            
            drawEventHorizon() {
                // Horizonte de eventos - semi-transparente para mostrar estrellas internas
                this.ctx.fillStyle = 'rgba(0, 0, 0, 0.8)';
                this.ctx.beginPath();
                this.ctx.arc(this.centerX, this.centerY, this.schwarzschildRadius, 0, Math.PI * 2);
                this.ctx.fill();
                
                // Borde del horizonte con efecto de lente gravitacional
                const gradient = this.ctx.createRadialGradient(
                    this.centerX, this.centerY, this.schwarzschildRadius - 5,
                    this.centerX, this.centerY, this.schwarzschildRadius + 10
                );
                gradient.addColorStop(0, 'transparent');
                gradient.addColorStop(0.5, 'rgba(255, 255, 255, 0.3)');
                gradient.addColorStop(1, 'transparent');
                
                this.ctx.strokeStyle = gradient;
                this.ctx.lineWidth = 2;
                this.ctx.beginPath();
                this.ctx.arc(this.centerX, this.centerY, this.schwarzschildRadius, 0, Math.PI * 2);
                this.ctx.stroke();
            }
            
            drawGravitationalLensing() {
                // Efecto de lente gravitacional - distorsión del espacio-tiempo
                for (let i = 0; i < 5; i++) {
                    const radius = this.schwarzschildRadius + (i + 1) * 30;
                    const opacity = 0.1 / (i + 1);
                    
                    this.ctx.strokeStyle = `rgba(255, 255, 255, ${opacity})`;
                    this.ctx.lineWidth = 1;
                    this.ctx.beginPath();
                    this.ctx.arc(this.centerX, this.centerY, radius, 0, Math.PI * 2);
                    this.ctx.stroke();
                }
            }
            
            drawHawkingRadiation() {
                // Simulación de la radiación de Hawking
                const hawkingIntensity = this.mass < 10 ? 0.3 : 0.1; // Agujeros negros pequeños radian más
                
                for (let i = 0; i < 20; i++) {
                    const angle = Math.random() * Math.PI * 2;
                    const distance = this.schwarzschildRadius + Math.random() * 50;
                    const x = this.centerX + Math.cos(angle) * distance;
                    const y = this.centerY + Math.sin(angle) * distance;
                    
                    this.ctx.fillStyle = `rgba(255, 255, 255, ${hawkingIntensity * Math.random()})`;
                    this.ctx.beginPath();
                    this.ctx.arc(x, y, 1, 0, Math.PI * 2);
                    this.ctx.fill();
                }
            }
            
            drawStarsInsideBlackHole() {
                // Estrellas dentro del horizonte de eventos
                const starCount = 25;
                
                for (let i = 0; i < starCount; i++) {
                    // Distribución uniforme con rotación lenta
                    const angle = (i * 137.5 + this.time * 10) % 360;
                    const distance = Math.random() * (this.schwarzschildRadius - 5) + 3;
                    const x = this.centerX + Math.cos(angle * Math.PI / 180) * distance;
                    const y = this.centerY + Math.sin(angle * Math.PI / 180) * distance;
                    
                    // Estrella principal - más brillante y más grande
                    this.ctx.fillStyle = 'rgba(255, 255, 255, 1)';
                    this.ctx.beginPath();
                    this.ctx.arc(x, y, 3, 0, Math.PI * 2);
                    this.ctx.fill();
                    
                    // Brillo alrededor de la estrella - más grande y brillante
                    const gradient = this.ctx.createRadialGradient(
                        x, y, 0,
                        x, y, 8
                    );
                    gradient.addColorStop(0, 'rgba(255, 255, 255, 0.8)');
                    gradient.addColorStop(1, 'rgba(255, 255, 255, 0)');
                    
                    this.ctx.fillStyle = gradient;
                    this.ctx.beginPath();
                    this.ctx.arc(x, y, 8, 0, Math.PI * 2);
                    this.ctx.fill();
                }
            }

            draw() {
                // Limpiar canvas
                this.ctx.fillStyle = 'rgba(0, 0, 0, 0.1)';
                this.ctx.fillRect(0, 0, this.canvas.width, this.canvas.height);
                
                // Dibujar efectos en orden (estrellas internas antes del horizonte)
                this.drawGravitationalLensing();
                this.drawAccretionDisk();
                this.drawStarsInsideBlackHole(); // Estrellas dentro del agujero negro
                this.drawEventHorizon(); // Horizonte semi-transparente
                this.drawHawkingRadiation();
            }
            
            animate() {
                this.time += 0.016 * this.speed;
                this.updateParticles();
                this.draw();
                requestAnimationFrame(() => this.animate());
            }
            
            setMass(mass) {
                const minMass = 4;
                this.mass = Math.max(minMass, mass);
                this.schwarzschildRadius = this.mass * 1.5;
                this.initParticles();
            }
            
            setSpeed(speed) {
                this.speed = speed;
            }
            
            setParticleCount(count) {
                this.particleCount = count;
                this.initParticles();
            }
        }
        
        // Inicializar la aplicación
        document.addEventListener('DOMContentLoaded', function() {
            createStars();
            
            const canvas = document.getElementById('blackHoleCanvas');
            const blackHole = new BlackHole(canvas);
            
            // Controles
            const massSlider = document.getElementById('massSlider');
            const speedSlider = document.getElementById('speedSlider');
            const particlesSlider = document.getElementById('particlesSlider');
            const resetBtn = document.getElementById('resetBtn');
            
            const massValue = document.getElementById('massValue');
            const radiusValue = document.getElementById('radiusValue');
            
            massSlider.addEventListener('input', (e) => {
                const mass = parseFloat(e.target.value);
                blackHole.setMass(mass);
                massValue.textContent = mass;
                radiusValue.textContent = Math.round(Math.max(2, mass) * 1.5);

            });
            
            speedSlider.addEventListener('input', (e) => {
                blackHole.setSpeed(parseFloat(e.target.value));
            });
            
            particlesSlider.addEventListener('input', (e) => {
                blackHole.setParticleCount(parseInt(e.target.value));
            });
            
            resetBtn.addEventListener('click', () => location.reload());
        });
    </script>
</body>
</html>
<!-- partial -->
  
</body>
</html>
