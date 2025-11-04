from time import sleep
print("selamat datang!, kamu yang ulang tahun \U0001F973:)")
sleep(4)
waktu = input("jam 12  5/11(saat ini) : ")
sleep(0.25)
nama = input("Queen Cina : ")
sleep(0.75)
umur = input("21 Tahun : ")
sleep (2)
print ("selamat datang", Queen)
sleep (1)
print(waktu)
sleep(4)
print("selamat ulang tahun ke-", 21 , Queen)
sleep(3)
print("         \U0001F525   \U0001F525")
print("          |    |")
sleep(1)
print("          |    |")
sleep(1)
print("       ------------")
sleep(1)
print("       |          |")
sleep(1)
print("       |          |")
sleep(1)
print("       ------------")
sleep(2)
print("  ----------------------")
sleep(1)
print("  |                    |")
sleep(1)
print("  |                    |")
sleep(1)
print("  ----------------------")
sleep(3)
print("semoga panjang umur,")
sleep(2)
print("sehat selalu, dan bisa membanggakan orang tua \U0001F44D \U0001F44D")
sleep(3)
print("aku akan selalu mendoa'kan yang terbaik untuk kamu")      id="kartu"
    >
      <h1 class="text-3xl">Happy Birthday</h1>
      <h3
        class="text-4xl font-bold text-blue-500 animate__animated animate__infinite animate__pulse"
      >
        Queen Koding
      </h3>
      <button
        href="ucapan.html"
        class="animate__animated animate__delay-1s animate__tada p-2 bg-blue-600 text-white rounded mt-5 hover:bg-blue-900 transition ease-in w-full"
        onclick="ubahKartu()"
      >
        Klik Disini
      </button>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/@tsparticles/confetti@3.0.3/tsparticles.confetti.bundle.min.js"></script>
    <script>
      let kartu = document.getElementById("kartu");
      function ubahKartu() {
        kartu.innerHTML = `<h1 class="font-semibold text-wrap animate__animated animate__zoomIn">Selamat ulang tahun, bro! Semoga tahun ini makin banyak kebahagiaan, rezeki lancar, dan segala impian jadi kenyataan. Semoga kita terus bisa bareng-bareng, seru-seruan, dan saling dukung ya! 🎉🎂<h1>
        <h2 class="mt-3 animate__animated animate__fadeIn">- Dari : Queen Cina 🇨🇳 -</h2>
        <button onclick="refresh()" class="animate__animated animate__delay-1s animate__tada p-2 bg-slate-600 text-white rounded mt-5 hover:bg-slate-900 transition ease-in w-full">Tutup</button>
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
</html>
