<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Happy Birthday Rey dari Tibit</title>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
    />
    <script src="https://cdn.tailwindcss.com"></script>
  </head>
  
  <body
    class="flex justify-center items-center h-screen"
    style="
      background-image: url(https://i.pinimg.com/736x/50/5e/8e/505e8eb54f13df32462afc23242e1bf7.jpg);
      background-repeat: no-repeat;
      background-size: cover;
    "
  >
    <div
      class="border bg-white rounded-xl px-10 border-4 border-gray-300 py-8 shadow-lg shadow-red-300 text-center animate__animated animate__backInDown m-10 w-98"
      id="kartu"
    >
      <h1 class="text-3xl">Happy Birthday</h1>
      <h3
        class="text-10xl font-bold text-red-500 animate__animated animate__infinite animate__pulse"
      >
        REY🎉
      </h3>
      <button
        href="Buat Rey dari Tibit.html"
        class="animate__animated animate__delay-1s animate__tada p-2 bg-red-600 text-white rounded mt-5 hover:bg-red-900 transition ease-in w-full"
        onclick="ubahKartu()"
      >
        Click me-ow, please!
      </button>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/@tsparticles/confetti@3.0.3/tsparticles.confetti.bundle.min.js"></script>
    <script>
      let kartu = document.getElementById("kartu");
      function ubahKartu() {
        kartu.innerHTML = `<h1 class="font-semibold text-wrap animate__animated animate__zoomIn">Barakallah fii umrik, Rey! AYEEE, ada yang nambah umur nihh? Firstt, gw mau mengapresiasi semua kerja keras dan pencapaian lu sampai detik ini, honestly, you're SO cool, Rey. Oh ya IMO, you are such a good (silly) friend too, hahaha you should know thatt. So, here I'm really gonna pray for you (AAMIINKAN LOHYA), semogaa tahun ini makin banyak kebahagiaan, segala urusan maupun rezeki lancar, dan segala impian jadi kenyataan, there must be a big dream that you're chasing, and you have to believe that you can be whatever you want. Semoga panjang umur, sehat selalu (kalau lagi capek, tolong istirahat yang cukup, ok, you also need happiness, rest, and care) Semoga kita bisa terus seru-seruan bareng, dan saling dukung, ya! Masih banyak lagi do'a terbaik dari gw yang gabisa gw ketik disini, karena bakal panjang pake banget. Gw, kita semua very proud of you, Rey. Once again, HAPPY HAPPY B'DAY! KITA SEMUA SAYANG REY 🎉🎂<h1>
        <h2 class="mt-3 animate__animated animate__fadeIn">- Dari : Tibitfafa -</h2>
        <button onclick="refresh()" class="animate__animated animate__delay-1s animate__tada p-2 bg-slate-600 text-white rounded mt-5 hover:bg-slate-900 transition ease-in w-15000">SENYUUUMMM  :D</button>
          `;
      }
      confetti({
        particleCount: 200,
        spread: 70,
        origin: { y: 0.6 },
      });
      function refresh() {
        location.reload();
      }
    </script>
  </body>
