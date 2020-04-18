---
title: "Kontribusi"
description: "Cara ikut berkontribusi di web Indo-R"
date: 2020-04-18
tags: ["kontribusi", "artikel"]
weight: 1
draft: false
---

## Langkah awal

Web ini dibangun secara gotong-royong menggunakan *static page generator* [Hugo](https://gohugo.io/) yang dikelola melalui R menggunakan paket blogdown dan *version control* git. Sehingga untuk ikut berkontribusi dalam mengembangkan web komunitas ini, ada beberapa hal yang perlu dipersiapkan untuk bisa membangun web lewat '.Rproj'.

### Prasyarat

- R
- RStudio
- Paket blogdown
- Git dan akun Github
- Hugo (bisa dipasang menggunakan paket blogdown: `blogdown::install_hugo()`)

Bila prasyarat ini sudah terpenuhi, berikutnya teman-teman bisa ikut berkontribusi dalam hal apapun.

Untuk langkah awal, berikut yang perlu teman-teman lakukan:

1. *Fork* repositori ini dari [sumber utama](https://github.com/indo-r/r-indonesia.id) di Github R Indonesia
2. *Clone* repositori hasil *fork* yang tersimpan di akun Github ke komputer lokal
3. Kelola proyek melalui berkas 'indo-r.github.io.Rproj' dari RStudio

## Kolaborasi artikel

Konten artikel bisa dibuat melalui RStudio dengan langkah berikut:

1. Buka berkas 'indo-r.github.io.Rproj' dari RStudio
2. Buat konten dengan klik 'Addins - New Post'.
3. Pilih archetypes 'post' jika ingin menambahkan konten berupa artikel blog, atau 'project' untuk konten berupa laman proyek
4. Buat perubahan yang diperlukan untuk situs web
5. Jalankan kode `blogdown::build_site()`
6. Jalankan perintah berikut melalui terminal di RStudio
```
git add --all
git commit -m "pesan perubahan"
git push origin master
```
7. Buat *pull-request* ke repositori indo-r/laman-web

## Kontributor

- [Muhammad Aswan Syahputra](mailto:aswansyahputra@sensolution.id)
- [Aep Hidayatuloh](https://github.com/aephidayatuloh)
- [Andi Herlan](https://github.com/akherlan)