<template>
    <section class="py-20">
      <AtomsContainer>
        <div class="max-w-md mx-auto mb-14 text-center">
          <h1 class="text-4xl font-semibold mb-6 lg:text-5xl dark:text-white">
            <span class="text-green-600">Premium</span> Plans
          </h1>
          <p class="text-xl text-gray-500 font-medium dark:text-gray-200">
            Khusus anda yang sudah memiliki pelanggan diatas 5000 Data Pelanggan, kami menawarkan Paket Premium.
          </p>
        </div>
  
        <div class="flex flex-col justify-between items-center lg:flex-row lg:items-start">
          
  
          <div class="w-full flex-1 mt-8 p-8 order-2 bg-white shadow-xl rounded-3xl sm:w-96 lg:w-full lg:order-1 lg:rounded-r-none" >
            <div class="mb-4 pb-7 flex items-center border-b border-gray-300">
              <img src="/startup.svg" alt="" class="rounded-3xl w-20 h-20"/>
              <div class="ml-5">
                <span class="block text-2xl font-semibold">Mandiri 1</span>
                <span>
                    <span class="font-medium text-gray-500 text-xl align-top">Rp.&thinsp;</span>
                    <span class="text-3xl font-bold">150.000 </span>
                </span>
                    <span class="text-gray-500 font-medium">/ month</span>
              </div>
            </div>
            <div class="pb-4 mb-4 items-center border-b border-gray-300">
                <span>
                    <span class="font-medium text-gray-500 text-xs align-top">Rp.&thinsp;</span>
                    <span class="text-xl font-bold">5.000.000 </span>
                </span>
                    <span class="text-gray-500 font-medium">Installasi</span>
            </div>
            <ul class="mb-7 font-medium text-gray-500">
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6" />
                <span class="ml-3 text-base">Admin Panel <span class="text-white">Owner/Agen</span></span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6" />
                <span class="ml-3 text-base">Unlimited Device <span class="text-blue-600">(Mikrotik)</span></span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Unlimited Data Pelanggan <span class="text-blue-600">(Hotspot/PPPoE)</span></span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Unlimited Data <span class="text-blue-600">Voucher</span></span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Unlimited Sesi <span class="text-blue-600">Aktif</span></span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Gratis VPN</span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Gratis Setup</span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Gratis Update Selamanya</span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/crossed.png" class="h-6"/>
                <span class="ml-3 text-red-400">Dual Server Radius</span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3">Control Redaman OLT EPON/GPOM</span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Gratis VPN Remote WinBox</span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Gratis WhatsApp Pemberitahuan</span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Gratis Payment Gateway</span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Aplikasi Mobile Khusus Pelanggan</span>
              </li>
            </ul>
            <a href="#" class="flex justify-center items-center bg-indigo-600 rounded-xl py-5 px-4 text-center text-white text-xl">
            Contact +62 8528 5823 571</a>
          </div>

          <div class="w-full flex-1 p-8 order-1 shadow-xl rounded-3xl bg-cyan-800 dark:bg-cyan-600 text-gray-400 sm:w-96 lg:w-full lg:order-2 lg:mt-0">
            <div class="mb-7 pb-7 flex items-center border-b border-gray-300">
              <img
                src="/basic.svg"
                alt=""
                class="rounded-3xl w-20 h-20"
              />
              <div class="ml-5">
                <span class="block text-2xl font-semibold text-gray-100">Premium</span>
                <span
                  ><span class="font-medium text-gray-200 text-xl align-top"
                    >Rp.&thinsp;</span
                  ><span class="text-3xl font-bold text-gray-200">500.000 </span></span
                ><span class="text-gray-200 font-medium">/ Month</span>
              </div>
            </div>
            <ul class="mb-7 font-medium text-gray-200">
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6" />
                <span class="ml-3 text-base">Admin Panel <span class="text-green-600">Owner/Agen</span></span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6" />
                <span class="ml-3 text-base">Max 10 Device <span class="text-green-600">(Mikrotik)</span></span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">5.000 Data Pelanggan <span class="text-green-600">(Hotspot/PPPoE)</span></span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">100.000 Data <span class="text-green-600">Voucher</span></span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">5.000 Sesi <span class="text-green-600">Aktif</span></span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Gratis VPN</span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Gratis Setup</span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Gratis Update Selamanya</span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-red-400">Dual Server Radius</span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3">Control Redaman OLT EPON/GPOM</span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Gratis VPN Remote WinBox</span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Gratis WhatsApp Pemberitahuan</span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Gratis Payment Gateway</span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Aplikasi Mobile Khusus Pelanggan</span>
              </li>
            </ul>
            <a href="#" class="flex justify-center items-center bg-indigo-600 rounded-xl py-5 px-4 text-center text-white text-xl">
            Contact +62 8528 5823 571</a>
          </div>

          <div class="w-full flex-1 mt-8 p-8 order-3 bg-white shadow-xl rounded-3xl sm:w-96 lg:w-full lg:order-3 lg:rounded-l-none">
            <div class="mb-4 pb-7 flex items-center border-b border-gray-300">
              <img src="/bussines.svg" alt="" class="rounded-3xl w-20 h-20"/>
              <div class="ml-5">
                <span class="block text-2xl font-semibold">Mandiri 2</span>
                <span>
                    <span class="font-medium text-gray-500 text-xl align-top">Rp.&thinsp;</span>
                    <span class="text-3xl font-bold">250.000 </span>
                </span>
                    <span class="text-gray-500 font-medium">/ month</span>
              </div>
            </div>
            <div class="pb-4 mb-4 items-center border-b border-gray-300">
                <span>
                    <span class="font-medium text-gray-500 text-xs align-top">Rp.&thinsp;</span>
                    <span class="text-xl font-bold">10.000.000 </span>
                </span>
                    <span class="text-gray-500 font-medium">Installasi</span>
            </div>
            <ul class="mb-7 font-medium text-gray-500">
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6" />
                <span class="ml-3 text-base">Admin Panel <span class="text-white">Owner/Agen</span></span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6" />
                <span class="ml-3 text-base">Unlimited Device <span class="text-blue-600">(Mikrotik)</span></span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Unlimited Data Pelanggan <span class="text-blue-600">(Hotspot/PPPoE)</span></span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Unlimited Data <span class="text-blue-600">Voucher</span></span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Unlimited Sesi <span class="text-blue-600">Aktif</span></span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Gratis VPN</span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Gratis Setup</span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Gratis Update Selamanya</span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-red-400">Dual Server Radius</span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3">Control Redaman OLT EPON/GPOM</span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Gratis VPN Remote WinBox</span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Gratis WhatsApp Pemberitahuan</span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Gratis Payment Gateway</span>
              </li>
              <li class="flex text-lg mb-2">
                <img src="/check.png" class="h-6"/>
                <span class="ml-3 text-base">Aplikasi Mobile Khusus Pelanggan</span>
              </li>
            </ul>
            <a href="#" class="flex justify-center items-center bg-indigo-600 rounded-xl py-5 px-4 text-center text-white text-xl">
            Contact +62 8528 5823 571</a>
          </div>
        </div>
      </AtomsContainer>
    </section>
  </template>