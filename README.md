# SHINING_HEART_TOOL
Tool buat unpack/repack file dari SHINING HEART iso.
# FAILED
Beberapa file gagal decompile, lihat failed.txt,
untuk .psb bisa edit menggunakan [FREEMOTE](https://github.com/UlyssesWu/FreeMote),
untuk .nut bisa edit manual mliteralnya saja(non decompile).
# EDIT NUT.TMP
Harap hati-hati dalam mengedit,
Jangan edit yang bukan string value.
dan tidak semua string juga tidak bisa diedit,
untuk sekarang yang diketahui bisa diedit:
- String dalam argumen szs_nameTalk(name","string"); untuk talk karakter.
- String dalam argumen szs_lips(int, "string",  "string", "string"); untuk multiple select.
- Control code diawali "＠" jangan diedit.
# EDIT PSB.JSON
Sama seperti NUT.TMP, lebih baik hanya edit string value saja.
# NEXT GOAL
- Texture encode/decode