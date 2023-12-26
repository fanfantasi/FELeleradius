<template>
    <section class="pt-20 md:pt-24">
        <AtomsContainer>
            <div class="grid md:grid-cols-2 gap-10 xl:gap-14 relative">
                <div class="flex md:h-full ">
                    <div
                        class="w-full md:h-full rounded-3xl bg-white dark:bg-body shadow-lg shadow-box-shadow border border-box-border">
                        <img src="/about-us.png" alt="Illustratuin about" width="500"
                            class="w-full h-full object-cover rounded-2xl">
                    </div>
                </div>
                <div class="md:py-2 lg:py-4 relative">
                    <div class="relative">
                        <AtomsTitle texte="About Us Apps LeleRadius" />
                        <p class="text-gray-600 dark:text-gray-300 pt-8">
                            LeleRadius billing internet dengan teknik Radius Authentikasi, 
                            semua data pelanggan / voucher dari semua cabang terpusat pada dua server Leleradius memungkinkan data tetap aman
                            walaupun server cabang / mikrotik mengalami kerusakan.
                            <br />Fitur Dual Server Radius Memungkinkan proses Auth/Acounting tidak ada yang 
                            Radius timeOut / Radius Not Responding walaupun salah satu Server 
                            sedang Disconect/Maintenance/Rusak Dadakan dikarenakan jalur komunikasi diproses secara 
                            PlyOver ke dua server radius pada Data Center berbeda tanpa harus ganti-ganti VPN/Jalur komunikasi
                        </p>
                        <div class="grid grid-cols-3 gap-4 max-w-lg pt-8">
                            <div
                                class="text-center rounded-xl bg-box-bg shadow-lg shadow-box-shadow border border-box-border p-3">
                                <h3 class="text-gray-800 dark:text-white font-bold text-xl sm:text-2xl lg:text-3xl">45 +
                                </h3>
                                <p class="text-sm sm:text-base text-gray-600 dark:text-gray-300">Feature</p>
                            </div>
                            <div
                                class="text-center rounded-xl bg-box-bg shadow-lg shadow-box-shadow border border-box-border p-3">
                                <h3 class="text-gray-800 dark:text-white font-bold text-xl sm:text-2xl lg:text-3xl">5k +</h3>
                                <p class="text-sm sm:text-base text-gray-600 dark:text-gray-300">Pengguna</p>
                            </div>
                            <div
                                class="text-center rounded-xl bg-box-bg shadow-lg shadow-box-shadow border border-box-border p-3">
                                <h3 class="text-gray-800 dark:text-white font-bold text-xl sm:text-2xl lg:text-3xl">5 +
                                </h3>
                                <p class="text-sm sm:text-base text-gray-600 dark:text-gray-300">Pengalaman</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </AtomsContainer>
    </section>
</template>