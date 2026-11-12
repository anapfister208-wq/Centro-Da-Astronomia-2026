```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Centro da Astronomia — Exploração &amp; Academia Cósmica</title>
    <!-- ... existing code ... -->
            <!-- Título Principal em Branco Puro logo abaixo do Globo Terrestre -->
            <h1 class="font-nasa text-3xl sm:text-5xl font-black tracking-[0.22em] text-white uppercase leading-tight drop-shadow-[0_0_24px_rgba(255,255,255,0.25)]">
                CENTRO DA<br>ASTRONOMIA
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
                Bem-vindo ao <strong class="text-white font-semibold">Centro da Astronomia</strong> — Explore o cosmos, desvende os mistérios do espaço e mergulhe no infinito.
            </p>

            <!-- Botão Principal de Login -->
            <button 
                id="open-email-picker-btn" 
                type="button"
                class="group relative bg-[#0B3D91] hover:bg-blue-700 active:scale-[0.98] text-white font-nasa font-bold text-xs sm:text-sm tracking-[0.18em] uppercase py-4 px-8 rounded-2xl border border-blue-400/40 shadow-[0_0_35px_rgba(11,61,145,0.75)] transition flex items-center justify-center gap-3.5 cursor-pointer"
            >
<!-- ... existing code ... -->
            <p class="text-xs text-gray-400 mt-3 mb-4">
                Selecione seu e-mail para prosseguir para o <strong class="text-gray-200">Centro da Astronomia</strong>:
            </p>

            <!-- Lista de Contas Rápidas -->
            <div id="saved-accounts-list" class="space-y-2 mb-4">
<!-- ... existing code ... -->
            <div class="space-glass px-3.5 py-2 rounded-xl hidden sm:block">
                <div class="flex items-center gap-2">
                    <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span>
                    <span class="font-nasa text-xs font-bold tracking-widest text-white">CENTRO DA ASTRONOMIA</span>
                </div>
                <p id="hud-user-display" class="font-mono-tech text-[11px] text-blue-300 mt-0.5 truncate max-w-[220px]">EXPLORADOR: CONVIDADO</p>
            </div>
        </div>
<!-- ... existing code ... -->
        <!-- Rodapé do Menu -->
        <div class="mt-8 pt-4 border-t border-white/10 text-[11px] font-mono-tech text-gray-400 space-y-2">
            <div id="drawer-account-email" class="text-blue-300 truncate">Conta: explorador@astronomia.com</div>
            <div>Fale Conosco: <a href="mailto:anapfister208@gmail.com" class="text-gray-300 hover:underline">anapfister208@gmail.com</a></div>
            <button id="logout-btn" class="text-red-400 hover:text-red-300 text-xs underline cursor-pointer">Trocar Conta / Sair</button>
        </div>
    </aside>
<!-- ... existing code ... -->
```                                    
