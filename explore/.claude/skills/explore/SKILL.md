---
name: explore
description: Eksplorasi terstruktur sebuah topik, teknologi, atau codebase yang belum dikenal. Pakai saat user bilang "explore", "pelajarin", "jelasin struktur project ini", atau mau paham sesuatu dari nol.
---

# Explore

Bantu user memahami sesuatu yang baru dengan urutan dari gambaran besar ke detail.

## Langkah

1. **Tentukan target.** Kalau user belum jelas mau explore apa (folder, repo, library, konsep), tanya satu pertanyaan singkat. Kalau sudah jelas, langsung jalan.
2. **Gambaran besar.** Untuk codebase: baca README, struktur folder, file konfigurasi (package.json, requirements.txt, dll.). Untuk topik: cari definisi dan kegunaan utamanya.
3. **Peta.** Rangkum dalam 5-10 baris: tujuan, bagian-bagian utama, dan cara bagian itu saling terhubung.
4. **Alur utama.** Telusuri satu alur nyata dari awal sampai akhir (misalnya dari request masuk sampai respons keluar) dengan menyebut `file:baris`.
5. **Simpan catatan.** Tulis ringkasan ke `notes/<nama-topik>.md` supaya bisa dibaca lagi.
6. **Tutup dengan arah lanjut.** Kasih 2-3 hal menarik yang bisa digali berikutnya.

## Aturan
- Mulai dari yang paling umum, jangan langsung ke detail.
- Jelaskan istilah teknis saat pertama muncul.
- Jangan ubah file project yang di-explore; ini mode baca saja, kecuali menulis catatan di `notes/`.
- Kalau ada yang belum pasti, bilang terus terang, jangan menebak.

## Format jawaban
- **Intinya**: 1-2 kalimat
- **Peta**: daftar bagian utama
- **Alur**: langkah demi langkah
- **Lanjut ke mana**: saran berikutnya
