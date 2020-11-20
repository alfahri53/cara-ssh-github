 # Cara Menggunakan SSH key untuk koneksi keGithub

Referensi jika ingin googling dengan kata kunci **github ssh key**.

## Mengapa menggunakan SSH?

* Alasan keamanan repository anda.
* Tidak repot menuliskan username dan password setiap kali **push & pull**.
* Lebih cepat akses keremote server.
* Cara kerjanya adalah Github mengindentifikasi laptop anda dengan key number.
 
 ## Cara Generate SSH baru dilaptop anda.
 
 Jika tidak yakin apakah anda sudah memiliki SSH key dilaptop?
 
 Cara cek SSH key dileptop anda, ketik dibawah ini:
 
  cat ~/.ssh/id_rsa.pub
  
  Apabila muncul seperti ini :
  
  ssh-rsa
  AAAAB3Nza.xxxxxxxxxxxxxxxyyyyyyyyyyyyyyzzzzzzzzzzzzzzzzzxxxxxxxxxxxxxxxxxxyyyyyyyyyyyyyyzzzzzzzzzzzzzzzzzxxxxxxxxxxxxxxyyyyyyyyyyyyyyyyyyyyyyzzzzzzzzzzzzzzzzzzzzzzz alfahri53