<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Celestial Serenade</title>
<style>
    body {
        margin: 0;
        padding: 0;
        overflow: hidden;
        background-color: #000;
        font-family: 'Inter', sans-serif;
    }
    canvas {
        display: block;
    }

    /* Menú hamburguesa ☰ */
    #menu-toggle {
        position: absolute;
        top: 20px;
        left: 20px;
        width: 40px;
        height: 40px;
        background: rgba(255, 255, 255, 0.15);
        backdrop-filter: blur(12px);
        border: 1px solid rgba(255, 255, 255, 0.2);
        border-radius: 12px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 5px;
        cursor: pointer;
        z-index: 100;
    }
    .menu-bar {
        width: 24px;
        height: 3px;
        background: white;
        border-radius: 2px;
        transition: all 0.3s ease;
    }
    #menu-toggle.active .menu-bar:nth-child(1) {
        transform: rotate(45deg) translate(5px, 5px);
    }
    #menu-toggle.active .menu-bar:nth-child(2) {
        opacity: 0;
    }
    #menu-toggle.active .menu-bar:nth-child(3) {
        transform: rotate(-45deg) translate(5px, -5px);
    }

    /* Panel de configuración */
    #settings-panel {
        position: absolute;
        top: 70px;
        left: 20px;
        width: 300px;
        background: rgba(20, 20, 40, 0.92);
        backdrop-filter: blur(16px);
        border: 1px solid rgba(255, 255, 255, 0.1);
        border-radius: 16px;
        padding: 20px;
        box-shadow: 0 8px 32px rgba(0, 0, 0, 0.5);
        color: white;
        font-size: 14px;
        z-index: 90;
        display: none;
        flex-direction: column;
        gap: 16px;
        max-height: 80vh;
        overflow-y: auto;
    }
    #settings-panel.active {
        display: flex;
    }
    .setting-section {
        display: flex;
        flex-direction: column;
        gap: 12px;
        padding: 12px 0;
        border-top: 1px solid rgba(255, 255, 255, 0.1);
    }
    .setting-section:first-child {
        border-top: none;
    }
    .setting-section h3 {
        margin: 0;
        font-size: 16px;
        color: #e0e0ff;
    }
    .setting-control {
        display: flex;
        align-items: center;
        gap: 10px;
    }
    .setting-control label {
        width: 120px;
        font-size: 13px;
    }
    .setting-control input[type="color"] {
        width: 50px;
        height: 24px;
        border: none;
        border-radius: 4px;
        cursor: pointer;
    }
    .setting-control input[type="range"] {
        flex: 1;
        height: 6px;
        border-radius: 3px;
        background: #333;
        outline: none;
        -webkit-appearance: none;
    }
    .setting-control input[type="range"]::-webkit-slider-thumb {
        -webkit-appearance: none;
        width: 16px;
        height: 16px;
        border-radius: 50%;
        background: #7f5af0;
        cursor: pointer;
    }
    .creator-info {
        background: rgba(127, 90, 240, 0.2);
        padding: 15px;
        border-radius: 10px;
        font-family: 'Georgia', serif;
        text-align: center;
        font-size: 15px;
        line-height: 1.5;
    }

    /* Créditos inferiores */
    .credit-footer {
        position: fixed;
        bottom: 15px;
        left: 0;
        width: 100%;
        text-align: center;
        color: rgba(255, 255, 255, 0.7);
        font-family: 'Georgia', serif;
        font-size: 14px;
        letter-spacing: 1px;
        z-index: 20;
        pointer-events: none;
        text-shadow: 0 0 5px rgba(255, 255, 255, 0.3);
    }
</style>

<div id="menu-toggle">
    <div class="menu-bar"></div>
    <div class="menu-bar"></div>
    <div class="menu-bar"></div>
</div>

