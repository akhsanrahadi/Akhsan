<!DOCTYPE html>



<html>



<meta charset='UTF-8'/>

<meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5' name='viewport'/><script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script><link href="https://feeldreams.github.io/tutorkak/style.css" rel="stylesheet" type="text/css" />

<meta content='IE=edge' http-equiv='X-UA-Compatible'/>

 

<head>

<title>AKHSAN RAHADI</title>

<meta name="description" content="">

<meta name="keywords" content="">

<link rel="icon" type="image/x-icon" href="https://www.palingit.com/favicon.ico">

<!-- 

  

  Made with love by akhsan!

  

     Blog: https://PalingIT.com

     Instagram: @akhsanrahafi

     TikTok: @supersann

     Email: akhsanrahadiii@gmail.com

     

  Thanks to all <3

  

-->

  <link rel="preconnect" href="https://fonts.googleapis.com">

  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

  <link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@400;700&display=swap" rel="stylesheet">

</head>

<body>

	

   <!-- Ganti Audio di sini --><audio src="https://feeldreams.github.io/tutorkak/tutorkak.mp3" id="linkmp3"></audio><script>audio = new Audio('' + linkmp3.src);</script>

   

   <div id="bodyblur">

     <!-- Wallpaper --><img src="https://feeldreams.github.io/street22.jpeg" id="wallpaper"/>

   </div>



   <div id='Content'>

   	

     <div id="suratin">

       <!-- Tombol Surat --><img src="https://rayyscoding.github.io/envelope.png"/>

     </div>

     <p id="ket">Klik Pesannya!</p>

   

     <div>

         <!-- Stiker untuk Konten -->

         <img src="https://feeldreams.github.io/peachhug.gif" id="fotoakhir"/>

         <img src="https://feeldreams.github.io/peachhello.gif" id="fotoakhir1"/>

         <img src="https://feeldreams.github.io/peachspeech.gif" id="fotoakhir2"/>

         <img src="https://feeldreams.github.io/peachnaik.gif" id="fotoakhir3"/>

         <img src="https://feeldreams.github.io/peachmuter.gif" id="fotoakhir4"/>

         <img src="https://feeldreams.github.io/peachktw2.gif" id="fotoakhir5"/>

       

         <img src="https://feeldreams.github.io/peachhello.gif" id="fotoAkhir"/>

     </div>

     <div><blockquote id='bq'>

  

       <!-- Konten Penerapan -->

       <p id="kalimat">Tutor Dong Kak 👉👈</p>

       <p id="kalimata">Biar Masuk SW Kakak..</p>

       <p id="kalimatb">24 Jam,</p>

       <p id="kalimatc">Ga Dihapus 😆❤️</p>

       <p id="kalimatd">Ahahaha~</p>

       

       <!-- Konten Pertanyaan -->

       <p id="kalimat2">Tutor Dong wkwk 🤣❤️</p>



       <!-- Konten Jawaban -->

       <p id="kalimat3">Jawabanmu: </p>

       <p id="kalimatb3">Kirim ke WhatsApp aku ya!</p>

     </blockquote></div>

   

     <!-- Tombol Multifungsi -->

     <div id="Tombol">

       <a id="By" onClick="multifungsi()">

         <b id="tmbl">Lanjut</b>

         <b id="tmbl2">💌 Balas</b>

       </a>

     </div>

     

   </div>



<!-- Jangan Edit Bagian Ini --><script>

  async function menuju(){await swals.fire('OK!', 'Kirim pesan ke WhatsApp aku, ya!', 'success');window.location = "https://api.whatsapp.com/send?phone=6285749020837&text&type=phone_number&app_absen=0" + pesanwhatsapp;Tombol.style="margin-top:15px;opacity:1;transform: scale(1);";}



  const swalst = Swal.mixin({timer: 2777, allowOutsideClick: false, showConfirmButton: false, timerProgressBar: true, imageHeight: 100,}); const swals = Swal.mixin({allowOutsideClick: false, cancelButtonColor: '#FF0040', imageWidth: 100, imageHeight: 100,}); const body = document.querySelector("body");function createHeart() {const heart = document.createElement("div"); heart.className = "fas fa-heart"; heart.style.left = (Math.random() * 90)+"vw"; heart.style.animationDuration = (Math.random()*3)+2+"s"; body.appendChild(heart);} setInterval(function name(params) {var heartArr = document.querySelectorAll(".fa-heart"); if (heartArr.length > 100) {heartArr[0].remove()}},100); ftom=0;jikatom=0;ftganti=0;fungsi=0;

  

  function mulaikonten() {

    setTimeout(fmketik1,1700);setTimeout(mketik1,1700);

    setTimeout(fmketik2,3080);setTimeout(mketik2,3080);

    setTimeout(fmketik3,4700);setTimeout(mketik3,4700);

    setTimeout(fmketik4,6000);setTimeout(mketik4,6000);

    setTimeout(fmketik5,7000);setTimeout(mketik5,7100);

  }

  

  vketik=kalimat.innerHTML;kalimat.innerHTML = "";

  vketika=kalimata.innerHTML;kalimata.innerHTML = "";

  vketikb=kalimatb.innerHTML;kalimatb.innerHTML = "";

  vketikc=kalimatc.innerHTML;kalimatc.innerHTML = "";

  vketikd=kalimatd.innerHTML;kalimatd.innerHTML = "";



async function jawab(){

  var { value: jawaban } = await swals.fire({

    title: 'Tulis Pesan &#128073;&#128072;', input: 'text', allowOutsideClick: false, showCancelButton: false,

  });

  if(jawaban && jawaban.length < 19){

    window.jawaban = jawaban;

    pesanwhatsapp = jawaban;

    balasan = jawaban;

    otomatis3();setTimeout(stakhir,1000);

  } else {

    await swals.fire('Ups!', 'Jawaban tidak boleh kosong atau lebih dari 18 karakter, ya!');jawab();

  }

}

</script>

<script src="https://feeldreams.github.io/tutorkak/script.js"></script>

<!-- Sampai Sini -->

</body>

</html>
