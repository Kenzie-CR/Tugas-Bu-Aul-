# Tugas-Bu-Aul-
Hasil Praktek

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gabungan Praktikum HTML - Kenzie Camilo Rahmandito</title>
</head>
<body>

    <section id="profil">
        <h1>Profil Diri</h1>
        <hr>

    

        <h2>Identitas</h2>
        <p><strong>Nama Lengkap :</strong> Kenzie Camilo Rahmandito</p>
        <p><strong>Kelas        :</strong> XI TKJ 4</p>
        <p><strong>Sekolah      :</strong> SMK Telkom Malang</p>
        <p><strong>Email        :</strong> kenziecamilo2308@gmail.com</p>

        <h2>Tentang Saya</h2>
        <p>
            Perkenalkan, nama saya <strong>Kenzie</strong>.
            Saya adalah siswa kelas XI jurusan TKJ.
            Saya <em>sangat antusias</em> dalam mempelajari Cabbling.
        </p>

        <h2>Hobi Saya</h2>
        <p>Ada beberapa hal yang saya sukai:</p>
        <p>1. <mark>Fisik</mark> - Saya suka olahraga</p>
        <p>2. Gaming - Main game strategi</p>
    
        
        

    <hr>

    <section id="praktik-list">
        <h2>List Berurutan</h2>
        <ol type="A">
            <li>Adi</li>
            <li>Badi</li>
            <li>Cadi</li>
            <li>Dadi</li>
        </ol>

        <h2>List Tidak Berurutan</h2>
        <ul type="square">
            <li>OSIS
                <ol type="1">
                    <p>Sie/Komisi</p>
                    <li>sie 1</li>
                    <li>sie 2</li>
                    <li>sie 3</li>
                    <li>sie 4</li>
                    <li>sie 5</li>
                </ol>
            </li>
            <li>MPK</li>
            <li>METIC</li>
            <li>MEMO</li>
        </ul>
    </section>

    <hr>

    <section id="data-kelas">
        <h1>Data Kelas X RPL</h1>
        
        <h2>Daftar Nilai Ulangan HTML</h2>
        <table border="1" cellpadding="8" cellspacing="0">
            <tr>
                <th>No</th>
                <th>Nama Siswa</th>
                <th>Pre-Test</th>
                <th>Post-Test</th>
                <th>Praktik</th>
                <th>Rata-rata</th>
            </tr>
            <tr>
                <td>1</td>
                <td>Kenzie</td>
                <td>80</td>
                <td>85</td>
                <td>90</td>
                <td>85</td>
            </tr>
            <tr>
                <td>2</td>
                <td>Athaya</td>
                <td>75</td>
                <td>80</td>
                <td>88</td>
                <td>81</td>
            </tr>
        </table>

        <h2>Materi yang Sudah Dipelajari</h2>
        <ol>
            <li>Pengenalan HTML dan Struktur Dasar
                <ul>
                    <li>DOCTYPE, html, head, body</li>
                    <li>Tag meta dan title</li>
                </ul>
            </li>
            <li>Tag Teks dan Multimedia
                <ul>
                    <li>Heading h1-h6</li>
                    <li>Paragraf dan format teks</li>
                    <li>Link dan Gambar</li>
                </ul>
            </li>
            <li>Tabel dan List (pertemuan ini)</li>
        </ol>

        <h2>Galeri Web Development</h2>
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/61/HTML5_logo_and_wordmark.svg"
             alt="Logo HTML5" width="100">
        <img src="https://upload.wikimedia.org/wikipedia/commons/d/d5/CSS3_logo_and_wordmark.svg"
             alt="Logo CSS3" width="100">
    </section>

    <hr>

    <section id="praktik-tabel">
        <h2>Praktik Tabel Sederhana & Span</h2>
        <table border="1">
            <tr>
                <th>No</th>
                <th>Nama</th>
                <th>Kelas</th>
            </tr>
            <tr>
                <td>1</td>
                <td>Ahamd</td>
                <td>90</td>
            </tr>
            <tr>
                <td>2</td>
                <td>Budi</td>
                <td>85</td>
            </tr>
        </table>

        <br>

        <table border="1">
            <tr>
                <th rowspan="2">No</th>
                <th rowspan="2">Nama</th>
                <th colspan="3">Nilai Mapel</th>
            </tr>
            <tr>
                <td>Mat</td>
                <td>Bindo</td>
                <td>Produktif</td>
            </tr>
        </table>
    </section>

    <hr>

    <section id="praktik-form">
        <h2>Form Input Data</h2>
        <form>
            <table>
                <tr>
                    <td><label>Nama Siswa</label></td>
                    <td>:</td>
                    <td><input type="text" required placeholder="Masukkan Nama"></td>
                </tr>
                <tr>
                    <td><label>No HP</label></td>
                    <td>:</td>
                    <td><input type="number"></td>
                </tr>
                <tr>
                    <td><label>Email</label></td>
                    <td>:</td>
                    <td><input type="email"></td>
                </tr>
                <tr>
                    <td><label>Password</label></td>
                    <td>:</td>
                    <td><input type="password"></td>
                </tr>
                <tr>
                    <td><label>Alamat</label></td>
                    <td>:</td>
                    <td><textarea></textarea></td>
                </tr>
                <tr>
                    <td><label>Jenis Kelamin</label></td>
                    <td>:</td>
                    <td>
                        <input type="radio" name="JenisKelamin" value="Laki-laki"> Laki-laki
                        <input type="radio" name="JenisKelamin" value="Perempuan"> Perempuan
                    </td>
                </tr>
                <tr>
                    <td><label>Makanan Favorit</label></td>
                    <td>:</td>
                    <td>
                        <input type="checkbox" name="makanan" value="Bakso"> Bakso  
                        <input type="checkbox" name="makanan" value="Mie Ayam"> Mie Ayam Bakso  
                        <input type="checkbox" name="makanan" value="Nasi Goreng"> Tahu Telor   
                        <input type="checkbox" name="makanan" value="Sate"> Sate   
                        <input type="checkbox" name="makanan" value="Pizza"> Pizza  
                    </td>
                </tr>
                <tr>
                    <td><label>Tanggal Lahir</label></td>
                    <td>:</td>
                    <td><input type="date"></td>
                </tr>
                <tr>
                    <td><label>Jurusan</label></td>
                    <td>:</td>
                    <td>
                        <select name="jurusan">
                            <option value="RPL">Rekayasa Perangkat Lunak</option>
                            <option value="TKJ">Teknik Komputer dan Jaringan</option>
                            <option value="PG">Pengembangan Game</option>
                        </select>
                    </td>
                </tr>
                <tr>
                    <td><label>Upload file foto</label></td>
                    <td>:</td>
                    <td><input type="file"></td>
                </tr>
                <tr>
                    <td></td>
                    <td></td>
                    <td>
                        <button type="submit">Submit</button>
                    </td>
                </tr>
            </table>
        </form>
    </section>

    <hr>
    <footer>
        <small>Dibuat sama.. aku &copy; 2026</small>
    </footer>

</body>
</html>
