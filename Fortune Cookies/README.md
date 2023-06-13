# Fortune Cookies
Would you like to have some fortune cookies?
http://103.167.136.89:10088/

## About the Challenge
Diberikan sebuah url website dimana kita harus mencari flag yang ada pada website tersebut dengan mengecek bagian cookies dari website tersebut

![preview](images/FortuneCookies.png)

## Solution
Tampilan website : 

![preview](images/WebInterface.png)

Tampilan ketika menekan tombol "Get your fortune!"
![preview](images/ClickButton.png)

Lalu saya melakukan inspect untuk melihat cookies dari web tersebut : 
![preview](images/Inspect.png)

Setelah dilakukan inspect pada cookies ditemukan cookies "flag" dengan nilai 0.

Saya mencoba mengganti nilai dari cookies dari 0 menjadi 1 
![preview](images/Inspect2.png)

Setelah mengubah nilai cookies saya merefresh halaman website dan flag berhasil ditemukan pada cookies "flag" dengan value 1
![preview](images/Flag.png)

```
Flag : ForestyHC{here_is_your_fortun3_cookie_4a0a47}
```