<div id="settings-panel">
    <div class="setting-section">
        <h3>🎨 Colores</h3>
        <div class="setting-control">
            <label>Shockwave:</label>
            <input type="color" id="shockwaveColor" value="#DA70D6">
        </div>
        <div class="setting-control">
            <label>Stream 1:</label>
            <input type="color" id="stream1Color" value="#DA70D6">
        </div>
        <div class="setting-control">
            <label>Stream 2:</label>
            <input type="color" id="stream2Color" value="#C71585">
        </div>
        <div class="setting-control">
            <label>Stream 3:</label>
            <input type="color" id="stream3Color" value="#9932CC">
        </div>
        <div class="setting-control">
            <label>Stream 4:</label>
            <input type="color" id="stream4Color" value="#8A2BE2">
        </div>
        <div class="setting-control">
            <label>Stream 5:</label>
            <input type="color" id="stream5Color" value="#9370DB">
        </div>
        <div class="setting-control">
            <label>Texto 3D:</label>
            <input type="color" id="textColor" value="#FFFFFF">
        </div>
    </div>

    <div class="setting-section">
        <h3>✨ Brillo y Efectos</h3>
        <div class="setting-control">
            <label>Brillo Global:</label>
            <input type="range" id="globalBrightness" min="0.5" max="2.0" step="0.1" value="1.0">
        </div>
        <div class="setting-control">
            <label>Intensidad Bloom:</label>
            <input type="range" id="bloomIntensity" min="0.5" max="3.0" step="0.1" value="1.5">
        </div>
    </div>

    <div class="setting-section">
        <h3>🌀 Orbital</h3>
        <div class="setting-control">
            <label>Velocidad Giro:</label>
            <input type="range" id="rotationSpeed" min="0.1" max="2.0" step="0.1" value="1.0">
        </div>
    </div>

    <div class="setting-section">
        <h3>👑 Información del Creador</h3>
        <div class="creator-info">
            <strong>By AnthZz Berrocal</strong><br>
            BerMatMods<br>
            Creador de Experiencias Celestiales<br>
            © 2025 - Todos los derechos reservados
        </div>
    </div>
</div>

<div class="credit-footer">By AnthZz Berrocal BerMatMods</div>

<script type="importmap">
{
    "imports": {
        "three": "https://cdn.jsdelivr.net/npm/three@0.162.0/build/three.module.js",
        "three/addons/": "https://cdn.jsdelivr.net/npm/three@0.162.0/examples/jsm/"
    }
}
</script>

<script type="module">
import * as THREE from 'three';
import { OrbitControls } from 'three/addons/controls/OrbitControls.js';
import { EffectComposer } from 'three/addons/postprocessing/EffectComposer.js';
import { RenderPass } from 'three/addons/postprocessing/RenderPass.js';
import { UnrealBloomPass } from 'three/addons/postprocessing/UnrealBloomPass.js';
import { TextGeometry } from 'three/addons/geometries/TextGeometry.js';
import { FontLoader } from 'three/addons/loaders/FontLoader.js';

const scene = new THREE.Scene();
const camera = new THREE.PerspectiveCamera(75, window.innerWidth / window.innerHeight, 0.1, 2000);
camera.position.set(0, 20, 120);

const renderer = new THREE.WebGLRenderer({
    antialias: true,
    powerPreference: "high-performance"
});
renderer.setSize(window.innerWidth, window.innerHeight);
renderer.setPixelRatio(Math.min(window.devicePixelRatio, 2));
document.body.appendChild(renderer.domElement);

const controls = new OrbitControls(camera, renderer.domElement);
controls.enableDamping = true;
controls.dampingFactor = 0.05;
controls.minDistance = 30;
controls.maxDistance = 250;
controls.autoRotate = false;
controls.autoRotateSpeed = 0.1;

const composer = new EffectComposer(renderer);
composer.addPass(new RenderPass(scene, camera));
const bloomPass = new UnrealBloomPass(new THREE.Vector2(window.innerWidth, window.innerHeight), 1.5, 0.4, 0.85);
bloomPass.threshold = 0.05;
composer.addPass(bloomPass);

// MUCHAS más frases románticas (¡40+!)
const romanticPhrases = [
    "Te amo", "Mi reina", "Mi corazón", "Mi todo", "Eres mi amor", "Preciosa",
    "Mi vida entera", "Eres perfecta", "Mi eternidad", "Mi dulzura", "Mi razón de ser",
    "Mi princesa", "Mi tesoro", "Mi alegría", "Mi sueño hecho realidad", "Eres mi universo",
    "Mi alma gemela", "Mi felicidad", "Mi estrella", "Te adoro", "Eres mi paz",
    "Mi refugio", "Mi inspiración", "Mi milagro", "Mi fortaleza", "Mi ternura",
    "Mi pasión", "Mi locura", "Mi verdad", "Mi destino", "Mi presente",
    "Mi futuro", "Mi hoy", "Mi siempre", "Mi luz", "Mi calma",
    "Mi suspiro", "Mi poesía", "Mi canción", "Mi verso", "Mi abrazo eterno"
];

