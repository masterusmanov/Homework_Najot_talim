<script setup></script>

<template>
  <section class="bg-gray-100 h-[90px]">
    <div class="container mx-auto justify-center items-center w-full h-[70px]">
      <div class="grid-container justify-center items-center relative ">
        <div class="column inline-block w-[50%] h-[70px]">
          <img src="../images/logo.png" alt="" class="w-[40%] pt-5">
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
                ><img src="../images/Dark_mode.svg" alt="" class="w-16"
              /></nuxt-link>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </section>
  <section class="bg-gray-100 pb-14">
   <div class="container mx-auto pt-28">
      <img src="../images/main_img.png"  alt="rasm" >
       <div class="w-1/2  font-bold absolut justify-center items-center mt-[-400px]">
           <h1 class="text-5xl mt-2">Kasblarni</h1>
           <h1 class="text-5xl mt-2 text-yellow-800">onlayn</h1>
           <h1 class="text-5xl mt-2">o'rganing</h1>
           <p class="text-blue-400 mt-10 w-[90%]">O'zingizga qulay vaqtda, joyda va uslubda zamonaviy kasblarni o'rganing</p>
           <button class="p-4 rounded-full  bg-yellow-600 text-white w-48 mt-14">Kurslarni ko'rish</button>
       </div>
   </div>
</section>
<section class="mx-auto mt-10 p-2">
   <div class="container mx-auto">
      <h1 class="mt-24 text-5xl font-bold">Bizning afzalliklarimiz</h1>
      <div class="flex justify-center items-center mt-14 ">
          <div class="w-1/2 text-center flex">
              <div class="w-1/4">
                  <img src="../images/academiya.png" alt="" class="p-4">
              </div>
              <div class="w-1/2">
                  <h1 class="text-justify text-2xl font-bold ">Onlayn akademiya</h1>
                  <p class="text-justify mt-5">«Najot Ta’lim» digital academy — bu zamonaviy kasblar o‘qitiladigan onlayn
                      akademiya. Qayerda bo‘lishingizdan qat’i nazar: uydami yo mehmonda,
                      daladami yo safarda — o‘zingizga qulay tarzda va vaqtda bilim olishingiz
                      mumkin, internet va noutbuk bo‘lsa bas.</p>
              </div>
          </div>
          <div class="w-1/2 text-center flex">
              <div class="w-1/4">
                  <img src="../images/academiya2.png" alt="" class="p-4">
              </div>
              <div class="w-1/2">
                  <h1 class="text-justify text-2xl font-bold ">O‘z ishining ustalari</h1>
                  <p class="text-justify mt-5">Darslar katta tajribaga ega malakali mutaxassislar tomonidan tayyorlangan.
                      O‘z ishining ustalaridan yanada ishonchli bilim va tajribaga ega bo’lasiz</p>
              </div>
          </div>
      </div>
      <div class="flex justify-center items-center mt-14 ">
          <div class="w-1/2 text-center flex">
              <div class="w-1/4">
                  <img src="../images/academiya.png" alt="" class="p-4">
              </div>
              <div class="w-1/2">
                  <h1 class="text-justify text-2xl font-bold ">Shunchaki kurs emas</h1>
                  <p class="text-justify mt-5">Darslarni o‘zlashtirish davrida sizda savollar tug‘ilishi tabiiy holat.
                      Mentorlarga murojaat qilishingiz, o’zingizni qiziqtirgan savollarizga javob
                      olishingiz va tavsiyalar olishingiz mumkin</p>
              </div>
          </div>
          <div class="w-1/2 text-center flex">
              <div class="w-1/4">
                  <img src="../images/academiya4.png" alt="" class="p-4">
              </div>
              <div class="w-1/2">
                  <h1 class="text-justify text-2xl font-bold ">Onlayn akademiya</h1>
                  <p class="text-justify mt-5">Darslarni o‘zlashtirish davrida sizda savollar tug‘ilishi tabiiy holat.
                      Mentorlarga murojaat qilishingiz, o’zingizni qiziqtirgan savollarizga javob
                      olishingiz va tavsiyalar olishingiz mumkin</p>
              </div>
          </div>
      </div>
      <div class="mt-14"><span class="text-blue-500 font-bold">Ko'proq</span><select name="select" id=""></select></div>
   </div>
</section>
<section class="mx-auto  mt-10 p-2 bg-purple-200">
   <div class="container mx-auto">
      <h1 class="mt-10 text-5xl font-bold">Yo‘nalishlar bo‘yicha kurslar</h1>
   <p class="text-cyan-950 font-bold mt-10">Zamonaviy sohalardan birini o‘rganing va talabgir kasb egasi bo‘ling!</p>
   <div class="flex justify-beetwen items-center mt-10">
       <div class="w-1/4 border border-gray-600 p-5">
           <h1 class="text-2xl font-bold">Dasturlash foundation</h1>
           <a href="#" class="text-blue-600">Foundation dasturlash kursida</a>
       </div>
       <div class="w-1/4 border border-gray-600 p-5 ml-10">
           <h1 class="text-2xl font-bold"><b class="text-blue-900">.NET</b> mutaxassislik kursi</h1>
           <a href="#" class="text-blue-600">.NET mutaxassislik kursi</a>
       </div>
   </div>
   <div class="mt-5 mb-10">
       <a href="#" class="text-blue-900 font-bold">Barcha kurslarni ko‘rish</a>
   </div>
   </div>
