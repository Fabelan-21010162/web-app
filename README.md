
# CATATAN APLIKASI SIMPEL
  ◉ Simple Notes App adalah aplikasi web sederhana berbasis HTML dan JavaScript yang memungkinkan pengguna:

- Menulis catatan dalam text area (kotak teks besar)
- Menyimpan catatan tersebut (simulasi penyimpanan)
- Bisa dijalankan langsung dari browser



# Aplikasi web sederhana berbasis HTML dan JavaScript

- Tampilan sederhana: hanya ada judul, textarea, dan tombol "Simpan Catatan"
- Interaktif: ketika tombol ditekan, muncul notifikasi bahwa catatan telah disimpan (simulasi)
-  Bebas backend: aplikasi ini hanya HTML dan JS, tidak memerlukan server atau database

## Codingan Program:

```cpp
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Notes App</title>
</head>
<body>
    <h1>Simple Notes App</h1>
    <textarea rows="10" cols="30" placeholder="Tulis catatan Anda di sini..."></textarea>
    <br><br>
    <button onclick="saveNote()">Simpan Catatan</button>
    <script>
        function saveNote() {
            alert("Catatan disimpan (simulasi)!");
        }
    </script>
</body>
</html>