let currentThemeName = 'nebula';
const clock = new THREE.Clock();

const sharedUniforms = {
    uTime: { value: 0 },
    uClickTime: { value: -1000.0 },
    uShockwaveColor: { value: new THREE.Color("#DA70D6") }
};

// Load font for 3D text
let fontLoaded = false;
let font = null;
const loader = new FontLoader();
loader.load('https://threejs.org/examples/fonts/helvetiker_bold.typeface.json', function (loadedFont) {
    font = loadedFont;
    fontLoaded = true;
    if (textPaths.length > 0) createAllTextOnPaths();
});

// Particle shader
const particleShader = {
    vertexShader: `
        uniform float uTime;
        uniform float uClickTime;
        attribute float size;
        attribute vec3 customColor;
        attribute float phase;
        varying vec3 vColor;
        varying float vShockwaveIntensity;
        void main() {
            vColor = customColor;
            vec3 pos = position;
            vShockwaveIntensity = 0.0;
            float timeSinceClick = uTime - uClickTime;
            if(timeSinceClick > 0.0 && timeSinceClick < 5.0) {
                float waveSpeed = 50.0;
                float waveFront = timeSinceClick * waveSpeed;
                float dist = length(position);
                float shockwaveThickness = 40.0;
                float distFromWavefront = abs(dist - waveFront);
                
                if(distFromWavefront < shockwaveThickness) {
                    float waveProfile = smoothstep(shockwaveThickness, 0.0, distFromWavefront);
                    vShockwaveIntensity = waveProfile * 1.5;
                    if (dist > 0.0) {
                        vec3 direction = normalize(position);
                        pos += direction * waveProfile * 8.0;
                    }
                }
            }
            float dist = length(pos.xz);
            if (dist > 0.0) {
                float swirlAngle = atan(pos.z, pos.x);
                float swirlSpeed = 0.5 / (dist * 0.05 + 1.0);
                swirlAngle += uTime * swirlSpeed;
                pos.x = cos(swirlAngle) * dist;
                pos.z = sin(swirlAngle) * dist;
            }
            pos.y += sin(uTime * 0.5 + dist * 0.1) * 1.0;
            vec4 mvPosition = modelViewMatrix * vec4(pos, 1.0);
            
            float pulse = 0.9 + 0.2 * sin(uTime * 2.0 + phase);
            float finalSize = (size * pulse) + vShockwaveIntensity * 3.0;
            gl_PointSize = finalSize * (400.0 / -mvPosition.z);
            gl_Position = projectionMatrix * mvPosition;
        }
    `,
    fragmentShader: `
        uniform vec3 uShockwaveColor;
        varying vec3 vColor;
        varying float vShockwaveIntensity;
        
        void main() {
            float dist = length(2.0 * gl_PointCoord - 1.0);
            if (dist > 1.0) discard;
            
            float intensity = exp(-dist * 6.0) * 1.2;
            vec3 finalColor = mix(vColor, uShockwaveColor, vShockwaveIntensity * 0.7);
            float alpha = intensity * 0.9 + vShockwaveIntensity * 0.3;
            
            gl_FragColor = vec4(finalColor, alpha);
        }
    `
};

// Text material — ¡BRILLO REDUCIDO! (opacity: 0.85 en vez de 0.95)
const createTextMaterial = (color) => {
    return new THREE.MeshBasicMaterial({
        color: color,
        transparent: true,
        opacity: 0.85, // 👈 ¡Reducido brillo!
        side: THREE.DoubleSide
    });
};

let activeStreams = [];
let textMeshes = [];

