<template>
    <section class="pt-20 md:pt-24">
        <AtomsContainer>
            <div class="grid md:grid-cols-2 gap-10 xl:gap-14 relative">
                <div class="md:py-2 lg:py-4 relative">
                    <div class="relative">
                        <AtomsTitle texte="Cari tahu apa yang membuat berbeda dari yang lain" />
                        <p class="text-gray-600 dark:text-gray-300 pt-8">
                            Fitur Dual Server Radius Memungkinkan proses Auth/Acounting tidak ada yang Radius timeOut / Radius Not Responding walaupun salah satu Server sedang Disconect/Maintenance/Rusak.
                        </p>
                        <div class="space-y-4 pt-8">
                            <div class="p-4 rounded-xl border border-box-border transition hover:bg-gray-200 dark:hover:bg-box-bg">
                                <h3 class="text-gray-700 dark:text-gray-200 font-semibold text-xl">Integrasikan semua mikrotik server</h3>
                                <p class="text-base text-gray-600 dark:text-gray-300">1 data Hotspot/PPPoE bisa dipakai untuk semua cabang</p>
                            </div>
                            <div class="p-4 rounded-xl border border-box-border transition hover:bg-gray-200 dark:hover:bg-box-bg">
                                <h3 class="text-gray-700 dark:text-gray-200 font-semibold text-xl">Data Vocuher/Pelanggan</h3>
                                <p class="text-base text-gray-600 dark:text-gray-300">Semua data voucher/Pelanggan yang telah dibuat aman, ketika Mikrotik Rusak.</p>
                            </div>
                            <div class="p-4 rounded-xl border border-box-border transition hover:bg-gray-200 dark:hover:bg-box-bg">
                                <h3 class="text-gray-700 dark:text-gray-200 font-semibold text-xl">WhatsApp Gateway</h3>
                                <p class="text-base text-gray-600 dark:text-gray-300">WhatsApp Gateway memungkinkan bisa berganti-ganti Nomor.</p>
                            </div>
                            <div class="p-4 rounded-xl border border-box-border transition hover:bg-gray-200 dark:hover:bg-box-bg">
                                <h3 class="text-gray-700 dark:text-gray-200 font-semibold text-xl">Payment Gateway</h3>
                                <p class="text-base text-gray-600 dark:text-gray-300">Terdapat Feature Payment Gateway yang memudahkan transaksi pelanggan.</p>
                            </div>
                            <div class="p-4 rounded-xl border border-box-border transition hover:bg-gray-200 dark:hover:bg-box-bg">
                                <h3 class="text-gray-700 dark:text-gray-200 font-semibold text-xl">Feature Lainnya</h3>
                                <p class="text-base text-gray-600 dark:text-gray-300">Masih banyak feature lainnya, silahkan hubungi kami untuk mengetahui lebih lengkapnya.</p>
                            </div>
                        </div>
                        <div class="pt-10 flex">
                            <AtomsLinkBtn href="https://wa.me/6285285823571?text=Hallo LeleRadius" variant="primary">
                                Hubungi Kami
                            </AtomsLinkBtn>
                        </div>
                    </div>
                </div>
                <div class="flex md:h-full relative">
                    <div
                            class="absolute z-0 top-1/2  -translate-y-1/2 w-5/6 right-0 h-[calc(80%+20px)] bg-gradient-to-tr opacity-25 from-primary to-pink-300 dark:from-[#570cac] dark:to-primary blur-2xl">
                        </div>
                    <div
                        class="w-full h-[27rem] sm:h-[30rem] md:h-full flex justify-start md:justify-end relative pb-5">
                        <img src="/images/profile.png" alt="Podcast image" width="300" class="w-2/5 aspect-square absolute bottom-0 right-0 md:left-0 object-cover rounded-t-[10%] rounded-b-[10%] border-4 border-box-border shadow-md shadow-box-shadow">
                        <img src="/images/pelanggan.png" alt="Illustratuin about" width="500"
                            class="w-11/12 lg:w-5/6 h-full object-cover rounded-t-[1rem] rounded-b-[1rem] border-8 border-box-border">
                    </div>
                </div>
            </div>
        </AtomsContainer>
    </section>
</template>