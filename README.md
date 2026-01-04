# Adimology - Kalkulator Target Saham 📈

Adimology adalah aplikasi web sederhana yang dirancang untuk membantu investor saham, baik pemula maupun berpengalaman, dalam menganalisis target harga saham. Aplikasi ini menggunakan data transaksi broker (bandarmologi) dari Stockbit untuk menghitung potensi pergerakan harga saham.

## 🌟 Fitur Utama

- **Analisis Target Cerdas**: Menghitung target harga "Realistis" dan "Maksimal" berdasarkan rata-rata harga pembelian broker.
- **Data Terintegrasi Stockbit**: Mengambil data transaksi broker secara real-time dari Stockbit untuk akurasi analisis.
- **Ringkasan Broker**: Menampilkan ringkasan akumulasi broker (Top 1, Top 3, dan Top 5) untuk melihat kekuatan pembeli vs penjual.
- **Kalkulator Potensi**: Melihat persentase potensi keuntungan (upside) dan risiko (downside) dari harga pasar saat ini.

## 🚀 Cara Menggunakan

1. **Buka Aplikasi**: Jalankan aplikasi di browser Anda.
2. **Masukkan Kode Saham**: Ketik kode saham yang ingin dianalisis (contoh: `BBCA`, `TLKM`, `GOTO`) pada kolom input.
3. **Pilih Rentang Waktu** (Opsional): Jika tersedia, pilih rentang waktu analisis.
4. **Klik Analyze**: Tekan tombol untuk memulai analisis.
5. **Baca Hasil**:
   - **Broker Summary**: Lihat siapa broker yang paling banyak membeli/menjual.
   - **Result Table**: Bandingkan harga pasar saat ini dengan rata-rata harga broker.
   - **Target Price**: Lihat prediksi harga target realistis dan maksimal.

---

## 💻 Untuk Pengembang (Getting Started)

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

### Menjalankan Aplikasi Secara Lokal

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

### Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

### Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
