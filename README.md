# web-platform-btxiwg

# DOM - Manipulasi Elemen

Banyak fungsi salah satunya

- createElement()

-- append dappat menambahkan selain element HTML sedangkan appendChild yang ditambahkan wajib element
Ex.
//masukan headingSatu kedalam id app
app.append(headingSatu);
// tambahkan element h2
const headingDua = document.createElement('h2');
// sekarang berikan headingDua attribute class
headingDua.className = 'headingKedua';
// sekarang tambahkan text menggunakan appent bukan innerHTML
headingDua.append('Hallo ini adalah Heading 2 dengan suatu class');
//memastikan bahwa yang diappend wajib suatu element
app.appendChild(headingDua);

-- Event = sebuah Aksi yang terjadi dalam HTml
-- Cra medeklarikan event ada cara 1. Secara HTML dengan menggunakan on[namaevent] pada element html
Contoh : onclick="namaFungsi" 2. Secara JS - mengguakan element.addEventListener(namaEvent, namaFungsi)
-- contoh beberapa Event dalam javascript 1. onclick 2. keypress 3. hover 4. submit 5. blur 6. keyup

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/web-platform-btxiwg)