function createLoxodromePath({ radius, turns, points }) {
    const path = [];
    for (let i = 0; i <= points; i++) {
        const t = i / points;
        const angle = t * Math.PI;
        const y = radius * Math.cos(angle);
        const r = radius * Math.sin(angle);
        const theta = t * turns * Math.PI * 2;
        const x = r * Math.cos(theta);
        const z = r * Math.sin(theta);
        path.push(new THREE.Vector3(x, y, z));
    }
    return path;
}

const textPaths = [];

// ¡MÁS PARTÍCULAS!
const streamConfigs = [
    { radius: 25, turns: 3, width: 1.5, count: 22000 },
    { radius: 35, turns: -4, width: 1.5, count: 22000 },
    { radius: 45, turns: 2.5, width: 2.0, count: 28000 },
    { radius: 55, turns: -3.5, width: 2.0, count: 28000 },
    { radius: 65, turns: 4.5, width: 2.5, count: 34000 },
];

function clearStreams() {
    activeStreams.forEach(stream => {
        scene.remove(stream);
        stream.geometry.dispose();
        stream.material.dispose();
    });
    activeStreams = [];
    
    textMeshes.forEach(mesh => {
        scene.remove(mesh);
        mesh.geometry.dispose();
        if (mesh.material.dispose) mesh.material.dispose();
    });
    textMeshes = [];
}

function createParticleStream({ pathPoints, particleCount, streamWidth, colorFn, sizeFn, index }) {
    const geometry = new THREE.BufferGeometry();
    const positions = [], colors = [], sizes = [], phases = [];
    
    for (let i = 0; i < particleCount; i++) {
        const pathIndex = Math.floor(Math.random() * pathPoints.length);
        const pathPoint = pathPoints[pathIndex];
        const offset = new THREE.Vector3().randomDirection().multiplyScalar(Math.random() * streamWidth);
        const pos = pathPoint.clone().add(offset);
        positions.push(pos.x, pos.y, pos.z);
        const color = colorFn(pos, pathIndex / pathPoints.length);
        colors.push(color.r, color.g, color.b);
        sizes.push(sizeFn());
        phases.push(pathIndex / pathPoints.length * Math.PI * 2);
    }
    
    geometry.setAttribute('position', new THREE.Float32BufferAttribute(positions, 3));
    geometry.setAttribute('customColor', new THREE.Float32BufferAttribute(colors, 3));
    geometry.setAttribute('size', new THREE.Float32BufferAttribute(sizes, 1));
    geometry.setAttribute('phase', new THREE.Float32BufferAttribute(phases, 1));
    
    const material = new THREE.ShaderMaterial({
        uniforms: sharedUniforms,
        vertexShader: particleShader.vertexShader,
        fragmentShader: particleShader.fragmentShader,
        transparent: true,
        depthWrite: false,
        blending: THREE.AdditiveBlending
    });
    
    const points = new THREE.Points(geometry, material);
    scene.add(points);
    return points;
}

function createTextOnPath(path, color) {
    if (!fontLoaded) return;
    
    const phrase = romanticPhrases[Math.floor(Math.random() * romanticPhrases.length)];
    
    const textGeometry = new TextGeometry(phrase, {
        font: font,
        size: 2.0,
        height: 0.3,
        curveSegments: 12,
        bevelEnabled: false
    });
    textGeometry.computeBoundingBox();
    
    const textMaterial = createTextMaterial(color);
    const textMesh = new THREE.Mesh(textGeometry, textMaterial);
    
    const totalLength = path.length;
    const midIndex = Math.floor(totalLength * 0.1 + Math.random() * totalLength * 0.8);
    const position = path[midIndex].clone();
    textMesh.position.copy(position);
    
    textMesh.lookAt(camera.position);
    
    textMesh.userData = {
        originalPosition: position.clone(),
        pathIndex: midIndex,
        path: path,
        baseRotation: Math.random() * Math.PI * 2
    };
    
    scene.add(textMesh);
    textMeshes.push(textMesh);
}

function createAllTextOnPaths() {
    textPaths.forEach((path, index) => {
        const color = document.getElementById('textColor').value || "#FFFFFF";
        // ¡AHORA 3-5 TEXTOS POR STREAM! (antes 2-3)
        const textCount = 3 + Math.floor(Math.random() * 3);
        for (let i = 0; i < textCount; i++) {
            setTimeout(() => {
                createTextOnPath(path, color);
            }, i * 300);
        }
    });
}

