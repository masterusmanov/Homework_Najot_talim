<script setup>

</script>

<template>
    <section class="bg-gray-100 h-[100px]">
        <div class="container mx-auto justify-center items-center w-full h-[70px]">
          <div class="grid-container justify-center items-center relative ">
            <div class="column inline-block w-[50%] h-[70px]">
              <img src="../../images/logo.png" alt="" class="w-[40%] pt-5">
            </div>
            <div
              class="column inline-block absolute justify-beetwen items-center w-[50%] h-[70px]"
            >
              <ul
                class="flex justify-end items-center gap-10 text-xl mt-5 font-bold text-blue-800"
              >
                <li>
                  <nuxt-link to="/course">Kurslar</nuxt-link>
                </li>
                <li>
                  <nuxt-link to="/blog">Blog</nuxt-link>
                </li>
                <li>
                  <nuxt-link to="/">Kirish</nuxt-link>
                </li>
                <li>
                  <nuxt-link to="#"
                    ><img src="../../images/Dark mode.svg" alt="" class="w-16"
                  /></nuxt-link>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </section>
      <section>
        <div class="container mx-auto">
            <div class="flex mx-auto justify-center mt-10 items-center">
                <div class="w-1/2">
                    <h1>Bosh sahifa ->  <nuxt-link to="#" class="text-yellow-800">Kurslar</nuxt-link></h1>
                    <h1 class="text-3xl mt-10 font-bold">Barcha o‘quv kurslari</h1>
                    <button class="p-4 rounded-full mt-10 bg-yellow-600 text-white hover:bg-gray-400 hover:text-black">Barchasi</button>
                    <button class="p-4 rounded-full ml-10 bg-yellow-600 text-white hover:bg-gray-400 hover:text-black">Dasturlash</button>
                </div>
                <div class="w-1/2">
                    <input type="text" placeholder="Izlash" class="flex mb-7 ml-[50%] w-[50%] h-[50px] pl-10 rounded-full border ">
                    <img src="../../images/search.png" alt="Izlash" class="absolute ml-[37%] mt-[-73px]">
                </div>
            </div>
        </div> 
      </section>
      <section>
            <div class="container mx-auto mt-24">
                <div class="flex p-10 justify-center items-center">
                    <div class="w-1/2 ml-10 bg-gray-100 p-5 pt-10">
                        <nuxt-link to="#" class="p-3 text-xl pl-4 pr-4 bg-gray-400 rounded-full">Dasturlash</nuxt-link>
                        <nuxt-link to="#" class="p-3 text-xl text-yellow-700 ml-5">Davomiylik: 19 soat 24 daqiqa</nuxt-link>
                        <nuxt-link to="#" class="p-3 text-xl text-yellow-700 ml-5">Darslar soni: 126 ta</nuxt-link>
                        <div class="flex justify-center items-center mt-5">
                            <div class="w-1/2">
                                <h1 class="font-bold text-3xl">Dasturlash foundation</h1>
                                <p class="mt-5 text-justify text-xl">Foundation dasturlash kursida C va Python
                                    dasturlash tillari va ular orqali dasturlashning
                                    mantiq-mohiyati o’rgatiladi. Kurs davomida
                                    dasturlashning fundamental tushunchalari,
                                    dasturchining ishini yengillashtirib beradigan</p>
                            </div>
                            <div class="w-1/2">
                                <img src="../../images/kompyuter.png" alt="kompyuter" class="w-[90%] ml-10 h-[90%]">
                            </div>
                        </div>
                    </div>
                    <div class="w-1/2 ml-10 bg-gray-100 p-5 pt-10">
                        <nuxt-link to="#" class="p-3 text-xl pl-4 pr-4 bg-gray-400 rounded-full">Dasturlash</nuxt-link>
                        <nuxt-link to="#" class="p-3 text-xl text-yellow-700 ml-5">Davomiylik: 23 soat 7 daqiqa</nuxt-link>
                        <nuxt-link to="#" class="p-3 text-xl text-yellow-700 ml-5">Darslar soni: 93 ta</nuxt-link>
                        <div class="flex justify-center items-center mt-5">
                            <div class="w-1/2">
                                <h1 class="font-bold text-3xl">.NET mutaxassislik kursi</h1>
                                <p class="mt-5 text-justify text-xl">.NET mutaxassislik kursi yordamida universal
                                    C# dasturlash tilida ishlovchi va oʻz faoliyatida
                                    .NET platformasi va texnologiyalaridan
                                    foydalanuvchi dasturchiga aylaning. C#
                                    dasturlash tilining imkoniyatlari va qoʻllash</p>
                            </div>
                            <div class="w-1/2">
                                <img src="../../images/komp.png" alt="kompyuter" class="w-[90%] ml-10 h-[90%]">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
      </section>
      <section class="bg-gray-100">
        <div class="container mx-auto">
          <div class="flex">
            <div class="w-1/4 p-5">
                <img src="../images/logo.png" alt="Najot ta'lim" class="w-[90%]" />
                <p class="font-bold text-gray-600 text-justify mt-10">
                  Onlayn platformaga tegishli barcha materiallar "NAJOT TA‘LIM MARKAZI"
                  MCHJning mulki hisoblanadi. Ushbu materiallardan onlayn ta‘lim
                  olishdan tashqari nusxa ko‘chirish, tarqatish va boshqa maqsadlarda
                  foydalanish qonunan man etiladi.
                </p>
              </div>
              <div class="w-1/4 p-5 ml-5">
                <h1 class="text-2xl font-bold ml-10 mt-3">Ma'lumotlar</h1>
                <div class="mt-14 ml-10">
                  <nuxt-link to="#" class="text-blue-900 font-bold">FAQ</nuxt-link><br><br>
                  <nuxt-link to="#" class="text-blue-900 font-bold">Blog</nuxt-link><br><br>
                  <nuxt-link to="#" class="text-blue-900 font-bold">Ommaviy oferta</nuxt-link>
                </div>
              </div>
              <div class="w-1/4 p-5 ml-5">
                <h1 class="text-2xl font-bold mt-3">Ommabop kurslar</h1>
                <div class="mt-14">
                  <nuxt-link to="#" class="text-blue-900 font-bold">Dasturlash foundation</nuxt-link><br><br>
                  <nuxt-link to="#" class="text-blue-900 font-bold">.NET mutaxassislik kursi</nuxt-link><br><br>
                </div>
              </div>
              <div class="w-1/4 p-5 ml-5">
                <h1 class="text-2xl font-bold mt-3">Bizning loyihalar</h1>
                <div class="mt-14">
                  <nuxt-link to="#" class="text-blue-900 font-bold">Osmondagi bolalar</nuxt-link><br><br>
                  <nuxt-link to="#" class="text-blue-900 font-bold">0 dan 1 gacha</nuxt-link><br><br>
                  <nuxt-link to="#" class="text-blue-900 font-bold">Abutech</nuxt-link><br><br>
                  <nuxt-link to="#" class="text-blue-900 font-bold">Alohida mavzu</nuxt-link>
                </div>
              </div>
          </div>
          <!-- =============================================================================================== -->
          <div class="flex">
            <div class="w-1/4 p-5">
                <p class="font-bold text-gray-600 text-justify mt-10">© Najot ta'lim, 2023</p>
                <p class="font-bold text-gray-600 text-justify mt-3">Barcha huquqlar himoyalangan</p>
              </div>
              <div class="w-1/4 p-5 ml-5">
                <h1 class="text-2xl font-bold ml-10 mt-3">Toshkent shahri, Chilonzor-9,
                    Qatortol ko‘chasi</h1>
                <div class="mt-5 ml-10">
                  <nuxt-link to="#" class="text-blue-900 font-bold">Mo‘ljal: Rayhon milliy taomlari qarshi
                    tomoni, 1- va 2-uylar orqa tomoni.</nuxt-link><br>
                </div>
              </div>
              <div class="w-1/4 p-5 ml-5">
                <h1 class="text-2xl font-bold mt-3">Tarmoqlar:</h1>
                <div class="mt-10 flex">
                  <nuxt-link to="#"><img src="../images/telegram.png" alt="telegram" class="w-[30px]"></nuxt-link>
                  <nuxt-link to="#"><img src="../images/facebook.png" alt="facebook" class="w-[30px] ml-3"></nuxt-link>
                  <nuxt-link to="#"><img src="../images/youtube.png" alt="YouTube" class="w-[30px] ml-3"></nuxt-link>
                  <nuxt-link to="#"><img src="../images/instagram.png" alt="instagram" class="w-[30px] ml-3"></nuxt-link>
                  <nuxt-link to="#"><img src="../images/in.png" alt="LinkedIn" class="w-[30px] ml-3"></nuxt-link>
                </div>
              </div>
              <div class="w-1/4 p-5 ml-5">
                <h1 class="text-2xl font-bold mt-3">Telefon raqami:</h1>
                <div class="mt-10">
                  <nuxt-link to="#" class="text-blue-900 text-3xl font-bold">+998 (78) 888 9 888</nuxt-link>
                </div>
              </div>
          </div>
     
        </div>
      </section>
</template>

<style lang="scss" scoped>
</style>