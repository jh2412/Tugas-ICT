<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <title>Blog Computational Thinking & Programming C</title>
  <style>
    body { font-family: Arial, sans-serif; background: #f0f4f8; margin: 0; padding: 20px; }
    header { background: #4a90e2; color: white; padding: 20px; text-align: center; border-radius: 8px; }
    article { background: #fffacd; padding: 20px; margin-top: 20px; border-radius: 8px; box-shadow: 0 2px 6px rgba(0,0,0,0.1); }
    h1, h2 { color: #333; }
    p { line-height: 1.6; color: #555; }
    pre { background: #eee; padding: 10px; border-radius: 6px; overflow-x: auto; }
    code { font-family: monospace; }
  </style>
</head>
<body>

<header>
  <h1>Computational Thinking & Programming Algorithms with C</h1>
</header>

<article id="content"></article>

<div class="profile">
  <img src="IMG_1791.JPG" width="200" height="150">
  <h3>Nama: Rochelle Alinz Calista</h3>
  <p>Tugas: Coding</p>
</div>

<div class="profile">
  <img src="367d6929-0018-4753-8fae-ac953b89e453.JPG" width="150" height="200">
  <h3>Nama: Valerie Shallvyn</h3>
  <p>Tugas: Presentasi</p>
</div>

<div class="profile">
  <img src="0112b6cd-d3b8-4f5a-af00-f5c640dfe29e.JPG" width="150" height="200">
  <h3>Nama: Kelsey Sarita Phelia</h3>
  <p>Tugas: Menncari Informasi</p>
</div>

<div class="profile">
  <img src="f2519753-cf54-4bb5-a7af-2dbd69ac4792.JPG" width="150" height="200">
  <h3>Nama: Carissa Kirana Tanson</h3>
  <p>Tugas: Mencari Informasi</p>
</div>

<script>
  const articleContent = `
    <h2> Apa Itu Computational Thinking?</h2>
    <p> Computational thinking adalah cara berpikir sistematis untuk menyelesaikan masalah dengan memecah masalah besar menjadi bagian kecil, mengenali pola, menyederhanakan masalah dengan fokus pada hal penting, dan merancang langkah-langkah penyelesaian (algoritma).Pendekatan ini membantu mengubah masalah yang kompleks menjadi solusi yang lebih mudah dipahami dan diimplementasikan, terutama dalam pemrograman dan pengembangan teknologi.</p>
    
    <h2> Langkah-langkah Computational Thinking </h2>
    <ul>
      <li>Decomposition (Pemisahan masalah menjadi bagian kecil)</li>
      <li>Pattern Recognition (Mengenali pola)</li>
      <li>Abstraction (Menyederhanakan masalah dengan mengabaikan detail yang tidak perlu)</li>
      <li>Algorithm Design (Merancang langkah demi langkah penyelesaian masalah)</li>
    </ul>

    <h2> Algoritma dalam Bahasa C</h2>
    <p> Algoritma dalam bahasa C adalah serangkaian langkah logis dan sistematis yang dirancang untuk menyelesaikan suatu masalah atau tugas tertentu. Algoritma ini diterjemahkan ke dalam kode bahasa C agar dapat dijalankan komputer. Contohnya, algoritma untuk mencari nilai maksimum dari dua angka melibatkan langkah membandingkan kedua angka dan mengembalikan nilai yang lebih besar. Dalam kode C, ini bisa ditulis dengan fungsi sederhana yang menggunakan perintah <code>if</code> atau operator ternary, sehingga program bisa menentukan nilai maksimum dengan cepat dan efisien. Algoritma sangat penting dalam pemrograman karena membantu programmer memikirkan solusi secara terstruktur sebelum membuat kode, memastikan program berjalan dengan tepat dan optimal.</p>
    
    <p> Contohnya, algoritma sederhana untuk mencari nilai maksimum antara dua angka bisa ditulis seperti ini: </p>
    <pre><code>
int max(int a, int b) {
  return (a > b)? a: b;
}
    </code></pre>

    <p> Jadi, algoritma membantu kita merancang solusi sebelum dikodekan dalam bahasa C agar program berjalan sesuai tujuan. </p>
  `;

  var password = prompt('Masukkan password untuk mengakses halaman ini:');
  var pass1 = "kelompok3";
  if(password === pass1){
    alert('Password benar, selamat datang!');
    document.getElementById('content').innerHTML = articleContent;
  } else {
    alert('Password salah, kamu akan dialihkan.');
    window.location.href = "https://ppl-ai-file-upload.s3.amazonaws.com/ask-perplexity/whatsapp_uploads/6281288823870/22360ce3-c197-493c-9f14-7f318ba1bb32/5941549d-4545-4123-b6de-92fb790ea4a7.jpg";
  }
</script>

</body>
</html>
