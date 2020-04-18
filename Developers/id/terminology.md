---
title: Memahami dasar dari arsitektur dan APIs IdProo 
author: nugroho
description: Penjelasan sederhana tentang dasar dari arsitektur dan APIs IdProo 
ysi.author: nugroho
ysi.custom: idproo
ysi.date: 4/18/2020
uid: getting-started
---
Spesifikasi, dokumentasi, dan model objek pada IdProo menggunakan terminologi tertentu yang harus anda ketahui. IdProo mengimplementasikan protokol OpenID Connect dan OAuth 2.0 yang menyediakan token keamanan pada aplikasi klien.

IdProo memiliki pekerjaan dan fitur - termasuk:
* Melindungi sumber daya Anda
* Mengautentikasi pengguna yang disimpan sebagai akun lokal atau melalui penyedia identitas eksternal
* Menyediakan manajemen sesi dan sistem masuk tunggal
* Mengelola dan mengautentikasi klien
* Mengeluarkan identitas dan token akses ke klien
* Memvalidasi token

## Pengguna
Pengguna adalah manusia yang menggunakan klien terdaftar untuk mengakses sumber daya.

## Klien
Klien adalah perangkat lunak yang meminta token dari IdProo - baik untuk mengotentikasi pengguna (meminta token identitas) atau untuk mengakses sumber daya (meminta token akses). Klien harus terdaftar terlebih dahulu dengan IdProo sebelum meminta token.

Contoh untuk klien adalah aplikasi web, aplikasi seluler atau desktop asli, SPA, proses server, dll.

## Sumber daya
Sumber daya adalah sesuatu yang ingin Anda lindungi dengan IdProo - baik data identitas pengguna Anda, atau API.

Setiap sumber daya memiliki nama unik - dan klien menggunakan nama ini untuk menentukan sumber daya mana yang ingin mereka akses. 

Sumber daya API mewakili fungsionalitas yang ingin dijalankan oleh klien - biasanya dimodelkan sebagai API Web.

## Token Identitas
Token identitas mewakili hasil dari proses otentikasi. Berisi minimal pengidentifikasi untuk pengguna (disebut sub alias klaim subjek) dan informasi tentang bagaimana dan kapan pengguna diautentikasi.

## Token Akses
Token akses memungkinkan akses ke sumber daya API. Klien meminta token akses dan meneruskannya ke API. Token akses berisi informasi tentang klien dan pengguna (jika ada). API menggunakan informasi itu untuk mengotorisasi akses ke data mereka.
