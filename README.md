# ReapeR-MizaH
![banner-logo](https://github.com/user-attachments/assets/a71e4319-bc97-447c-83b7-815e5ab9837d)
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ReapeR Quiz</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #111;
      color: #eee;
      margin: 0;
      padding: 0;
    }
  
    }
    .container {
      max-width: 800px;
      margin: auto;
      padding: 20px;
    }
    h1 {
      text-align: center;
      color: #ff6f61;
    }
    form {
      margin-top: 20px;
    }
    .question {
      margin-bottom: 30px;
    }
    .question h3 {
      color: #ffcc00;
    }
    .result {
      margin-top: 30px;
      font-weight: bold;
      font-size: 1.2em;
      text-align: center;
    }
    button {
      padding: 10px 20px;
      font-size: 16px;
      background-color: #ff6f61;
      color: white;
      border: none;
      cursor: pointer;
    }
    button:hover {
      background-color: #ff3b2e;
    }
  </style>
</head>
<body>
  <header></header>
  <div class="container">
    <h1>Gerçek Bir ReapeR Bağımlısı mısın?</h1>
    <p>Aşağıdaki 10 soruya dürüstçe cevap ver ve ReapeR dünyasındaki yerini öğren!</p>
    <form id="quizForm">
      <div class="question">
        <h3>1. Bu sunucunun kurulma tarihi nedir?</h3>
        <label><input type="radio" name="q1" value="0" /> a) 23 Nisan 1923</label><br />
        <label><input type="radio" name="q1" value="0" /> b) 7 Eylül 2017</label><br />
        <label><input type="radio" name="q1" value="0" /> c) 1 Mayıs 2018</label><br />
        <label><input type="radio" name="q1" value="10" /> d) 25 Şubat 2019</label>
      </div>
      <div class="question">
        <h3>2. Daha önce yönetimde yer almış fakat sonrasında yollarını ayırmış üyelere hangi rol verilir?</h3>
        <label><input type="radio" name="q2" value="0" /> a) Hedylogos</label><br />
        <label><input type="radio" name="q2" value="0" /> b) Loyal Yenge</label><br />
        <label><input type="radio" name="q2" value="10" /> c) Emekli</label><br />
        <label><input type="radio" name="q2" value="0" /> d) Anbu</label>
      </div>
      <div class="question">
        <h3>3. ReapeR'da Owner'dan sonra gelen en yüksek yetki rolü hangisidir?</h3>
        <label><input type="radio" name="q3" value="0" /> a) Colleague</label><br />
        <label><input type="radio" name="q3" value="0" /> b) Admin</label><br />
        <label><input type="radio" name="q3" value="0" /> c) Manager</label><br />
        <label><input type="radio" name="q3" value="10" /> d) Mugen no Kage</label>
      </div>
      <div class="question">
        <h3>4. Güncel olarak ReapeR yönetim kadrosunda kaç kişi bulunmaktadır?</h3>
        <label><input type="radio" name="q4" value="10" /> a) 9</label><br />
        <label><input type="radio" name="q4" value="0" /> b) 4</label><br />
        <label><input type="radio" name="q4" value="0" /> c) 5</label><br />
        <label><input type="radio" name="q4" value="0" /> d) 7</label>
      </div>
      <div class="question">
        <h3>5. Aşağıdaki emojilerden hangisi ReapeR sunucusunda yasaklanmıştır?</h3>
        <label><input type="radio" name="q5" value="0" /> a) Şeftali 🍑</label><br />
        <label><input type="radio" name="q5" value="0" /> b) Kiraz 🍒</label><br />
        <label><input type="radio" name="q5" value="10" /> c) Ayak 🦶</label><br />
        <label><input type="radio" name="q5" value="0" /> d) Öpücük 💋</label>
      </div>
      <div class="question">
        <h3>6. Toplam ceza puanı 5 olan biri, kaç saat susturulma cezası alır?</h3>
        <label><input type="radio" name="q6" value="0" /> a) 2 hafta</label><br />
        <label><input type="radio" name="q6" value="0" /> b) 1 hafta</label><br />
        <label><input type="radio" name="q6" value="0" /> c) 8 saat</label><br />
        <label><input type="radio" name="q6" value="10" /> d) 5 saat</label>
      </div>
      <div class="question">
        <h3>7. ReapeR Moments için mizahi editler hazırlayan üyelere hangi rol verilir?</h3>
        <label><input type="radio" name="q7" value="0" /> a) Editor</label><br />
        <label><input type="radio" name="q7" value="10" /> b) Mizahşör</label><br />
        <label><input type="radio" name="q7" value="0" /> c) Hedylogos</label><br />
        <label><input type="radio" name="q7" value="0" /> d) Pollster</label>
      </div>
      <div class="question">
        <h3>8. Etkinlik kategorisindeki kanallarda en çok vakit geçiren ilk 3 üyeye verilen rol nedir?</h3>
        <label><input type="radio" name="q8" value="10" /> a) Katsudo</label><br />
        <label><input type="radio" name="q8" value="0" /> b) Kaiteki</label><br />
        <label><input type="radio" name="q8" value="0" /> c) Ayın Aktifi (yazılı)</label><br />
        <label><input type="radio" name="q8" value="0" /> d) Event Manager</label>
      </div>
      <div class="question">
        <h3>9. Anket kanallarında son 7 gün içerisinde en aktif ilk 3 üyeye verilen rol nedir?</h3>
        <label><input type="radio" name="q9" value="0" /> a) Forum Yerlisi</label><br />
        <label><input type="radio" name="q9" value="0" /> b) Kaiteki</label><br />
        <label><input type="radio" name="q9" value="0" /> c) Pollster</label><br />
        <label><input type="radio" name="q9" value="10" /> d) Seçkin Yorumcu</label>
      </div>
      <div class="question">
        <h3>10. ReapeR Elite rolünü almak için aşağıdakilerden hangisi gerekli <u>değildir</u>?</h3>
        <label><input type="radio" name="q10" value="0" /> a) Eien no Reaper</label><br />
        <label><input type="radio" name="q10" value="0" /> b) Seri 50</label><br />
        <label><input type="radio" name="q10" value="10" /> c) Değerli Destekçilerimiz</label><br />
        <label><input type="radio" name="q10" value="0" /> d) Voice 20 Level</label>
      </div>
      <div style="text-align: center;">
        <button type="button" onclick="calculateScore()">Gönder ve Skorunu Gör!</button>
      </div>
    </form>
    <div class="result" id="result"></div>
  </div>
  <script>
    function calculateScore() {
      let score = 0;
      const form = document.forms["quizForm"];
      for (let i = 1; i <= 10; i++) {
        const answer = form[`q${i}`].value;
        if (answer) score += parseInt(answer);
      }
      let message = "";
      if (score >= 85) {
        message = `🔱 <b>${score} puan</b>: Gerçek bir <span style="color: #ffcc00">ReapeRist</span>!<br>Sen bu sunucunun hem hafızası hem ruhusun! Osman bile seninle gurur duyar.`;
      } else if (score >= 65) {
        message = `✨ <b>${score} puan</b>: Takılıyorsun ama biraz daha aktif olmalısın!<br>Seslere gir, muhabbet et, zaptoya sataş... ReapeR seni bekliyor.`;
      } else {
        message = `🌱 <b>${score} puan</b>: Henüz bir ReapeRist sayılmazsın ama...<br>Potansiyel var! Biraz daha aktif takıl, kim bilir belki bir gün sen de yönetimin bir parçası olursun!`;
      }
      document.getElementById("result").innerHTML = message;
    }
  </script>
</body>
</html>

   
