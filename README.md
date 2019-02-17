# Blog Kolaborasi Komunitas R Indonesia

**Pra-syarat:**

* R
* RStudio
* Paket blogdown
* git
* Hugo (bisa dipasang menggunakan paket blogdown: `blogdown::install_hugo()`

**Cara kolaborasi:**

1. *Fork* repositori ini
2. *Clone* *forked-repository* ke repositori lokal
3. Buka berkas 'indo-r.github.io.Rproj'
4. Buat konten dengan klik 'Addins - New Post' pada RStudio. Pilih archetypes 'post' jika ingin menambahkan konten berupa blog dan 'project' untuk konten berupa (laman) proyek
5. Buat perubahan yang diperlukan untuk situs web
6. Jalankan rutin
```
git add -all
git commit -m "pesan perubahan"
git push origin master
```
7. Buat *pull-request* ke repositori indo-r/laman-web

**Kebutuhan saat ini:**
1. Konten tulisan
2. Kustomusasi UI (jika dianggap perlu)
