'Modul 2: if, elif, dan else'

if = jika, else = jika tidak

Contoh, 
ada sebuah pohon apel, dan kita akan mengkategorikannya menjadi dua kemungkinan. Yang pertama matang dan yang kedua mentah. Saat memanen buah apel, kita melihat kondisinya, jika buah apel tersebut matang kita panen dan masukkan ke dalam keranjang. Jika buahnya masih mentah, jangan dipanen. Nah, kondisi tersebut bisa dilakukan menggunakan if-else

if apel == "matang":
  panen
else:
  diamkan

Nah, tapi, gimana kalo kondisinya ada 3? jika dari studi kasus sebelumnya, bagaimana jika ada kondisi apel yang busuk? itulah mengapa ada yang namanya elif. 

elif artinya sama seperti else, tapi bedanya dengan else, elif memiliki kondisi yang harus dipenuhi, sementara else setiap kondisi selain dari yang harus terpenuhi akan tetap dilakukan. 

Semisal dari studi kasus tadi, jika kita menggunakan else hasilnya jika apel itu busuk atau belum matang kita akan tetap mendiamkannya. Sementara jika kita menggunakan elif, sebagai kondisi tambahan jika ada kondisi busuk kita akan membuangnya. Contoh:

if apel == "Matang"
  panen
elif apel == "Busuk"
  buang
else
  diamkan

Dengan berdasarkan kondisi di atas, jika sebuah apel berada dalam kondisi matang, kita akan memanennya. Sementara jika apel dalam kondisi busuk, kita akan membuangnya, dan jika apel dalam kondisi selain kedua itu kita diamkan. 
