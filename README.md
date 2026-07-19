# 🎓 KampusSwap DEX (Decentralized Exchange)

KampusSwap adalah aplikasi *Decentralized Exchange* (DEX) mini berbasis Web3 yang dibangun sebagai proyek eksperimental untuk memahami cara kerja *Automated Market Maker* (AMM), integrasi *Smart Contract* di jaringan Ethereum (EVM), dan eksplorasi tren **Vibecoding** menggunakan kecerdasan buatan (AI) dalam pengembangan *frontend*.

## 🚀 Fitur Utama
*   **Token Swap:** Menukar token kripto secara terdesentralisasi menggunakan *smart contract* (pengujian rumus `x * y = k`).
*   **Token Approval (ERC20):** Implementasi standar keamanan Web3 yang mewajibkan izin (*approve*) sebelum aset dapat ditarik oleh *pool* likuiditas.
*   **Modern UI/UX:** Antarmuka responsif dengan efek *Glassmorphism* dan *Dark Mode*, dirancang menggunakan pendekatan Vibecoding dan Tailwind CSS.
*   **Wallet Connection:** Terhubung dengan dompet digital Web3 untuk membaca saldo dan mengeksekusi transaksi secara *on-chain*.

## 🛠️ Tech Stack
*   **Frontend:** React.js, Tailwind CSS, Wagmi
*   **Backend / Blockchain:** Solidity, Ethereum Virtual Machine (EVM), Sepolia Testnet
*   **Development Tools:** Hardhat / Foundry (untuk kompilasi contract), AI Assistants (untuk Vibecoding)

## 📖 Artikel & Studi Kasus
Proyek ini tidak hanya sebatas kode, tetapi juga merupakan sebuah studi kasus mengenai bagaimana AI mulai mengubah cara *developer* bekerja. 

Saya telah mendokumentasikan pengalaman dan analisis teknis dari eksperimen ini ke dalam sebuah artikel:
👉 **[Mengenal Vibecoding, Tren Masa Depan Developer Web3 Bikin Aplikasi Pakai AI - ON PROGRESS](masukkan-link-kumparan-kamu-di-sini)**

**Sorotan Pembahasan di Artikel:**
1. Apa itu Vibecoding dan bagaimana AI mempercepat desain antarmuka Web3.
2. Mengapa kalkulasi AI (*floating point*) bisa meleset saat dihadapkan dengan mesin EVM (*integer truncation*).
3. Pentingnya validasi manusia terhadap logika *smart contract* untuk menghindari kerugian akibat *slippage* dan kegagalan transaksi finansial.

## 💻 Cara Menjalankan Aplikasi Secara Lokal

Jika Anda ingin menjalankan aplikasi ini di komputer Anda, ikuti langkah-langkah berikut:

1. Kloning repositori ini:
   ```bash
   git clone [https://github.com/akbrff/kampusswap-dex.git](https://github.com/akbrff/kampusswap-dex.git)