function generateAllStreams(themeName) {
    const theme = themes[themeName];
    clearStreams();
    textPaths.length = 0;
    
    streamConfigs.forEach((config, index) => {
        const path = createLoxodromePath({ radius: config.radius, turns: config.turns, points: 2000 });
        textPaths.push(path);
        
        const stream = createParticleStream({
            pathPoints: path,
            particleCount: config.count,
            streamWidth: config.width,
            colorFn: (pos, t) => new THREE.Color().setHSL(theme.streamHues[index], 0.9, 0.4 + t * 0.4),
            sizeFn: () => Math.random() * 1.5 + 0.8,
            index: index
        });
        
        activeStreams.push(stream);
    });
    
    setTimeout(() => {
        if (fontLoaded) {
            createAllTextOnPaths();
        }
    }, 500);
}

const themes = {
    celestial: {
        shockwave: "#ADD8E6",
        streamHues: [0.65, 0.6, 0.55, 0.5, 0.7] 
    },
    solar: {
        shockwave: "#FFD700",
        streamHues: [0.05, 0.08, 0.1, 0.12, 0.03] 
    },
    nebula: {
        shockwave: "#DA70D6",
        streamHues: [0.8, 0.75, 0.9, 0.85, 0.7] 
    }
};

// Toggle menú hamburguesa
const menuToggle = document.getElementById('menu-toggle');
const settingsPanel = document.getElementById('settings-panel');

menuToggle.addEventListener('click', () => {
    menuToggle.classList.toggle('active');
    settingsPanel.classList.toggle('active');
});

// Controles
const colorInputs = {
    shockwaveColor: document.getElementById('shockwaveColor'),
    stream1Color: document.getElementById('stream1Color'),
    stream2Color: document.getElementById('stream2Color'),
    stream3Color: document.getElementById('stream3Color'),
    stream4Color: document.getElementById('stream4Color'),
    stream5Color: document.getElementById('stream5Color'),
    textColor: document.getElementById('textColor')
};

const globalBrightness = document.getElementById('globalBrightness');
const bloomIntensity = document.getElementById('bloomIntensity');
const rotationSpeed = document.getElementById('rotationSpeed');

// Aplicar cambios de color
Object.keys(colorInputs).forEach(key => {
    colorInputs[key].addEventListener('input', updateColors);
});

function updateColors() {
    sharedUniforms.uShockwaveColor.value.set(colorInputs.shockwaveColor.value);
    if (activeStreams.length > 0) {
        generateAllStreams(currentThemeName);
    }
    textMeshes.forEach(mesh => {
        mesh.material.color.set(colorInputs.textColor.value);
    });
}

// Brillo global (simulado con intensidad de bloom y renderer)
globalBrightness.addEventListener('input', function() {
    renderer.toneMappingExposure = parseFloat(this.value);
});

// Intensidad bloom
bloomIntensity.addEventListener('input', function() {
    bloomPass.strength = parseFloat(this.value);
});

// Velocidad orbital
rotationSpeed.addEventListener('input', function() {
    controls.autoRotateSpeed = parseFloat(this.value) * 0.5;
});

// Click para shockwave
window.addEventListener('click', (event) => {
    if (event.target.closest('#menu-toggle') || event.target.closest('#settings-panel')) {
        return;
    }
    sharedUniforms.uClickTime.value = clock.getElapsedTime();
});

// Animación
function animate() {
    requestAnimationFrame(animate);
    const elapsedTime = clock.getElapsedTime();
    sharedUniforms.uTime.value = elapsedTime;
    
    textMeshes.forEach(mesh => {
        mesh.lookAt(camera.position);
        mesh.rotateY(0.002);
    });
    
    controls.update();
    composer.render();
}

// Resize
window.addEventListener('resize', () => {
    camera.aspect = window.innerWidth / window.innerHeight;
    camera.updateProjectionMatrix();
    renderer.setSize(window.innerWidth, window.innerHeight);
    composer.setSize(window.innerWidth, window.innerHeight);
});

// Inicializar
generateAllStreams(currentThemeName);
animate();
</script>
