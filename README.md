# websitebarokah
datawebsite

Login admin/admin123 untuk akses penuh, user/user123 untuk read-only.
Unggah logo di tab Admin (disimpan di localStorage).
Dashboard terbagi: Demografi (atas) & Laporan Keuangan (bawah), sekarang dengan saldo per kas (Insiba,Ronda,Donasi,Umum).
Pada tab Admin Anda dapat mengatur saldo awal per kas, lalu tambah transaksi dengan kategori.


<script type="module">
  // Import the functions you need from the SDKs you need
  import { initializeApp } from "https://www.gstatic.com/firebasejs/12.2.1/firebase-app.js";
  // TODO: Add SDKs for Firebase products that you want to use
  // https://firebase.google.com/docs/web/setup#available-libraries

  // Your web app's Firebase configuration
  const firebaseConfig = {
    apiKey: "AIzaSyC6s1V-g8KHNpJIjlSVTP7Twz4YLcjQtzY",
    authDomain: "database-barokah.firebaseapp.com",
    projectId: "database-barokah",
    storageBucket: "database-barokah.firebasestorage.app",
    messagingSenderId: "135687399675",
    appId: "1:135687399675:web:92bf5672e9b533e401285e"
  };

  // Initialize Firebase
  const app = initializeApp(firebaseConfig);
</script>
