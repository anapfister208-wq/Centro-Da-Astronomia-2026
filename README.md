# Centro-Da-Astronomia-2026
```html
        <!-- Centro: Logo Planeta Terra (Azul, Verde e Branco) + Título Branco + Boas-vindas + Botão de Login -->
        <div class="relative z-10 w-full max-w-xl flex flex-col items-center text-center my-auto px-2">
            
            <!-- Logo Planeta Terra em suas cores originais (Oceanos Azuis, Continentes Verdes e Nuvens Brancas) -->
            <div class="mb-5 relative flex items-center justify-center">
                <!-- Halo atmosférico suave ao redor da Terra -->
                <div class="absolute w-28 h-28 sm:w-32 sm:h-32 rounded-full bg-sky-400/20 blur-xl pointer-events-none"></div>
                
                <svg class="relative w-28 h-28 sm:w-32 sm:h-32 drop-shadow-[0_0_24px_rgba(56,189,248,0.45)]" viewBox="0 0 140 140" fill="none" xmlns="http://www.w3.org/2000/svg" aria-label="Logo Planeta Terra">
                    <defs>
                        <!-- Gradiente dos Oceanos (Azul profundo a azul vibrante) -->
                        <radialGradient id="earthOceanGrad" cx="38%" cy="32%" r="68%">
                            <stop offset="0%" stop-color="#38BDF8"/>
                            <stop offset="45%" stop-color="#0284C7"/>
                            <stop offset="85%" stop-color="#0369A1"/>
                            <stop offset="100%" stop-color="#0C2D57"/>
                        </radialGradient>

                        <!-- Gradiente dos Continentes (Tons de verde natural) -->
                        <linearGradient id="earthLandGrad" x1="20%" y1="15%" x2="80%" y2="85%">
                            <stop offset="0%" stop-color="#4ADE80"/>
                            <stop offset="50%" stop-color="#16A34A"/>
                            <stop offset="100%" stop-color="#14532D"/>
                        </linearGradient>

                        <!-- Sombra esférica 3D para dar volume ao globo -->
                        <radialGradient id="earthShadowGrad" cx="32%" cy="28%" r="72%">
                            <stop offset="55%" stop-color="rgba(0,0,0,0)"/>
                            <stop offset="85%" stop-color="rgba(2,6,23,0.45)"/>
                            <stop offset="100%" stop-color="rgba(2,6,23,0.85)"/>
                        </radialGradient>

                        <!-- Brilho atmosférico na borda -->
                        <radialGradient id="earthAtmoRim" cx="50%" cy="50%" r="50%">
                            <stop offset="84%" stop-color="rgba(125,211,252,0)"/>
                            <stop offset="96%" stop-color="rgba(125,211,252,0.55)"/>
                            <stop offset="100%" stop-color="rgba(255,255,255,0.85)"/>
                        </radialGradient>

                        <!-- Recorte circular perfeito do globo -->
                        <clipPath id="earthGlobeClip">
                            <circle cx="70" cy="70" r="54"/>
                        </clipPath>
                    </defs>

                    <!-- Anel sutil de atmosfera externa -->
                    <circle cx="70" cy="70" r="57" stroke="rgba(125, 211, 252, 0.28)" stroke-width="1.5"/>

                    <!-- Interior do Globo Terrestre -->
                    <g clip-path="url(#earthGlobeClip)">
                        <!-- Base Oceânica Azul -->
                        <circle cx="70" cy="70" r="54" fill="url(#earthOceanGrad)"/>

                        <!-- Continentes Verdes (Américas, África/Europa estilizadas e ilhas) -->
                        <path d="M26 36 C34 28, 48 27, 55 34 C60 39, 56 48, 50 53 C46 57, 45 62, 51 66 C58 70, 65 76, 61 88 C58 97, 50 109, 43 113 C38 115, 35 106, 37 97 C39 87, 34 79, 27 72 C20 65, 18 44, 26 36 Z" fill="url(#earthLandGrad)"/>
                        <path d="M76 26 C87 23, 102 28, 110 38 C116 46, 114 58, 106 63 C99 67, 96 73, 101 81 C105 89, 100 101, 91 105 C83 108, 77 99, 77 89 C77 79, 71 72, 71 62 C71 52, 67 45, 72 36 C74 32, 73 27, 76 26 Z" fill="url(#earthLandGrad)"/>
                        <!-- Ilha / Groenlândia e detalhes verdes -->
                        <path d="M56 18 C62 16, 70 18, 72 22 C73 25, 66 28, 60 27 C55 26, 53 20, 56 18 Z" fill="#4ADE80" opacity="0.9"/>
                        <path d="M106 86 C112 84, 119 88, 118 94 C117 99, 109 101, 105 97 C102 93, 102 88, 106 86 Z" fill="#22C55E" opacity="0.9"/>

                        <!-- Calotas Polares Brancas (Norte e Sul) -->
                        <path d="M35 16 Q70 25 105 16 L105 10 L35 10 Z" fill="#FFFFFF" opacity="0.88"/>
                        <path d="M42 122 Q70 114 98 122 L98 130 L42 130 Z" fill="#FFFFFF" opacity="0.85"/>

                        <!-- Massas de Nuvens Brancas Suaves -->
                        <g fill="#FFFFFF" opacity="0.82">
                            <rect x="22" y="44" width="34" height="5.5" rx="2.75"/>
                            <rect x="34" y="51" width="22" height="4" rx="2" opacity="0.7"/>
        <!-- Centro: Globo Terrestre 3D Realista (Como Globo de Mesa) + Título Branco + Boas-vindas + Botão de Login -->
        <div class="relative z-10 w-full max-w-xl flex flex-col items-center text-center my-auto px-2">
            
            <!-- Globo Terrestre 3D Realista (Oceanos azuis, continentes reais e calotas polares de neve) -->
            <div class="mb-4 relative flex items-center justify-center group" title="Arraste para girar o Globo Terrestre">
                <!-- Halo atmosférico realista ao redor do globo -->
                <div class="absolute w-32 h-32 sm:w-36 sm:h-36 rounded-full bg-sky-400/25 blur-xl pointer-events-none"></div>
                <div class="absolute w-[132px] h-[132px] sm:w-[152px] sm:h-[152px] rounded-full border border-sky-300/25 shadow-[inset_0_0_22px_rgba(56,189,248,0.45),0_0_28px_rgba(14,165,233,0.35)] pointer-events-none"></div>
                
                <canvas 
                    id="login-earth-globe" 
                    class="relative w-32 h-32 sm:w-36 sm:h-36 rounded-full cursor-grab active:cursor-grabbing drop-shadow-[0_12px_28px_rgba(0,0,0,0.9)]"
                    aria-label="Globo Terrestre 3D Realista"
                ></canvas>
            </div>

            <!-- Título Principal em Branco Puro logo abaixo do Globo Terrestre -->
            <h1 class="font-nasa text-3xl sm:text-5xl font-black tracking-[0.22em] text-white uppercase leading-tight drop-shadow-[0_0_24px_rgba(255,255,255,0.25)]">
                CENTRAL DO<br>UNIVERSO
            </h1>
            
            <div class="flex items-center gap-3 mt-3 mb-5">
                <span class="h-[1px] w-8 bg-sky-400"></span>
                <p class="font-mono-tech text-[11px] sm:text-xs tracking-[0.26em] text-blue-300 uppercase">
                    Exploração &amp; Academia Cósmica
                </p>
                <span class="h-[1px] w-8 bg-sky-400"></span>
            </div>

            <!-- Mensagem de Boas-Vindas -->
            <p class="text-sm sm:text-base text-gray-300 max-w-md leading-relaxed mb-8 font-light">
                Bem-vindo à <strong class="text-white font-semibold">Central do Universo</strong> — Explore o cosmos, desvende os mistérios do espaço e mergulhe no infinito.
            </p>

            <!-- Botão Principal de Login -->
            <button 
                id="open-email-picker-btn" 
                type="button"
                class="group relative bg-[#0B3D91] hover:bg-blue-700 active:scale-[0.98] text-white font-nasa font-bold text-xs sm:text-sm tracking-[0.18em] uppercase py-4 px-8 rounded-2xl border border-blue-400/40 shadow-[0_0_35px_rgba(11,61,145,0.75)] transition flex items-center justify-center gap-3.5 cursor-pointer"
            >
                <svg class="w-5 h-5 text-blue-200 group-hover:text-white transition" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/>
                </svg>
                <span>Entrar com E-mail</span>
                <svg class="w-4 h-4 transform group-hover:translate-x-1 transition" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7l5 5m0 0l-5 5m5-5H6"/>
                </svg>
            </button>

            <span class="mt-3.5 font-mono-tech text-[10px] text-gray-500 uppercase tracking-widest">
                Modo Tela Cheia Horizontal (Paisagem) Automático
            </span>
        </div>

        <!-- Rodapé Discreto -->
        <div class="relative z-10 w-full max-w-6xl flex flex-col sm:flex-row justify-between items-center gap-2 text-[11px] font-mono-tech text-gray-500 pt-3 border-t border-white/10">
            <span>SISTEMA DE SIMULAÇÃO ASTRONÔMICA INTERATIVA</span>
            <a href="mailto:anapfister208@gmail.com" class="hover:text-gray-300 transition">Fale Conosco: anapfister208@gmail.com</a>
        </div>
    </div>

    <!-- ==========================================
         MODAL SELETOR DE CONTA / E-MAIL (ESTILO GOOGLE)
         ========================================== -->
    <div id="email-picker-modal" class="fixed inset-0 z-50 bg-black/80 backdrop-blur-md hidden items-center justify-center p-4">
        <div class="w-full max-w-md space-glass nasa-badge-border rounded-2xl p-6 sm:p-7 text-left shadow-2xl border border-white/15">
            <div class="flex items-center justify-between pb-4 border-b border-white/10">
                <div class="flex items-center gap-2.5">
                    <span class="w-2.5 h-2.5 rounded-full bg-[#0B3D91] ring-2 ring-blue-400"></span>
                    <h2 class="font-nasa text-sm sm:text-base font-bold tracking-wider text-white uppercase">Escolher uma conta</h2>
                </div>
                <button id="close-email-picker-btn" type="button" class="w-8 h-8 rounded-lg bg-white/5 hover:bg-white/15 text-gray-400 hover:text-white flex items-center justify-center transition cursor-pointer">
                    ✕
                </button>
            </div>

            <p class="text-xs text-gray-400 mt-3 mb-4">
                Selecione seu e-mail para prosseguir para a <strong class="text-gray-200">Central do Universo</strong>:
            </p>

            <!-- Lista de Contas Rápidas -->
            <div id="saved-accounts-list" class="space-y-2 mb-4">
                <!-- Preenchido dinamicamente via JS -->
            </div>

            <!-- Divisor -->
            <div class="relative my-4 flex items-center justify-center">
                <div class="border-t border-white/10 w-full"></div>
                <span class="bg-[#0b101d] px-3 text-[10px] font-mono-tech text-gray-400 uppercase tracking-widest">ou digite seu e-mail</span>
                <div class="border-t border-white/10 w-full"></div>
            </div>

            <!-- Formulário para Usar Outro E-mail -->
            <form id="custom-email-form" class="space-y-3">
                <div>
                    <input 
                        type="email" 
                        id="custom-email-input" 
                        placeholder="seu.email@gmail.com" 
                        required
                        class="w-full bg-black/75 border border-white/20 focus:border-blue-500 rounded-xl px-4 py-3 text-sm text-white placeholder-gray-500 outline-none transition"
                    >
                </div>
                <button 
                    type="submit" 
                    class="w-full bg-[#0B3D91] hover:bg-blue-700 active:scale-[0.99] text-white font-nasa font-bold text-xs tracking-[0.18em] uppercase py-3.5 px-5 rounded-xl border border-blue-400/30 transition flex items-center justify-center gap-2 cursor-pointer"
                >
                    <span>Continuar com este E-mail</span>
                    <span>→</span>
                </button>
            </form>
        </div>
    </div>

    <!-- ==========================================
         VIEWPORT DO JOGO (FORÇA TELA DE LADO / PAISAGEM)
         ========================================== -->
    <div id="game-viewport">

    <!-- ==========================================
         2. PALCO 3D PRINCIPAL (THREE.JS)
         ========================================== -->
    <canvas id="universe-canvas"></canvas>

    <!-- ==========================================
         3. HUD SUPERIOR E CONTROLES DA MISSÃO
         ========================================== -->
    <header id="main-hud" class="absolute top-0 left-0 right-0 z-30 p-3 sm:p-5 flex items-start justify-between pointer-events-none opacity-0 fade-transition">
        
        <!-- Esquerda: Botão Menu 3 Riscos (☰) + Identificação -->
        <div class="flex items-center gap-3 pointer-events-auto">
            <button 
                id="menu-toggle-btn" 
                aria-label="Abrir Menu"
                class="space-glass hover:bg-white/10 active:scale-95 w-11 h-11 sm:w-12 sm:h-12 rounded-xl flex flex-col items-center justify-center gap-1.5 border border-white/20 transition cursor-pointer group"
            >
                <span class="w-5 h-0.5 bg-white group-hover:bg-[#FC3D21] transition"></span>
                <span class="w-5 h-0.5 bg-white transition"></span>
                <span class="w-5 h-0.5 bg-white group-hover:bg-blue-400 transition"></span>
            </button>

            <div class="space-glass px-3.5 py-2 rounded-xl hidden sm:block">
                <div class="flex items-center gap-2">
                    <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span>
                    <span class="font-nasa text-xs font-bold tracking-widest text-white">CENTRAL DO UNIVERSO</span>
                </div>
                <p id="hud-user-display" class="font-mono-tech text-[11px] text-blue-300 mt-0.5 truncate max-w-[220px]">EXPLORADOR: CONVIDADO</p>
            </div>
        </div>

        <!-- Centro: Contador de Descobertas & Escala de Zoom -->
        <div class="flex flex-col items-center gap-1.5 pointer-events-auto">
            <div class="space-glass px-4 py-2 rounded-full flex items-center gap-3 border border-white/15">
                <div class="flex items-center gap-2">
                    <svg class="w-4 h-4 text-[#FC3D21]" fill="currentColor" viewBox="0 0 20 20">
                        <path d="M10 2a8 8 0 100 16 8 8 0 000-16zm1 11H9v-2h2v2zm0-4H9V5h2v4z"/>
                    </svg>
                    <span class="font-mono-tech text-xs text-gray-200">
                        Descobertos: <strong id="discovery-counter" class="text-white font-bold">1/9</strong>
                    </span>
                </div>
                <span class="text-white/20 hidden md:inline">|</span>
                <span id="zoom-scale-label" class="font-mono-tech text-[11px] text-blue-300 hidden md:inline">ÓRBITA TERRESTRE</span>
            </div>

            <!-- Barra de Dica Rápida -->
            <div id="explore-hint" class="bg-black/60 backdrop-blur-md px-3 py-1 rounded-full border border-white/10 text-[10px] sm:text-[11px] text-gray-300 font-mono-tech text-center hidden sm:block">
                Arraste para girar • Afaste o zoom até a Via Láctea • Clique nos astros
            </div>
        </div>

        <!-- Direita: Zoom +/-, Foco na Terra, Áudio & Tela Cheia -->
        <div class="flex items-center gap-1.5 sm:gap-2 pointer-events-auto">
            <div class="space-glass rounded-xl flex items-center border border-white/15 overflow-hidden">
                <button id="zoom-in-btn" title="Aproximar Zoom" class="hover:bg-white/15 px-2.5 py-2.5 text-xs font-mono-tech font-bold text-white transition cursor-pointer">+</button>
                <span class="w-[1px] h-4 bg-white/15"></span>
                <button id="zoom-out-btn" title="Afastar Zoom" class="hover:bg-white/15 px-2.5 py-2.5 text-xs font-mono-tech font-bold text-white transition cursor-pointer">−</button>
            </div>

            <button 
                id="focus-earth-btn" 
                title="Voltar para a Terra"
                class="space-glass hover:bg-white/10 px-3 py-2.5 rounded-xl text-xs font-mono-tech text-blue-300 flex items-center gap-1.5 transition cursor-pointer"
            >
                <span>🌍</span>
                <span class="hidden lg:inline">TERRA</span>
            </button>

            <button 
                id="quick-audio-btn" 
                title="Ativar/Pausar Trilha Espacial"
                class="space-glass hover:bg-white/10 px-3 py-2.5 rounded-xl text-xs font-mono-tech text-gray-300 flex items-center gap-1.5 transition cursor-pointer"
            >
                <span id="quick-audio-icon">🔇</span>
                <span class="hidden lg:inline" id="quick-audio-text">SOM OFF</span>
            </button>

            <button 
                id="fullscreen-toggle-btn" 
                title="Alternar Tela Cheia / Modo Paisagem"
                class="space-glass hover:bg-white/10 px-3 py-2.5 rounded-xl text-xs font-mono-tech text-gray-200 flex items-center gap-1.5 transition cursor-pointer"
            >
                <span>⛶</span>
            </button>
        </div>
    </header>

    <!-- ==========================================
         4. CARTÃO FLUTUANTE DE DESCOBERTA DE PLANETA
         ========================================== -->
    <div id="planet-info-card" class="absolute bottom-4 left-1/2 -translate-x-1/2 z-30 w-[92%] max-w-lg space-glass rounded-2xl p-4 sm:p-5 border border-blue-400/30 hidden fade-transition">
<!-- ... existing code ... -->
    <!-- ==========================================
         5. MENU LATERAL (GAVETA DOS 3 RISCOS ☰)
         ========================================== -->
    <div id="drawer-backdrop" class="absolute inset-0 bg-black/70 backdrop-blur-sm z-40 hidden opacity-0 transition-opacity duration-300"></div>

    <aside id="side-drawer" class="absolute top-0 left-0 bottom-0 w-[85%] max-w-sm space-glass z-50 border-r border-white/15 transform -translate-x-full transition-transform duration-300 flex flex-col justify-between p-5 overflow-y-auto">
<!-- ... existing code ... -->
        <!-- Rodapé do Menu -->
        <div class="mt-8 pt-4 border-t border-white/10 text-[11px] font-mono-tech text-gray-400 space-y-2">
            <div id="drawer-account-email" class="text-blue-300 truncate">Conta: explorador@universo.com</div>
            <div>Fale Conosco: <a href="mailto:anapfister208@gmail.com" class="text-gray-300 hover:underline">anapfister208@gmail.com</a></div>
            <button id="logout-btn" class="text-red-400 hover:text-red-300 text-xs underline cursor-pointer">Trocar Conta / Sair</button>
        </div>
    </aside>

    <!-- ==========================================
         6. SALA DE AULA 3D (INÍCIO, MEIO E FIM)
         ========================================== -->
    <section id="classroom-modal" class="absolute inset-0 z-40 bg-black/92 backdrop-blur-xl hidden flex-col overflow-hidden">
<!-- ... existing code ... -->
        </div>
    </section>

    </div><!-- Fim de #game-viewport -->

    <!-- ==========================================
         SCRIPT PRINCIPAL: 3D, ÁUDIO E LÓGICA
         ========================================== -->
<!-- ... existing code ... -->
        // Responsividade ao redimensionar tela
        function updateGameViewportSize() {
            const viewport = document.getElementById('game-viewport');
            const isForced = viewport.classList.contains('forced-landscape');
            const w = isForced ? window.innerHeight : window.innerWidth;
            const h = isForced ? window.innerWidth : window.innerHeight;

            camera.aspect = w / h;
            camera.updateProjectionMatrix();
            renderer.setSize(w, h);
            resizeClassroomCanvas();
        }

        window.addEventListener('resize', () => {
            if (!loginScreen.classList.contains('hidden')) return;
            applyLandscapeOrientation();
            updateGameViewportSize();
        });

        /* ============================================================
           6. SELETOR DE E-MAIL, MODO PAISAGEM E NAVEGAÇÃO
           ============================================================ */
        const loginScreen = document.getElementById('login-screen');
        const emailPickerModal = document.getElementById('email-picker-modal');
        const gameViewport = document.getElementById('game-viewport');
        const mainHud = document.getElementById('main-hud');
        const sideDrawer = document.getElementById('side-drawer');
        const drawerBackdrop = document.getElementById('drawer-backdrop');
        const classroomModal = document.getElementById('classroom-modal');

        // Contas sugeridas + contas usadas anteriormente na sessão
        const defaultAccounts = [
            { name: 'Comandante Ana', email: 'anapfister208@gmail.com', avatar: 'A' },
            { name: 'Explorador Orbital', email: 'explorador.nasa@gmail.com', avatar: 'E' },
            { name: 'Viajante Cósmico', email: 'viajante.cosmos@outlook.com', avatar: 'V' }
        ];
        let sessionAccounts = [...defaultAccounts];

        function renderAccountList() {
            const container = document.getElementById('saved-accounts-list');
            container.innerHTML = sessionAccounts.map(acc => `
                <button type="button" onclick="completeLoginWithEmail('${acc.email}')" class="w-full p-3 rounded-xl bg-white/5 hover:bg-blue-600/20 border border-white/10 hover:border-blue-400/50 flex items-center gap-3 text-left transition cursor-pointer group">
                    <div class="w-9 h-9 rounded-full bg-[#0B3D91] border border-blue-400/40 flex items-center justify-center font-nasa font-bold text-xs text-white shrink-0">
                        ${acc.avatar}
                    </div>
                    <div class="min-w-0 flex-1">
                        <div class="text-xs font-semibold text-white group-hover:text-blue-200 truncate">${acc.name}</div>
                        <div class="font-mono-tech text-[11px] text-gray-400 truncate">${acc.email}</div>
                    </div>
                    <span class="text-xs text-gray-500 group-hover:text-white transition">→</span>
                </button>
            `).join('');
        }

        // Ativa Tela Cheia + Orientação Paisagem (de lado como um jogo)
        async function applyLandscapeOrientation() {
            const isPortrait = window.innerHeight > window.innerWidth;

            try {
                if (document.documentElement.requestFullscreen && !document.fullscreenElement) {
                    await document.documentElement.requestFullscreen();
                }
            } catch (err) {
                // Fullscreen pode ser bloqueado em iframes, segue com fallback
            }

            let nativeLocked = false;
            try {
                if (screen.orientation && screen.orientation.lock) {
                    await screen.orientation.lock('landscape');
                    nativeLocked = true;
                }
            } catch (err) {
                nativeLocked = false;
            }

            // Se o dispositivo continuar em retrato (desktop estreito ou iOS Safari), aplica rotação CSS de 90°
            if (!nativeLocked && window.innerHeight > window.innerWidth) {
                gameViewport.classList.add('forced-landscape');
            } else {
                gameViewport.classList.remove('forced-landscape');
            }

            updateGameViewportSize();
        }

        // Abrir e fechar modal de escolha de e-mail
        document.getElementById('open-email-picker-btn').addEventListener('click', () => {
            renderAccountList();
            emailPickerModal.classList.remove('hidden');
            emailPickerModal.classList.add('flex');
        });

        document.getElementById('close-email-picker-btn').addEventListener('click', () => {
            emailPickerModal.classList.add('hidden');
            emailPickerModal.classList.remove('flex');
        });

        // Finaliza login imediatamente com o e-mail escolhido
        window.completeLoginWithEmail = async function(email) {
            const cleanEmail = (email || '').trim().toLowerCase();
            if (!cleanEmail) return;

            // Adiciona à lista rápida se for um novo e-mail
            if (!sessionAccounts.some(a => a.email === cleanEmail)) {
                const namePart = cleanEmail.split('@')[0];
                const formattedName = namePart.charAt(0).toUpperCase() + namePart.slice(1);
                sessionAccounts.unshift({
                    name: formattedName,
                    email: cleanEmail,
                    avatar: formattedName.charAt(0).toUpperCase()
                });
            }

            // Atualiza HUD e Menu com o e-mail logado
            document.getElementById('hud-user-display').textContent = cleanEmail;
            document.getElementById('drawer-account-email').textContent = `Conta: ${cleanEmail}`;

            // Fecha modal e tela inicial
            emailPickerModal.classList.add('hidden');
            emailPickerModal.classList.remove('flex');

            loginScreen.style.opacity = '0';
            loginScreen.style.pointerEvents = 'none';
            setTimeout(() => {
                loginScreen.classList.add('hidden');
            }, 500);

            // Vira a tela de lado (paisagem) e entra direto no 3D
            await applyLandscapeOrientation();
            mainHud.classList.remove('opacity-0');
            focusOnBody('terra', true);
            updateDiscoveryUI();
        };

        document.getElementById('custom-email-form').addEventListener('submit', (e) => {
            e.preventDefault();
            const emailVal = document.getElementById('custom-email-input').value;
            completeLoginWithEmail(emailVal);
        });

        // Botões de Zoom +/- e Tela Cheia no HUD
        document.getElementById('zoom-in-btn').addEventListener('click', () => {
            const dir = new THREE.Vector3().subVectors(camera.position, controls.target);
            dir.multiplyScalar(0.75);
            if (dir.length() >= controls.minDistance) {
                camera.position.copy(controls.target).add(dir);
            }
        });

        document.getElementById('zoom-out-btn').addEventListener('click', () => {
            const dir = new THREE.Vector3().subVectors(camera.position, controls.target);
            dir.multiplyScalar(1.35);
            if (dir.length() <= controls.maxDistance) {
                camera.position.copy(controls.target).add(dir);
            }
        });

        document.getElementById('fullscreen-toggle-btn').addEventListener('click', async () => {
            if (!document.fullscreenElement) {
                await applyLandscapeOrientation();
            } else {
                try {
                    await document.exitFullscreen();
                } catch (e) {}
                gameViewport.classList.remove('forced-landscape');
                updateGameViewportSize();
            }
        });

        // Abrir / Fechar Menu Lateral (3 Riscos ☰)
        function openDrawer() {
            drawerBackdrop.classList.remove('hidden');
            requestAnimationFrame(() => {
                drawerBackdrop.style.opacity = '1';
                sideDrawer.style.transform = 'translateX(0)';
            });
        }

        function closeDrawer() {
            drawerBackdrop.style.opacity = '0';
            sideDrawer.style.transform = 'translateX(-100%)';
            setTimeout(() => {
                drawerBackdrop.classList.add('hidden');
            }, 300);
        }

        document.getElementById('menu-toggle-btn').addEventListener('click', openDrawer);
        document.getElementById('close-drawer-btn').addEventListener('click', closeDrawer);
        drawerBackdrop.addEventListener('click', closeDrawer);

        // Controles de Áudio
        document.getElementById('quick-audio-btn').addEventListener('click', () => audioEngine.toggle());
        document.getElementById('drawer-play-btn').addEventListener('click', () => audioEngine.toggle());
        document.getElementById('volume-slider').addEventListener('input', (e) => audioEngine.setVolume(e.target.value));

        document.querySelectorAll('.track-btn').forEach(btn => {
            btn.addEventListener('click', () => {
                const trackIdx = parseInt(btn.dataset.track, 10);
                audioEngine.playTrack(trackIdx);
            });
        });

        // Botões de Foco na Terra e Planeta Selecionado
        document.getElementById('focus-earth-btn').addEventListener('click', () => {
            focusOnBody('terra', true);
            discoverAndShowBody('terra');
        });

        document.getElementById('focus-selected-btn').addEventListener('click', () => {
            if (selectedBodyId) {
                focusOnBody(selectedBodyId, true);
            }
        });

        document.getElementById('close-card-btn').addEventListener('click', () => {
            document.getElementById('planet-info-card').classList.add('hidden');
        });

        // Sala de Aula 3D
        function openClassroom(initialModule = 'inicio', planetId = 'terra') {
            closeDrawer();
            classroomModal.classList.remove('hidden');
            classroomModal.classList.add('flex');
            setTimeout(() => {
                resizeClassroomCanvas();
                renderClassroomModule(initialModule, planetId);
            }, 30);
        }

        function closeClassroom() {
            classroomModal.classList.add('hidden');
            classroomModal.classList.remove('flex');
        }

        document.getElementById('nav-classroom-btn').addEventListener('click', () => openClassroom('inicio'));
        document.getElementById('nav-explore-btn').addEventListener('click', () => {
            closeClassroom();
            closeDrawer();
        });
        document.getElementById('close-classroom-btn').addEventListener('click', closeClassroom);

        document.getElementById('open-in-classroom-btn').addEventListener('click', () => {
            openClassroom('meio', selectedBodyId || 'terra');
        });

        document.querySelectorAll('.module-tab').forEach(tab => {
            tab.addEventListener('click', () => {
                renderClassroomModule(tab.dataset.module);
            });
        });

        // Encerrar Sessão / Trocar Conta
        document.getElementById('logout-btn').addEventListener('click', async () => {
            closeDrawer();
            closeClassroom();
            if (document.fullscreenElement) {
                try { await document.exitFullscreen(); } catch (e) {}
            }
            gameViewport.classList.remove('forced-landscape');
            loginScreen.classList.remove('hidden');
            requestAnimationFrame(() => {
                loginScreen.style.opacity = '1';
                loginScreen.style.pointerEvents = 'auto';
            });
        });

        /* ============================================================
           7. GLOBO TERRESTRE 3D REALISTA DA TELA INICIAL (THREE.JS)
           ============================================================ */
        function initLoginEarthGlobe() {
            const globeCanvas = document.getElementById('login-earth-globe');
            if (!globeCanvas || typeof THREE === 'undefined') return;

            const size = 320; // Alta definição (Retina / HiDPI)
            const globeScene = new THREE.Scene();

            const globeCamera = new THREE.PerspectiveCamera(36, 1, 0.1, 100);
            globeCamera.position.set(0, 0.18, 3.35);
            globeCamera.lookAt(0, 0, 0);

            const globeRenderer = new THREE.WebGLRenderer({
                canvas: globeCanvas,
                alpha: true,
                antialias: true
            });
            globeRenderer.setSize(size, size, false);
            globeRenderer.setPixelRatio(Math.min(window.devicePixelRatio || 1, 2));

            // Gerador procedural de textura equiretangular realista da Terra (Oceanos, Continentes Reais, Relevo, Neve Polar)
            function createRealisticEarthTextures() {
                const w = 1024;
                const h = 512;

                // 1. Mapa de Cores (Albedo)
                const colorCanvas = document.createElement('canvas');
                colorCanvas.width = w;
                colorCanvas.height = h;
                const ctx = colorCanvas.getContext('2d');

                // Oceano profundo realista com gradiente latitudinal
                const oceanGrad = ctx.createLinearGradient(0, 0, 0, h);
                oceanGrad.addColorStop(0.0, '#0a2540');
                oceanGrad.addColorStop(0.25, '#0b3d75');
                oceanGrad.addColorStop(0.5, '#0e5cad');
                oceanGrad.addColorStop(0.75, '#0b3d75');
                oceanGrad.addColorStop(1.0, '#071d36');
                ctx.fillStyle = oceanGrad;
                ctx.fillRect(0, 0, w, h);

                // Águas costeiras rasas (azul turquesa sutil ao redor dos continentes)
                function drawContinentShape(points, fillStyle, strokeCoast = true) {
                    ctx.save();
                    ctx.beginPath();
                    points.forEach(([px, py], i) => {
                        const x = px * w;
                        const y = py * h;
                        if (i === 0) ctx.moveTo(x, y);
                        else ctx.lineTo(x, y);
                    });
                    ctx.closePath();

                    if (strokeCoast) {
                        ctx.lineJoin = 'round';
                        ctx.lineWidth = 10;
                        ctx.strokeStyle = 'rgba(34, 166, 224, 0.42)';
                        ctx.stroke();
                    }

                    ctx.fillStyle = fillStyle;
                    ctx.fill();
                    ctx.restore();
                }

                // Gradientes naturais para vegetação, planícies e desertos
                const lushGreen = ctx.createLinearGradient(0, h * 0.15, 0, h * 0.85);
                lushGreen.addColorStop(0, '#2e6f40');
                lushGreen.addColorStop(0.45, '#3b873e');
                lushGreen.addColorStop(0.7, '#276636');
                lushGreen.addColorStop(1, '#366844');

                const africaEurasiaGrad = ctx.createLinearGradient(0, h * 0.15, 0, h * 0.85);
                africaEurasiaGrad.addColorStop(0, '#366b47');
                africaEurasiaGrad.addColorStop(0.32, '#487e45');
                africaEurasiaGrad.addColorStop(0.46, '#c8a96e'); // Saara / Oriente Médio
                africaEurasiaGrad.addColorStop(0.62, '#2d7539'); // África Central
                africaEurasiaGrad.addColorStop(0.85, '#598249');
                africaEurasiaGrad.addColorStop(1, '#3a6640');

                // América do Norte
                drawContinentShape([
                    [0.10, 0.18], [0.16, 0.15], [0.24, 0.14], [0.30, 0.18],
                    [0.32, 0.25], [0.29, 0.32], [0.25, 0.38], [0.23, 0.44],
                    [0.26, 0.48], [0.23, 0.49], [0.19, 0.42], [0.16, 0.34],
                    [0.14, 0.26], [0.09, 0.23]
                ], lushGreen);

                // Groenlândia (com cobertura branca de neve/gelo)
                drawContinentShape([
                    [0.33, 0.08], [0.40, 0.07], [0.42, 0.13], [0.37, 0.19], [0.34, 0.15]
                ], '#e6f0f7');

                // América do Sul (Destaque inicial no globo)
                drawContinentShape([
                    [0.26, 0.49], [0.31, 0.51], [0.36, 0.57], [0.35, 0.65],
                    [0.31, 0.74], [0.29, 0.84], [0.27, 0.85], [0.26, 0.72],
                    [0.25, 0.60], [0.24, 0.53]
                ], lushGreen);

                // Europa
                drawContinentShape([
                    [0.46, 0.27], [0.49, 0.19], [0.55, 0.16], [0.60, 0.19],
                    [0.59, 0.27], [0.55, 0.31], [0.48, 0.31]
                ], africaEurasiaGrad);

                // África
                drawContinentShape([
                    [0.46, 0.34], [0.53, 0.33], [0.60, 0.37], [0.63, 0.46],
                    [0.60, 0.56], [0.57, 0.68], [0.53, 0.72], [0.50, 0.62],
                    [0.49, 0.50], [0.44, 0.44]
                ], africaEurasiaGrad);

                // Madagascar
                drawContinentShape([
                    [0.62, 0.61], [0.64, 0.61], [0.63, 0.68], [0.61, 0.67]
                ], '#367c3e');

                // Ásia
                drawContinentShape([
                    [0.60, 0.17], [0.70, 0.14], [0.82, 0.16], [0.90, 0.20],
                    [0.86, 0.29], [0.82, 0.37], [0.77, 0.45], [0.72, 0.46],
                    [0.68, 0.41], [0.63, 0.37], [0.60, 0.28]
                ], africaEurasiaGrad);

                // Japão e Indonésia / Ilhas
                drawContinentShape([[0.86, 0.30], [0.88, 0.29], [0.87, 0.35], [0.85, 0.34]], '#3b873e');
                drawContinentShape([[0.75, 0.50], [0.82, 0.50], [0.84, 0.54], [0.76, 0.54]], '#2d7539');

                // Austrália
                drawContinentShape([
                    [0.80, 0.61], [0.88, 0.60], [0.91, 0.67], [0.87, 0.74],
                    [0.80, 0.72], [0.78, 0.66]
                ], '#b5834b');

                // Nova Zelândia
                drawContinentShape([[0.93, 0.75], [0.95, 0.74], [0.94, 0.80], [0.92, 0.79]], '#3b873e');

                // Detalhes orgânicos de relevo e florestas sobre os continentes
                for (let i = 0; i < 450; i++) {
                    const rx = Math.random() * w;
                    const ry = h * 0.14 + Math.random() * (h * 0.72);
                    const pixel = ctx.getImageData(Math.floor(rx), Math.floor(ry), 1, 1).data;
                    // Aplica textura apenas onde não é azul oceânico predominante
                    if (pixel[1] > pixel[2] * 0.92) {
                        ctx.fillStyle = Math.random() > 0.45 ? 'rgba(26, 77, 36, 0.28)' : 'rgba(186, 152, 92, 0.22)';
                        ctx.beginPath();
                        ctx.ellipse(rx, ry, 4 + Math.random() * 14, 2 + Math.random() * 7, Math.random() * Math.PI, 0, Math.PI * 2);
                        ctx.fill();
                    }
                }

                // Calotas Polares de Neve Realistas (Polo Norte Ártico e Polo Sul Antártida)
                ctx.fillStyle = '#f8fafc';
                // Polo Norte (borda irregular de gelo e neve)
                ctx.beginPath();
                ctx.moveTo(0, 0);
                ctx.lineTo(w, 0);
                ctx.lineTo(w, h * 0.065);
                for (let x = w; x >= 0; x -= 16) {
                    const wave = Math.sin(x * 0.025) * 6 + Math.cos(x * 0.06) * 4;
                    ctx.lineTo(x, h * 0.065 + wave);
                }
                ctx.closePath();
                ctx.fill();

                // Polo Sul (Antártida coberta de neve)
                ctx.beginPath();
                ctx.moveTo(0, h);
                ctx.lineTo(w, h);
                ctx.lineTo(w, h * 0.89);
                for (let x = w; x >= 0; x -= 16) {
                    const wave = Math.cos(x * 0.022) * 7 + Math.sin(x * 0.055) * 4;
                    ctx.lineTo(x, h * 0.89 + wave);
                }
                ctx.closePath();
                ctx.fill();

                return new THREE.CanvasTexture(colorCanvas);
            }

            const earthTex = createRealisticEarthTextures();

            // Grupo principal com inclinação axial real da Terra (~23.5 graus como um globo de mesa)
            const globeGroup = new THREE.Group();
            globeGroup.rotation.z = THREE.MathUtils.degToRad(23.5);
            globeScene.add(globeGroup);

            // Esfera da Terra nítida (como globo físico de mesa, sem nuvens) com brilho especular nos oceanos
            const earthGeo = new THREE.SphereGeometry(1, 64, 64);
            const earthMat = new THREE.MeshPhongMaterial({
                map: earthTex,
                specular: new THREE.Color(0x3b82f6),
                shininess: 22
            });
            const earthMesh = new THREE.Mesh(earthGeo, earthMat);
            // Inicia mostrando as Américas e o Atlântico
            earthMesh.rotation.y = -1.25;
            globeGroup.add(earthMesh);

            // Halo atmosférico externo (Fresnel suave)
            const atmoGeo = new THREE.SphereGeometry(1.06, 48, 48);
            const atmoMat = new THREE.MeshBasicMaterial({
                color: 0x38bdf8,
                transparent: true,
                opacity: 0.14,
                side: THREE.BackSide
            });
            const atmoMesh = new THREE.Mesh(atmoGeo, atmoMat);
            globeGroup.add(atmoMesh);

            // Iluminação solar realista + luz ambiente suave do espaço
            const ambientLight = new THREE.AmbientLight(0x334155, 1.15);
            globeScene.add(ambientLight);

            const sunLight = new THREE.DirectionalLight(0xffffff, 1.85);
            sunLight.position.set(4, 2.2, 4.5);
            globeScene.add(sunLight);

            const rimLight = new THREE.DirectionalLight(0x38bdf8, 0.55);
            rimLight.position.set(-4, -1.5, -2.5);
            globeScene.add(rimLight);

            // Interatividade: usuário pode girar o globo com o mouse ou dedo
            let isDragging = false;
            let prevX = 0;
            let prevY = 0;
            let velX = 0.0038;
            let velY = 0;

            globeCanvas.addEventListener('pointerdown', (e) => {
                isDragging = true;
                prevX = e.clientX;
                prevY = e.clientY;
            });

            window.addEventListener('pointermove', (e) => {
                if (!isDragging) return;
                const dx = e.clientX - prevX;
                const dy = e.clientY - prevY;
                prevX = e.clientX;
                prevY = e.clientY;

                velX = dx * 0.008;
                velY = dy * 0.006;
                earthMesh.rotation.y += velX;
                globeGroup.rotation.x = THREE.MathUtils.clamp(globeGroup.rotation.x + velY, -0.65, 0.65);
            });

            window.addEventListener('pointerup', () => {
                isDragging = false;
            });

            // Loop de animação do globo (pausa automaticamente quando sai da tela inicial)
            function animateLoginGlobe() {
                requestAnimationFrame(animateLoginGlobe);
                if (loginScreen.classList.contains('hidden')) return;

                if (!isDragging) {
                    // Desacelera suavemente até a rotação natural contínua da Terra
                    velX += (0.0038 - velX) * 0.04;
                    earthMesh.rotation.y += velX;
                }

                globeRenderer.render(globeScene, globeCamera);
            }

            animateLoginGlobe();
        }

        // Inicializa animações no carregamento
        window.onload = function () {
            initLoginEarthGlobe();
            focusOnBody('terra', true);
            animateUniverse();
            animateClassroom();
        };
    </script>
</body>
</html>
```
