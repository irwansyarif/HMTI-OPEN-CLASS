## JavaScript: Menambahkan Interaktivitas

Javascript adalah bahasa pemrograman untuk web
Sintaks dasar JavaScript: variabel, tipe data, operator
Manipulasi DOM: mengubah HTML dan CSS menggunakan JavaScript
Penanganan event: merespons interaksi pengguna

# Mengubah Isi Teks Elemen JavaScript
Mengambil elemen dengan id "demo"
```const element = document.getElementById("demo");```

# Mengubah isi teks elemen
```element.textContent = "Teks baru telah diubah!";```

# Mengubah Style Elemen JavaScript
Mengambil semua elemen dengan tag <'p'>
```const paragraphs = document.getElementsByTagName("p");```

Mengubah warna latar belakang semua paragraf menjadi kuning
```for (let i = 0; i < paragraphs.length; i++) { paragraphs[i].style.backgroundColor = "yellow"; }```

# Menambahkan Elemen Baru JavaScript
Membuat elemen baru (paragraf)
```const newParagraph = document.createElement("p");const textNode = document.createTextNode("Ini adalah paragraf baru."); newParagraph.appendChild(textNode);```

Menambahkan elemen baru ke dalam elemen dengan id "container"
```const container = document.getElementById("container");container.appendChild(newParagraph);```

# Menghapus Elemen JavaScript
Mengambil elemen dengan id "to-be-removed"
```const elementToRemove = document.getElementBy("to-be-removed");```
# Menghapus elemen dari DOM
```elementToRemove.parentNode.removeChild(elementToRemove);```

# Mendengarkan Event JavaScript
Mengambil tombol dengan id "myButton"
```const button = document.getElementById("myButton");```

Menambahkan event listener untuk klik
```button.addEventListener("click", function() { alert("Tombol telah diklik!");});```