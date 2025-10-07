# Lab3Web
```
Nama   : Fathan Atallah Rasya Nugraha
NIM    : 312410425
Kelas  : TI.24.A3
```

## List
1. Ordered List
```html
    <section id="order-list">
        <h2>Ordered List</h2>
        <ol>
            <li>Pisang</li>
            <li>Apel</li>
            <li>Jeruk</li>
        </ol>
    </section>
```
2. Unordered List
```html
    <section id="unorder-list">
        <h2>Unordered List</h2>
        <ul type="square">
            <li>Buah Naga</li>
            <li>Kelapa</li>
            <li>Sirsak</li>
        </ul>
    </section>
```
3. Description List
```html
    <section id="desc-list">
        <h2>Description List</h2>
        <dl>
            <dt>Buah</dt>
            <dd>Lemon</dd>
            <dd>Mangga</dd>
            <dd>Jambu</dd>
            <dt>Sayur</dt>
            <dd>Sawi</dd>
            <dd>Kol</dd>
            <dd>Bayam</dd>
        </dl>
    </section>
```


## Tabel
```html
    <table border="1" cellpadding="4" cellspacing="0">
        <thead>
            <tr>
                <th>No.</th>
                <th>Fakultas</th>
                <th>Program Studi</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1.</td>
                <td rowspan="3" style="text-align: center;">Teknik</td>
                <td>Teknik Informatika</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>Teknik Industri</td>
            </tr>
            <tr>
                <td>3.</td> 
                <td>Teknik Lingkungan</td>
            </tr>
        </tbody>
    </table>
```


## Form
```html
    <form action="proses.php" method="post">
        <fieldset>
            <legend>Login</legend>
            <p>
                <label for="uname">Username</label>
                <input type="text" id="uname" name="Username">
            </p>
            <p>
                <label for="passwd">Password</label>
                <input type="password" id="passwd" name="Password">
            </p>
            <p>
                <label for="gndr">Gender</label>
                <select name="gender" id="gender">
                    <option value="Laki-Laki">Laki-Laki</option>
                    <option value="Perempuan">Perempuan</option>
                </select>
            </p>
            <p>
                <label for="matkul">Mata Kuliah</label>
                <input type="checkbox">RPL
                <input type="checkbox">Pemrograman Web
                <input type="checkbox">Pemrograman Mobile
                <input type="checkbox">Pendidikan Agama
                <input type="checkbox">OOP
            </p>
            <p><input type="submit" value="Login"></p>
        </fieldset>
    </form>
```
1. Dropdown
```html
            <p>
                <label for="gndr">Gender</label>
                <select name="gender" id="gender">
                    <option value="Laki-Laki">Laki-Laki</option>
                    <option value="Perempuan">Perempuan</option>
                </select>
            </p>
```
2. Listbox
```html
            <p>
                <label for="matkul">Mata Kuliah</label>
                <input type="checkbox">RPL
                <input type="checkbox">Pemrograman Web
                <input type="checkbox">Pemrograman Mobile
                <input type="checkbox">Pendidikan Agama
                <input type="checkbox">OOP
            </p>
```
