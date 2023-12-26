<template>
    <section class="relative w-full">
        <div class="absolute top-0 inset-x-0 h-64 flex items-start">
            <div
                class="h-24 w-2/3 bg-gradient-to-br from-primary opacity-20 blur-2xl dark:from-[#570cac] dark:invisible dark:opacity-40">
            </div>
            <div
                class="h-20 w-3/5 bg-gradient-to-r from-[#8cd66a] opacity-40 blur-2xl dark:from-[#670ccf] dark:opacity-40">
            </div>
        </div>
        <AtomsContainer class-name="relative">
            <div aria-hidden="true" class="absolute inset-y-0 w-44 left-0 hidden dark:flex">
                <div
                    class="h-full md:h-1/2 lg:h-full w-full bg-gradient-to-tr opacity-40 dark:blur-2xl dark:from-[#570cac] dark:opacity-20">
                </div>
            </div>
            <div
                class="grid lg:grid-cols-2 gap-10 xl:gap-14 relative pt-24 lg:max-w-none max-w-2xl md:max-w-3xl mx-auto">
                <div class="lg:py-6">
                    <div class="text-center lg:text-left">
                        <span class="px-2 py-1 rounded-md bg-blue-100 dark:bg-body text-blue-400 ">High Availability</span>
                        <h1 class="text-gray-800 pt-4 dark:text-white font-bold text-4xl md:text-5xl lg:text-6xl">
                            Yang pertama <br> dan  <span
                                class="text-transparent bg-clip-text bg-gradient-to-br from-blue-400 to-[#93c5fd]">Satu-satunya</span>
                            di Indonesia
                        </h1>
                    </div>

                    <p class="text-gray-600 dark:text-gray-300 pt-8 text-center lg:text-left mx-auto max-w-xl">
                        LeleRadius billing internet dengan teknik Radius Authentikasi, semua data pelanggan / voucher dari semua cabang terpusat pada dua server Leleradius memungkinkan data tetap aman walaupun server cabang / mikrotik mengalami kerusakan.
                    </p>

                    <div class="flex items-center gap-3 pt-9 flex-col sm:flex-row sm:w-max sm:mx-auto lg:mx-0">
                        <AtomsLinkBtn href="https://billing.leleradius.com" variant="primary" class="w-full sm:w-max flex justify-center">
                            Sign In
                        </AtomsLinkBtn>
                    </div>
                    <div class="pt-8 lg:pt-10 w-max mx-auto lg:mx-0">
                        <div class="flex items-center text-center flex-col sm:flex-row gap-4 sm:gap-0">
                            <div class="flex items-center">
                                <img src="/users.png" width="40" alt="avatar"
                                    class="w-10 h-10 rounded-full border-2 border-white dark:border-gray-400 object-cover">
                                <img src="/users.png" width="40" alt="avatar"
                                    class="w-10 h-10 rounded-full border-2 border-white dark:border-gray-400 object-cover -ml-2.5">
                                <img src="/users.png" width="40" alt="avatar"
                                    class="w-10 h-10 rounded-full border-2 border-white dark:border-gray-400 object-cover -ml-2.5">
                                <img src="/users.png" width="40" alt="avatar"
                                    class="w-10 h-10 rounded-full border-2 border-white dark:border-gray-400 object-cover -ml-2.5">
                                <span
                                    class="w-10 h-10 rounded-full border-2 border-white dark:border-gray-400 bg-blue-300 flex items-center justify-center text-xs text-white object-cover -ml-2.5">
                                    5k+
                                </span>
                            </div>
                            <div class="pl-2 text-gray-600 dark:text-gray-200">
                                Pengguna yang telah bergabung
                            </div>
                        </div>
                    </div>
                </div>
                <div class="lg:h-full  hidden md:flex">

                    <div
                        class="flex w-full h-96 min-h-[24rem] lg:min-h-[none] lg:w-full lg:h-full items-center relative">
                        <div
                            class="absolute z-0 top-1/2  -translate-y-1/2 w-5/6 right-0 h-[calc(80%+20px)] bg-gradient-to-tr opacity-25 from-primary to-pink-300 dark:from-[#570cac] dark:to-primary blur-2xl">
                        </div>
                        <div
                            class="absolute w-3/5 h-full z-10 p-1 -translate-y-1/2 top-1/2 right-3 rounded-3xl bg-white dark:bg-body shadow-lg shadow-box-shadow border border-box-border">
                            <img src="/images/home-screen.jpg" alt="In studio" width="500" height="auto" loading="lazy"
                                class="w-full h-full rounded-2xl object-cover">
                        </div>
                        <div
                            class="absolute  -translate-y-1/2 top-1/2 h-[calc(80%-2rem)] w-[calc(40%-20px)] p-1 rounded-3xl bg-white dark:bg-body shadow-lg shadow-box-shadow border border-box-border ">
                            <img src="/images/home-screen-1.jpg" alt="Happy in studio" width="200" height="auto"
                                loading="lazy" class="w-full h-full rounded-2xl object-cover">
                        </div>
                    </div>
                </div>
            </div>
        </AtomsContainer>
    </section>
</template>