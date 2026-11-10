# BedrockNBT

Editor NBT dan world Bedrock (.mcworld) yang jalan sepenuhnya di browser, dibuat untuk dipakai di HP.
Semua proses terjadi di perangkat, tidak ada file yang dikirim ke server.

## Fitur
- Buka `level.dat`, `.nbt`, `.mcstructure`, playerdata `.dat` (Java dan Bedrock terdeteksi otomatis)
- Tampilan tree seperti NBTExplorer: edit, tambah, duplikat, hapus, urungkan, cari
- Buka world Bedrock `.mcworld`: edit player, block entity, entity, dan `level.dat`
- Ekspor dan impor structure (`.mcstructure`) dari world
- Builder item: enchant (level sampai 32767), durabilitas, lore, item component, block, preset Structure Block
- Bisa dipasang sebagai PWA dan dipakai offline

## Pasang di GitHub Pages
1. Buat repository baru di GitHub, misalnya `bedrock-nbt` (Public).
2. Upload semua file di folder ini ke root repository (tombol Add file > Upload files).
3. Buka Settings > Pages. Di Source pilih Deploy from a branch, branch `main`, folder `/ (root)`, lalu Save.
4. Tunggu 1 sampai 2 menit. Alamatnya: `https://<username>.github.io/bedrock-nbt/`
5. Di Chrome HP, buka alamat itu lalu pilih menu > Add to Home screen.

## Catatan
- Selalu simpan cadangan world sebelum mengedit. Fitur tulis world bersifat eksperimental.
- Ekspor world menghasilkan `nama_edit.mcworld`, impor file itu ke Minecraft.
- Jalankan lewat https (GitHub Pages sudah https). Membuka `index.html` langsung dari file manager mungkin tidak mengaktifkan mode offline.
