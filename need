<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jonim Rayhona, meni kechirasanmi? 🥺❤️</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Canvas Confetti -->
    <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.6.0/dist/confetti.browser.min.js"></script>
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Caveat:wght@600;700&family=Nunito:wght@400;600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'rose-soft': '#fff0f3',
                        'rose-card': '#fff0f5',
                        'romantic-pink': '#ff758f',
                        'romantic-red': '#ff4d6d',
                        'deep-rose': '#c9184a',
                    },
                    fontFamily: {
                        sans: ['Nunito', 'sans-serif'],
                        handwriting: ['Caveat', 'cursive'],
                    }
                }
            }
        }
    </script>

    <style>
        /* Floating background hearts */
        @keyframes floatHeart {
            0% {
                transform: translateY(100vh) scale(0.5) rotate(0deg);
                opacity: 0;
            }
            20% {
                opacity: 0.85;
            }
            100% {
                transform: translateY(-10vh) scale(1.2) rotate(360deg);
                opacity: 0;
            }
        }

        .bg-heart {
            position: absolute;
            color: rgba(255, 117, 143, 0.4);
            user-select: none;
            pointer-events: none;
            animation: floatHeart 8s linear infinite;
        }

        /* Gentle Heartbeat Pulse */
        @keyframes heartbeat {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.12); }
        }

        .pulse-heart {
            animation: heartbeat 1.5s infinite ease-in-out;
        }

        /* Flip Card Effect */
        .perspective-1000 {
            perspective: 1000px;
        }
        .transform-style-3d {
            transform-style: preserve-3d;
            transition: transform 0.6s cubic-bezier(0.4, 0, 0.2, 1);
        }
        .backface-hidden {
            backface-visibility: hidden;
        }
        .rotate-y-180 {
            transform: rotateY(180deg);
        }

        /* Glassmorphism */
        .glass-card {
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(14px);
            border: 1px solid rgba(255, 182, 193, 0.5);
            box-shadow: 0 20px 40px rgba(255, 117, 143, 0.18);
        }

        /* Custom Scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #fff0f3;
        }
        ::-webkit-scrollbar-thumb {
            background: #ff758f;
            border-radius: 4px;
        }
    </style>
</head>
<body class="bg-gradient-to-br from-rose-100 via-pink-100 to-red-100 min-h-screen flex items-center justify-center p-4 font-sans relative overflow-x-hidden select-none">

    <!-- Floating Background Hearts Container -->
    <div id="heartsContainer" class="fixed inset-0 overflow-hidden pointer-events-none z-0"></div>

    <!-- MAIN CONTAINER -->
    <main class="relative z-10 w-full max-w-lg mx-auto my-6">
        
        <!-- STEP 1: APOLOGY CARD -->
        <div id="apologyCard" class="glass-card rounded-3xl p-6 sm:p-8 text-center transition-all duration-500 transform hover:shadow-2xl">
            <!-- Avatar Header -->
            <div class="relative w-28 h-28 mx-auto mb-4 flex items-center justify-center">
                <div class="absolute inset-0 bg-pink-200 rounded-full animate-ping opacity-30"></div>
                <div class="w-24 h-24 bg-gradient-to-tr from-pink-400 to-red-400 rounded-full flex items-center justify-center text-5xl shadow-lg border-4 border-white pulse-heart">
                    🥺
                </div>
                <div class="absolute -bottom-1 -right-1 bg-white p-2 rounded-full shadow">
                    <i class="fa-solid fa-heart text-romantic-red text-lg"></i>
                </div>
            </div>

            <!-- Personalized Heartfelt Headline -->
            <h1 class="text-3xl sm:text-4xl font-extrabold text-gray-800 mb-2 tracking-wide">
                Jonim Rayhona... 💖
            </h1>
            <p class="text-xl sm:text-2xl font-bold text-romantic-red mb-4 font-handwriting">
                Meni kechirasanmi, sevgilim? 🥺
            </p>

            <!-- Warm Apology Note -->
            <p class="text-gray-600 text-base sm:text-lg mb-5 leading-relaxed font-medium">
                Rayhonam, senga ozroq bo'lsa ham ozor berib qo'yganimdan yuragim og'riyapti... 😔<br>
                Sening tabassuming men uchun dunyodagi eng go'zal mo'jiza. Bilmasdan xafa qilgan bo'lsam, chin kalbimdan <b>kechirim so'rayman, yagonam!</b> ✨
            </p>

            <p class="text-sm text-pink-500 font-semibold italic mb-6">
                Iltimos, mehribonim, mendan gina qilma... 🥺🌸
            </p>

            <!-- Interactive Buttons Container -->
            <div id="buttonArea" class="relative min-h-[140px] sm:min-h-[120px] flex flex-col sm:flex-row items-center justify-center gap-4 p-2">
                
                <!-- YES BUTTON -->
                <button id="yesBtn" onclick="handleAccept()" class="w-full sm:w-auto min-w-[160px] px-8 py-3.5 bg-gradient-to-r from-pink-500 to-red-500 hover:from-pink-600 hover:to-red-600 text-white font-bold text-lg rounded-full shadow-lg shadow-pink-300/50 hover:shadow-xl transition-all duration-200 active:scale-95 flex items-center justify-center gap-2 z-20">
                    <i class="fa-solid fa-heart"></i>
                    <span>Ha, kechirdim jonim</span>
                </button>

                <!-- NO BUTTON (UNCLICKABLE) -->
                <button id="noBtn" class="w-full sm:w-auto min-w-[140px] px-8 py-3.5 bg-gray-200 text-gray-600 font-bold text-lg rounded-full shadow hover:bg-gray-300 transition-all duration-100 z-10 sm:relative">
                    Yo'q 😜
                </button>
            </div>
            
            <p id="dodgeCounter" class="text-xs text-pink-400 mt-4 opacity-0 transition-opacity duration-300">
                (Jonim Rayhona, "Yo'q" tugmasini baribir bosolmaysiz! 😉❤️)
            </p>
        </div>

        <!-- STEP 2: CELEBRATION CARD -->
        <div id="celebrationCard" class="hidden glass-card rounded-3xl p-6 sm:p-8 text-center transition-all duration-700 transform scale-90 opacity-0">
            
            <div class="text-5xl sm:text-6xl mb-3 pulse-heart">
                🥰
            </div>

            <h2 class="text-3xl sm:text-4xl font-extrabold text-pink-600 mb-1 font-handwriting">
                Urraaa! Rahmat, Rayhonam! ✨❤️
            </h2>
            <p class="text-sm font-bold text-romantic-red uppercase tracking-wider mb-5">
                Yagonam, sevgilim, erkatoyim!
            </p>

            <p class="text-gray-700 font-medium text-base sm:text-lg mb-6">
                Meni kechirishingni bilardim! Seni dunyodagi hammasidan ham ko'proq yaxshi ko'raman! 💖
            </p>

            <!-- Letter Envelope addressed to Rayhona -->
            <div class="mb-8 text-left">
                <div class="bg-rose-50 border-2 border-dashed border-pink-300 rounded-2xl p-5 shadow-inner relative">
                    <div class="absolute -top-3 right-4 bg-red-400 text-white text-xs px-3 py-1 rounded-full font-bold shadow">
                        Rayhonamga maktub ✉️
                    </div>
                    <p class="font-handwriting text-2xl text-pink-800 leading-snug mb-2">
                        Mening go'zal va yagona Rayhonamga...
                    </p>
                    <p class="text-gray-700 text-sm sm:text-base leading-relaxed">
                        Sening mehring, samimiy kulgularing va issiq mehring men uchun bebaho boylik, jonim. Har bir soniyada seni xursand qilishga, yuzingga faqat tabassum ulashishga va'da beraman! Hayotimda borliging uchun alohida rahmat, yagonam. 🌸✨
                    </p>
                </div>
            </div>

            <!-- Interactive Flipping Cards for Rayhona -->
            <div class="mb-6">
                <h3 class="text-base sm:text-lg font-bold text-gray-800 mb-3 flex items-center justify-center gap-2">
                    <i class="fa-solid fa-sparkles text-yellow-400"></i>
                    <span>Rayhonamning 3 ta yoqimtoy siri (bosib ko'ring):</span>
                </h3>

                <div class="grid grid-cols-1 sm:grid-cols-3 gap-3">
                    
                    <!-- Card 1 -->
                    <div class="perspective-1000 h-24 cursor-pointer" onclick="flipCard(this)">
                        <div class="card-inner relative w-full h-full transform-style-3d rounded-xl shadow-md">
                            <!-- Front -->
                            <div class="absolute inset-0 bg-white border-2 border-pink-200 rounded-xl flex items-center justify-center p-2 text-pink-500 font-bold backface-hidden">
                                <i class="fa-solid fa-face-smile-wink text-2xl mr-1"></i> 1-sir 🌸
                            </div>
                            <!-- Back -->
                            <div class="absolute inset-0 bg-gradient-to-br from-pink-400 to-red-400 text-white rounded-xl flex items-center justify-center p-2 text-xs font-bold text-center rotate-y-180 backface-hidden">
                                Dunyodagi eng go'zal kulgu ❤️
                            </div>
                        </div>
                    </div>

                    <!-- Card 2 -->
                    <div class="perspective-1000 h-24 cursor-pointer" onclick="flipCard(this)">
                        <div class="card-inner relative w-full h-full transform-style-3d rounded-xl shadow-md">
                            <!-- Front -->
                            <div class="absolute inset-0 bg-white border-2 border-pink-200 rounded-xl flex items-center justify-center p-2 text-pink-500 font-bold backface-hidden">
                                <i class="fa-solid fa-heart-pulse text-2xl mr-1"></i> 2-sir ✨
                            </div>
                            <!-- Back -->
                            <div class="absolute inset-0 bg-gradient-to-br from-pink-400 to-red-400 text-white rounded-xl flex items-center justify-center p-2 text-xs font-bold text-center rotate-y-180 backface-hidden">
                                Beg'ubor va pokiza qalbing 🌟
                            </div>
                        </div>
                    </div>

                    <!-- Card 3 -->
                    <div class="perspective-1000 h-24 cursor-pointer" onclick="flipCard(this)">
                        <div class="card-inner relative w-full h-full transform-style-3d rounded-xl shadow-md">
                            <!-- Front -->
                            <div class="absolute inset-0 bg-white border-2 border-pink-200 rounded-xl flex items-center justify-center p-2 text-pink-500 font-bold backface-hidden">
                                <i class="fa-solid fa-gem text-2xl mr-1"></i> 3-sir 💎
                            </div>
                            <!-- Back -->
                            <div class="absolute inset-0 bg-gradient-to-br from-pink-400 to-red-400 text-white rounded-xl flex items-center justify-center p-2 text-xs font-bold text-center rotate-y-180 backface-hidden">
                                Mening yagona erkatoyim liging 🥰
                            </div>
                        </div>
                    </div>

                </div>
            </div>

            <!-- Action Buttons -->
            <div class="flex flex-col sm:flex-row gap-3 justify-center">
                <button onclick="triggerMoreLove()" class="px-6 py-2.5 bg-pink-100 text-pink-600 font-bold rounded-full hover:bg-pink-200 transition-colors flex items-center justify-center gap-2">
                    <i class="fa-solid fa-wand-magic-sparkles"></i> Rayhonamga sovg'a 💖
                </button>
                
                <button onclick="shareLove()" class="px-6 py-2.5 bg-gradient-to-r from-pink-500 to-red-500 text-white font-bold rounded-full hover:shadow-lg transition-all flex items-center justify-center gap-2">
                    <i class="fa-solid fa-copy"></i> Havolani nusxalash
                </button>
            </div>

        </div>

    </main>

    <!-- Toast Notification -->
    <div id="toast" class="fixed bottom-5 left-1/2 -translate-x-1/2 bg-gray-900 text-white px-5 py-2.5 rounded-full text-sm font-semibold shadow-2xl opacity-0 transition-opacity duration-300 pointer-events-none z-50 flex items-center gap-2">
        <i class="fa-solid fa-check-circle text-green-400"></i>
        <span id="toastMsg">Havola nusxalandi!</span>
    </div>

    <!-- JAVASCRIPT LOGIC -->
    <script>
        // Floating Background Hearts
        function createFloatingHearts() {
            const container = document.getElementById('heartsContainer');
            const heartIcons = ['fa-heart', 'fa-heart-pulse', 'fa-sparkles'];
            
            setInterval(() => {
                const heart = document.createElement('i');
                const randomIcon = heartIcons[Math.floor(Math.random() * heartIcons.length)];
                
                heart.className = `fa-solid ${randomIcon} bg-heart`;
                heart.style.left = Math.random() * 100 + 'vw';
                heart.style.fontSize = (Math.random() * 20 + 12) + 'px';
                heart.style.animationDuration = (Math.random() * 5 + 6) + 's';
                
                container.appendChild(heart);

                setTimeout(() => {
                    heart.remove();
                }, 10000);
            }, 450);
        }

        // Elusive "Yo'q" Button Logic
        const noBtn = document.getElementById('noBtn');
        const yesBtn = document.getElementById('yesBtn');
        const dodgeCounter = document.getElementById('dodgeCounter');
        let dodgeCount = 0;

        function moveNoButton() {
            dodgeCount++;
            
            if (dodgeCount >= 2) {
                dodgeCounter.classList.remove('opacity-0');
            }

            playPopSound(300 + Math.random() * 200, 0.05);

            const padding = 20;
            const btnRect = noBtn.getBoundingClientRect();

            const maxX = window.innerWidth - btnRect.width - padding;
            const maxY = window.innerHeight - btnRect.height - padding;

            let randomX = Math.max(padding, Math.floor(Math.random() * maxX));
            let randomY = Math.max(padding, Math.floor(Math.random() * maxY));

            noBtn.style.position = 'fixed';
            noBtn.style.left = randomX + 'px';
            noBtn.style.top = randomY + 'px';
            
            // "Ha" button grows larger to encourage clicking
            const currentScale = 1 + (dodgeCount * 0.08);
            if (currentScale <= 1.6) {
                yesBtn.style.transform = `scale(${currentScale})`;
            }
        }

        noBtn.addEventListener('mouseenter', moveNoButton);
        noBtn.addEventListener('touchstart', (e) => {
            e.preventDefault();
            moveNoButton();
        });
        noBtn.addEventListener('click', (e) => {
            e.preventDefault();
            moveNoButton();
        });

        // Acceptance Logic
        function handleAccept() {
            playFanfareSound();
            triggerConfetti();

            const apologyCard = document.getElementById('apologyCard');
            const celebrationCard = document.getElementById('celebrationCard');

            apologyCard.style.opacity = '0';
            apologyCard.style.transform = 'scale(0.8)';

            setTimeout(() => {
                apologyCard.classList.add('hidden');
                
                celebrationCard.classList.remove('hidden');
                setTimeout(() => {
                    celebrationCard.classList.remove('scale-90', 'opacity-0');
                    celebrationCard.classList.add('scale-100', 'opacity-100');
                }, 50);
            }, 400);
        }

        // Confetti Fireworks
        function triggerConfetti() {
            const count = 200;
            const defaults = { origin: { y: 0.7 } };

            function fire(particleRatio, opts) {
                confetti(Object.assign({}, defaults, opts, {
                    particleCount: Math.floor(count * particleRatio)
                }));
            }

            fire(0.25, { spread: 26, startVelocity: 55, colors: ['#ff758f', '#ff4d6d', '#ffffff'] });
            fire(0.2, { spread: 60, colors: ['#ffb3c1', '#ffffff', '#ff4d6d'] });
            fire(0.35, { spread: 100, decay: 0.91, scalar: 0.8 });
            fire(0.1, { spread: 120, startVelocity: 25, decay: 0.92, colors: ['#e2afff', '#ff758f', '#ffffff'] });
            fire(0.1, { spread: 120, startVelocity: 45 });
        }

        function triggerMoreLove() {
            triggerConfetti();
            playPopSound(523.25, 0.1);
            showToast("Rayhonamga cheksiz sevgilar yo'llanmoqda! ❤️✨");
        }

        function flipCard(element) {
            const inner = element.querySelector('.card-inner');
            inner.classList.toggle('rotate-y-180');
            playPopSound(440, 0.05);
        }

        function shareLove() {
            const dummy = document.createElement('input');
            document.body.appendChild(dummy);
            dummy.value = window.location.href;
            dummy.select();
            document.execCommand('copy');
            document.body.removeChild(dummy);

            showToast("Havola nusxalandi! 📋✨");
        }

        function showToast(message) {
            const toast = document.getElementById('toast');
            const toastMsg = document.getElementById('toastMsg');
            toastMsg.innerText = message;
            
            toast.classList.remove('opacity-0');
            toast.classList.add('opacity-100');

            setTimeout(() => {
                toast.classList.remove('opacity-100');
                toast.classList.add('opacity-0');
            }, 3000);
        }

        // Web Audio Synthesizer Sound Effects
        function playPopSound(freq = 400, duration = 0.08) {
            try {
                const AudioCtx = window.AudioContext || window.webkitAudioContext;
                if (!AudioCtx) return;
                const ctx = new AudioCtx();
                const osc = ctx.createOscillator();
                const gain = ctx.createGain();

                osc.type = 'sine';
                osc.frequency.setValueAtTime(freq, ctx.currentTime);
                osc.frequency.exponentialRampToValueAtTime(freq * 1.5, ctx.currentTime + duration);

                gain.gain.setValueAtTime(0.15, ctx.currentTime);
                gain.gain.exponentialRampToValueAtTime(0.01, ctx.currentTime + duration);

                osc.connect(gain);
                gain.connect(ctx.destination);

                osc.start();
                osc.stop(ctx.currentTime + duration);
            } catch (e) {}
        }

        function playFanfareSound() {
            const notes = [261.63, 329.63, 392.00, 523.25];
            notes.forEach((freq, idx) => {
                setTimeout(() => {
                    playPopSound(freq, 0.2);
                }, idx * 100);
            });
        }

        window.addEventListener('DOMContentLoaded', () => {
            createFloatingHearts();
        });
    </script>
</body>
</html>