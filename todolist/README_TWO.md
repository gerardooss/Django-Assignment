## Perbedaan antara asynchronous programming dengan synchronous programming.
Asynchronous programming adalah sebuah teknik pemrograman untuk membuat sebuah program melakukan sebuah proses secara independen. Asynchronous programming ini menciptakan sebuah long-running task yang responsive sehingga memungkinkan sebuah proses dijalankan dan proses lain tetap berjalan di background.
Berbeda dengan asynchronous programming, synchronous programming merupakan model programming yang akan menghasilkan eksekusi proses yang sequential. Setiap proses dijalankan sesuai dengan urutannya, berbeda dengan asynchronous programming yang merupakan 'multitasker'. Oleh karena itu, synchronous programming membutuhkan waktu eksekusi yang lebih lama.

## Penerapan paradigma Event-Driven Programming, maksud, dan contohnya.
Event-Driven Programming merupakan sebuah kondisi dimana program akan berjalan sesuai dengan event berupa tindakan dari pengguna. Sebagai contoh ketika 'add task' dipilih, pengguna akan diarahkan ke halaman pembuatan task.

## Penerapan asynchronous programming pada AJAX.
Dengan AJAX, input masukan dari pengguna dapat langsung ditampilkan tanpa perlu reloading page.

## Cara mengimplementasikan checklist di atas.
### AJAX GET
1. Menambahkan function `show_json` pada todolist/views.py untuk me-return data task dalam bentuk json.
2. Menambahkan `path('json/', show_json, name='show_json'),` pada todolist/urls.py.
3. Menambahkan file `todolist_ajax.html` pada todolist/templates.
4. Menambahkan function `show_ajax` pada todolist/views.py yang merender `todolist_ajax.html`
5. Menambahkan skema fungsi `ajax_get` pada `todolist_ajax.html`
### AJAX POST
1. Lorem ipsum dolor sit amet,
2. consectetur adipiscing elit--