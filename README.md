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
