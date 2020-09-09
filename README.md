# AlanCreativeInternship
# No. 1
Membuat sebuah method/function untuk me-return biodata asli Anda, dengan
ketentuan sebagai berikut:
• name (String)
• age (Number)
• address (String)
• hobbies (Array)
• is_married (Boolean)
• list_school (Array of Object) with key name, year_in, year_out, and major (if
any, if no set “null” )
• skills (Array of Obj) with key skill_name and level (beginner, advanced,
expert)
• interest_in_coding (Boolean)
Return value harus berformat JSON dan sesuai ketentuan di atas.
Pada readme sebutkan kegunaan JSON pada REST API.

# NO. 2
Pada sebuah form, terdapat 2 buah field yaitu: username dan password. Buatlah
method/function untuk memvalidasi field-field tersebut, dengan requirement sebagai
berikut:
● Disarankan menggunakan REGEX
● Format username: merupakan kombinasi dari huruf kecil, huruf besar dan angka
dengan panjang 5-9 karakter. Username tidak boleh diawali dengan angka /
karakter special.
● Format password: merupakan kombinasi dari huruf kecil, huruf besar minimal
satu karakter, angka minimal satu karakter, dan karakter spesial minimal satu
karakter dan harus memiliki karakter simbol ‘@’ dan panjang minimal 8 karakter.
Clue:
Peserta hanya diminta membuat function validasi, tidak perlu membuat form HTML.
Examples:
- is_username_valid(‘@sony’)
return false
- is_username_valid(‘Ayu99v’)
return true
- is_password_valid(‘p@ssW0rd#’)
return true
- is_password_valid(‘C0d3YourFuture!#’)
return false

# No. 3
Buatlah program yang dapat menemukan berapa banyak sebuah kata/frasa dari
sebuah string baik itu dari kiri atau kanan.
REQUIREMENT:
1. Input dari user sebanyak 2 parameter berupa string dan kata/frasa yang ingin
dicari.
2. Input kata/frasa pencarian tidak bisa lebih panjang dibandingkan string.
3. Output berupa banyaknya kata/frasa pencarian yang ditemukan dari string
yang telah diberikan.
INPUT:
$ banananana
$ nana
OUTPUT:
$ ditemukan 6 kali

# No. 4
Pada soal no 4, menggunakan bahasa html. Dengan Output :
<pre>
<strong>$</strong> html Num4.html
* = = = * 
* = = = * 
* * * * * 
* = = = * 
* = = = * 
</pre>

# No. 5
Buatlah function yang mempunyai sebuah parameter, fungsi tersebut mempunyai
tugas untuk mencetak string acak sepanjang 32 karakter sebanyak jumlah parameter.
Pada function tersebut buatlah pengecekan untuk memastikan tidak ada
string(data) yang sama.
Clue:
Function dijalankan:
cetak(3);
Akan dicetak di layar
da2c312dfe804ef5bd318133a342251a
79n89a9mdfe804ef5b18133a342251o
6e576057da174c4189f7ea8341946aed

# 6A
Dibuat database menggunakan phpMyAdmin. sourcecode untuk querynya :

<pre>
SELECT name.name, work.work, category.salary FROM name, work, category WHERE name.id_work=work.id AND name.id_salary=category.id; 
</pre> soal
