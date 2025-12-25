<template>
    <div
        class="min-h-screen flex flex-col items-center justify-center gap-y-8 bg-[url('/bg.jpg')] bg-cover bg-fixed bg-center font-sans">

        <!-- Waitlist Label -->
        <div
            class="border border-white/20 bg-white/10 backdrop-blur-md rounded-full px-4 py-1.5 flex items-center gap-2 shadow-lg">
            <UIcon name="i-heroicons-sparkles-solid" class="text-yellow-300 w-4 h-4" />
            <span class="text-sm font-medium text-white tracking-wide">Waitlist</span>
        </div>

        <!-- Title -->
        <div>
            <h1 class="text-6xl md:text-8xl font-bold text-white/70 tracking-tight text-center drop-shadow-sm">Coming
                soon!</h1>
        </div>

        <!-- Main Card -->
        <div
            class="relative group w-full max-w-xl p-8 rounded-3xl border border-white/10 bg-black/30 backdrop-blur-2xl shadow-2xl flex flex-col items-center gap-y-6 overflow-hidden">
            <!-- Glow effect -->
            <div
                class="absolute -top-24 -left-24 w-48 h-48 bg-blue-500/20 rounded-full blur-3xl pointer-events-none group-hover:bg-blue-500/30 transition-colors duration-700">
            </div>
            <div
                class="absolute -bottom-24 -right-24 w-48 h-48 bg-purple-500/20 rounded-full blur-3xl pointer-events-none group-hover:bg-purple-500/30 transition-colors duration-700">
            </div>

            <div class="z-10 flex flex-col items-center gap-y-4 w-full text-center">
                <h2 class="text-4xl font-bold text-white">Berny Linville 正在搞大事 ✨</h2>
                <p class="text-gray-300 max-w-lg leading-relaxed text-left flex flex-col gap-2">
                    🤫 宝子们！我们正在秘密打造几款超有趣、超实用的效率神器！<br>
                    🛠️ 想要告别枯燥，第一时间解锁黑科技？<br>
                    🎁 快加入 Waitlist，抢先体验不迷路，还有独家惊喜掉落哦！<br>
                    🚀 冲鸭！
                </p>
                <UButton to="https://forms.cloud.microsoft/r/8rDD0WNsYw" target="_blank" color="white" variant="solid"
                    class="rounded-full px-6 py-2 font-semibold bg-white/70 text-black hover:bg-white transition-colors">
                    立即加入 Waitlist 🚀
                </UButton>
            </div>
        </div>

        <!-- Social Links -->
        <div class="flex items-center gap-6 mt-4">
            <a href="https://x.com/Dunkwithmyson" target="_blank"
                class="w-12 h-12 flex items-center justify-center rounded-2xl bg-black/30 backdrop-blur-md border border-white/10 text-white/60 hover:text-white hover:bg-black/50 hover:border-white/30 transition-all duration-300 group">
                <UIcon name="i-simple-icons-x" class="w-5 h-5" />
            </a>
            <a href="https://t.me/Dunkwithmyson" target="_blank"
                class="w-12 h-12 flex items-center justify-center rounded-2xl bg-black/30 backdrop-blur-md border border-white/10 text-white/60 hover:text-white hover:bg-black/50 hover:border-white/30 transition-all duration-300 group">
                <UIcon name="i-simple-icons-telegram" class="w-5 h-5" />
            </a>
            <a href="https://www.facebook.com/Dunkwithmyson" target="_blank"
                class="w-12 h-12 flex items-center justify-center rounded-2xl bg-black/30 backdrop-blur-md border border-white/10 text-white/60 hover:text-white hover:bg-black/50 hover:border-white/30 transition-all duration-300 group">
                <UIcon name="i-simple-icons-facebook" class="w-5 h-5" />
            </a>
        </div>
    </div>
</template>

<script setup></script>
