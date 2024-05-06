# Pemrograman Lanjut A
> Fadrian Yhoga Pratama - 2206819395

## Module 10 - Asynchoronous Programming - Broadcast Chat

## 2.1. Original code of broadcast chat
![2.1](assets/img/2.1.jpg)
Untuk menjalankan server adalah dengan membuka 1 terminal dan menjalankan `cargo run --bin server`. Kemudian untuk menjalankan 3 client adalah dengan membuka 3 terminal dan menjalankan `cargo run --bin client` pada masing-masing terminal. Setiap client yang dijalankan akan terhubung ke satu server. Setelah terhubung saya bisa mengetik sesuatu di salah satu terminal client dan client lain dapat melihat apa yang saya ketik sebelumnya karena telah dikirimkan oleh server.