</section>
<section>
   <div class="container mx-auto">
      <h1 class="mt-24 text-5xl font-bold">Bitiruvchilarimizning ish joylari:</h1>
   <p class="text-blue-900 mt-10">Eng yaxshi bitiruvchilarimiz nufuzli tashkilot va kompaniyalarda faoliyat yuritadi. Zamonaviy kasb egalariga doim va har yerda talab yuqori bo‘ladi.</p>
   <div class="flex mt-10">
       <div class="w-1/6 bg-gray-100 m-4">
           <img src="../images/epam.png" alt="" class="p-3">
       </div>
       <div class="w-1/6 bg-gray-100 m-4">
           <img src="../images/techart.png" alt="" class="p-3">
       </div>
       <div class="w-1/6 bg-gray-100 m-4">
           <img src="../images/humo.png" alt="" class="p-3">
       </div>
       <div class="w-1/6 bg-gray-100 m-4">
           <img src="../images/agrobank.png" alt="" class="p-3">
       </div>
       <div class="w-1/6 bg-gray-100 m-4">
           <img src="../images/davrbank.png" alt="" class="p-3">
       </div>
       <div class="w-1/6 bg-gray-100 m-4">
           <img src="../images/texnomart.png" alt="" class="p-3">
       </div>
   </div>
   <div class="flex">
       <div class="w-1/6 bg-gray-100 m-4">
           <img src="../images/soliq.png" alt="" class="p-3">
       </div>
       <div class="w-1/6 bg-gray-100 m-4">
           <img src="../images/uzcard.png" alt="" class="p-3">
       </div>
       <div class="w-1/6 bg-gray-100 m-4">
           <img src="../images/mytaxi.png" alt="" class="p-3">
       </div>
       <div class="w-1/6 bg-gray-100 m-4">
           <img src="../images/mfaktor.png" alt="" class="p-3">
       </div>
       <div class="w-1/6 bg-gray-100 m-4">
           <img src="../images/jaftan.png" alt="" class="p-3">
       </div>
       <div class="w-1/6 bg-gray-100 m-4">
           <img src="../images/fidostudio.png" alt="" class="p-3">
       </div>
   </div>
   <div class="flex">
       <div class="w-1/6 bg-gray-100 m-4">
           <img src="../images/osmondagibolalar.png" alt="" class="p-3">
       </div>
       <div class="w-1/6 bg-gray-100 m-4">
           <img src="../images/islomuz.png" alt="" class="p-3">
       </div>
       <div class="w-1/6 bg-gray-100 m-4">
           <img src="../images/cambradge.png" alt="" class="p-3">
       </div>
       <div class="w-1/6 bg-gray-100 m-4">
           <img src="../images/kunuz.png" alt="" class="p-3">
       </div>
       <div class="w-1/6 bg-gray-100 m-4">
           <img src="../images/yoshlar.png" alt="" class="p-3">
       </div>
       <div class="w-1/6 bg-gray-100 m-4">
           <img src="../images/pcg.png" alt="" class="p-3">
       </div>
   </div>
   </div>
</section>
<section class="mx-auto mt-10 p-2 mb-24">
   <div class="container mx-auto">
      <form action="">
         <div class="flex bg-gray-200 rounded-2xl">
             <div class="w-1/2">
                 <img src="../images/operator.png" alt="">
             </div>
             <div class="w-1/2 p-10">
               <div class="w-[90%] bg-white p-5 rounded-[20px] mt-10 ml-8">
                 <h1 class="mt-10 text-4xl ml-10">Yordam kerakmi?</h1>
                 <p class="text-blue-900 mt-10 ml-10 text-lg"><b class="text-yellow-700">FAQ</b> boʻlimi ham sizga yordam bera olmadimi?
                     Telefon raqamingizni yozib qoldiring, biz sizga
                     qoʻngʻiroq qilamiz va birorta ham savolingiz javobsiz
                     qolmasligiga harakat qilamiz.</p>
                 <div class="mt-10 ml-10">
                     <label for="" class="mt-10 text-lg font-bold">Ismingizni kiriting!</label><br>
                     <input type="text" placeholder="Ismingizni kiriting!" class="p-4 mt-5 w-[80%] border rounded-full">
                 </div>
                 <div class="mt-10 ml-10">
                     <label for="" class="mt-10 text-lg font-bold">Telefon raqamingizni kiriting!</label><br>
                     <input type="text" placeholder="00 000 00 00" class="p-4 pl-16 mt-5 w-[70%] text-xl border rounded-full relative">
                     <p class="absolute text-2xl ml-1 font-bold mt-[-48px]" >+998</p>
                 </div>
                 <div class="mt-14 ml-10 mb-10">
                     <p class="absolute font-bold">"So'rov yuborish" tugmasini bosish orqali <br>
                         <b class="text-yellow-700">Platformadan foydalanish qoidalari</b>ga rozilik bildirasiz. </p>
                      <button class="p-4 rounded-full  bg-yellow-600 text-white w-[80%] mt-28">So'rov yuborish</button>
                 </div>
               </div>
             </div>
         </div>
     </form>
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

<style lang="scss" scoped></style>
