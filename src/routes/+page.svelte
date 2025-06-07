<svelte:head>
    <title>Syntax Cafe - Coming Soon</title>
    <meta name="description" content="Syntax Cafe is launching soon! Stay tuned for our amazing features." />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
</svelte:head>

<div
    class="min-h-screen bg-gradient-to-br from-gray-900 to-indigo-900 overflow-hidden"
>
    <!-- Floating 3D Shapes (Background) -->
    <div class="fixed inset-0 overflow-hidden z-0">
        <div
            class="absolute top-1/4 left-1/4 w-32 h-32 rounded-full bg-purple-500/20 blur-xl floating"
        ></div>
        <div
            class="absolute top-1/3 right-1/4 w-40 h-40 rounded-full bg-blue-500/20 blur-xl floating-2"
        ></div>
        <div
            class="absolute bottom-1/4 right-1/3 w-28 h-28 rounded-full bg-pink-500/20 blur-xl floating-3"
        ></div>
    </div>

    <!-- Main Content -->
    <div
        class="relative z-10 min-h-screen flex flex-col items-center justify-center p-6 text-center"
    >
        <!-- 3D Logo/Brand -->
        <div
            class="mb-8 glass-card p-6 rounded-2xl shadow-lg transform rotate-3 hover:rotate-0 transition-all duration-500"
        >
            <img class="h-16 w-16 mx-auto" src="/logo.png" alt="" srcset="" />
        </div>

        <!-- Heading with Glow -->
        <h1 class="text-5xl md:text-6xl font-bold text-white mb-4 glow-text">
            Coming <span
                class="text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-purple-400"
                >Soon</span
            >
        </h1>

        <!-- Subheading -->
        <p class="text-xl text-white/80 max-w-lg mx-auto mb-10">
            We're building something amazing! Stay tuned for our launch.
        </p>

        <!-- Countdown Timer (3D Cards) -->
        <!-- <div class="grid grid-cols-4 gap-4 mb-12">
            <div
                class="glass-card p-4 rounded-xl text-center transform hover:-translate-y-2 transition-all"
            >
                <div class="text-3xl font-bold text-white">14</div>
                <div class="text-white/70 text-sm">Days</div>
            </div>
            <div
                class="glass-card p-4 rounded-xl text-center transform hover:-translate-y-2 transition-all"
            >
                <div class="text-3xl font-bold text-white">08</div>
                <div class="text-white/70 text-sm">Hours</div>
            </div>
            <div
                class="glass-card p-4 rounded-xl text-center transform hover:-translate-y-2 transition-all"
            >
                <div class="text-3xl font-bold text-white">42</div>
                <div class="text-white/70 text-sm">Minutes</div>
            </div>
            <div
                class="glass-card p-4 rounded-xl text-center transform hover:-translate-y-2 transition-all"
            >
                <div class="text-3xl font-bold text-white">30</div>
                <div class="text-white/70 text-sm">Seconds</div>
            </div>
        </div> -->

        <!-- 3D CTA Button -->
        <!-- <button
            class="btn-3d bg-gradient-to-r from-blue-500 to-purple-600 text-white font-bold py-4 px-8 rounded-xl shadow-lg mb-10"
        >
            Notify Me on Launch
        </button> -->

        <!-- Social Links (Floating) -->
        <div class="flex space-x-6">
            <a
                aria-label="Discord"
                target="_blank"
                href="https://discord.gg/rFyuV5ycHJ"
                class="glass-card w-12 h-12 rounded-full flex items-center justify-center transform hover:-translate-y-2 transition-all"
            >
                <svg
                    class="w-6 h-6 text-white"
                    role="img"
                    viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg"
                    height="24"
                    width="24"
                >
                    <path
                        d="M20.317 4.3698a19.7913 19.7913 0 0 0 -4.8851 -1.5152 0.0741 0.0741 0 0 0 -0.0785 0.0371c-0.211 0.3753 -0.4447 0.8648 -0.6083 1.2495 -1.8447 -0.2762 -3.68 -0.2762 -5.4868 0 -0.1636 -0.3933 -0.4058 -0.8742 -0.6177 -1.2495a0.077 0.077 0 0 0 -0.0785 -0.037 19.7363 19.7363 0 0 0 -4.8852 1.515 0.0699 0.0699 0 0 0 -0.0321 0.0277C0.5334 9.0458 -0.319 13.5799 0.0992 18.0578a0.0824 0.0824 0 0 0 0.0312 0.0561c2.0528 1.5076 4.0413 2.4228 5.9929 3.0294a0.0777 0.0777 0 0 0 0.0842 -0.0276c0.4616 -0.6304 0.8731 -1.2952 1.226 -1.9942a0.076 0.076 0 0 0 -0.0416 -0.1057c-0.6528 -0.2476 -1.2743 -0.5495 -1.8722 -0.8923a0.077 0.077 0 0 1 -0.0076 -0.1277c0.1258 -0.0943 0.2517 -0.1923 0.3718 -0.2914a0.0743 0.0743 0 0 1 0.0776 -0.0105c3.9278 1.7933 8.18 1.7933 12.0614 0a0.0739 0.0739 0 0 1 0.0785 0.0095c0.1202 0.099 0.246 0.1981 0.3728 0.2924a0.077 0.077 0 0 1 -0.0066 0.1276 12.2986 12.2986 0 0 1 -1.873 0.8914 0.0766 0.0766 0 0 0 -0.0407 0.1067c0.3604 0.698 0.7719 1.3628 1.225 1.9932a0.076 0.076 0 0 0 0.0842 0.0286c1.961 -0.6067 3.9495 -1.5219 6.0023 -3.0294a0.077 0.077 0 0 0 0.0313 -0.0552c0.5004 -5.177 -0.8382 -9.6739 -3.5485 -13.6604a0.061 0.061 0 0 0 -0.0312 -0.0286zM8.02 15.3312c-1.1825 0 -2.1569 -1.0857 -2.1569 -2.419 0 -1.3332 0.9555 -2.4189 2.157 -2.4189 1.2108 0 2.1757 1.0952 2.1568 2.419 0 1.3332 -0.9555 2.4189 -2.1569 2.4189zm7.9748 0c-1.1825 0 -2.1569 -1.0857 -2.1569 -2.419 0 -1.3332 0.9554 -2.4189 2.1569 -2.4189 1.2108 0 2.1757 1.0952 2.1568 2.419 0 1.3332 -0.946 2.4189 -2.1568 2.4189Z"
                        fill="currentColor"
                        stroke-width="1"
                    ></path>
                </svg>
            </a>
            <a
                aria-label="Instagram"
                target="_blank"
                href="https://www.instagram.com/syntaxcafe.app"
                class="glass-card w-12 h-12 rounded-full flex items-center justify-center transform hover:-translate-y-2 transition-all"
            >
                <svg
                    class="w-6 h-6 text-white"
                    fill="currentColor"
                    viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg"
                >
                    <path
                        d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zM12 0C8.741 0 8.333.014 7.053.072 2.695.272.273 2.69.073 7.052.014 8.333 0 8.741 0 12c0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98C8.333 23.986 8.741 24 12 24c3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98C15.668.014 15.259 0 12 0zm0 5.838a6.162 6.162 0 100 12.324 6.162 6.162 0 000-12.324zM12 16a4 4 0 110-8 4 4 0 010 8zm6.406-11.845a1.44 1.44 0 100 2.881 1.44 1.44 0 000-2.881z"
                    />
                </svg>
            </a>
            <a
                aria-label="X (Twitter)"
                target="_blank"
                href="https://x.com/syntaxcafe"
                class="glass-card w-12 h-12 rounded-full flex items-center justify-center transform hover:-translate-y-2 transition-all"
            >
                <svg
                    class="w-6 h-6 text-white"
                    role="img"
                    viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg"
                    height="24"
                    width="24"
                >
                    <path
                        d="M18.901 1.153h3.68l-8.04 9.19L24 22.846h-7.406l-5.8 -7.584 -6.638 7.584H0.474l8.6 -9.83L0 1.154h7.594l5.243 6.932ZM17.61 20.644h2.039L6.486 3.24H4.298Z"
                        fill="currentColor"
                        stroke-width="1"
                    ></path>
                </svg>
            </a>
        </div>
    </div>
</div>
