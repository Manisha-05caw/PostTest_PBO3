# PostTest_PBO3

<img width="1547" height="1063" alt="Screenshot 2025-09-21 194643" src="https://github.com/user-attachments/assets/7efad68b-8cfd-465c-a6f7-34275e711b3d" />

public class Orang → mendefinisikan class bernama Orang.
- private String nama; dan private int umur; → atribut (field) yang menyimpan data pribadi:
- nama → tipe data String
- umur → tipe data int
- private berarti atribut hanya bisa diakses di dalam class itu sendiri (enkapsulasi).

Konstruktor digunakan untuk membuat objek Orang dengan langsung memberikan nilai nama dan umur.

this.nama = nama; → membedakan antara parameter dan atribut class.

this.umur = umur; → mengisi atribut umur dengan nilai yang diberikan

- Getter → mengambil nilai atribut (misalnya getNama()).
- Setter → mengubah/mengisi nilai atribut (misalnya setNama(String nama)).
Dengan cara ini, akses data tetap aman (enkapsulasi), karena field tidak langsung diakses dari luar.

Method ini menimpa (override) method bawaan toString() dari class Object. Tujuannya agar ketika objek dicetak (System.out.println(objek);), hasilnya berupa teks yang mudah dibaca.


<img width="2023" height="1250" alt="image" src="https://github.com/user-attachments/assets/9be6495f-72e7-4783-ab5b-2a6bedab223f" />

private String nama; : Atribut untuk menyimpan nama hewan. Tipe data yang digunakan adalah String.

private String jenis; : Atribut untuk menyimpan jenis hewan. Tipe data yang digunakan adalah String.

private int umur; : Atribut untuk menyimpan umur hewan. Tipe data yang digunakan adalah int.

Constructor:

public Hewan(String nama, String jenis, int umur) : Constructor ini digunakan untuk menginisialisasi objek Hewan dengan nilai untuk nama, jenis, dan umur. Nilai yang diberikan dalam parameter constructor akan disalin ke dalam atribut kelas menggunakan this.

<img width="1530" height="237" alt="image" src="https://github.com/user-attachments/assets/a1023f7c-d340-43db-a9ea-d88b4e655655" />


super(nama, umur); :
super digunakan untuk memanggil konstruktor dari kelas induk (superclass). Kelas Pemilik kemungkinan besar merupakan subclass dari kelas yang memiliki konstruktor yang menerima dua parameter (String nama, int umur). Dengan menggunakan super, konstruktor Pemilik akan menginisialisasi atribut nama dan umur dengan nilai yang diberikan pada konstruktor kelas induk.
