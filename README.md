<!DOCTYPE html>
<html>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Modul 2 Form Registrasi</title>
    <style>
        label {
            display: inline-block;
            width: 190px;            
            vertical-align: top;
        }
        fieldset.kemampuan-dasar label {
            display: inline;
            width: auto;
            margin-right: 20px; 
        }
        fieldset.kemampuan-dasar input {
            margin-right: 5px;
        }
        .label-container {
            display: flex;
            justify-content: flex-start;
            align-items: center;
            margin-bottom: 5px;
        }
        .label-container label {
            display: inline-block;
            width: 200px;
            text-align: left;
        }
        .label-container span {
            display: inline-block;
            width: 5px;
        }
    </style>
</head>

    </style>
</head>

<body>
    <h1>Form Registrasi</h1> 
    <div>
        
        <form action="" method="post">
            <!-- Biodata -->
            <fieldset>
                <legend>Biodata</legend>
                <div class="label-container">
                    <label for="nama">Nama Mahasiswa</label>
                    <span>:</span>
                    <input type="text" id="nama" name="nama" placeholder="Nama Anda">
                </div>
                <div class="label-container">
                    <label for="nim">No Induk Mahasiswa (NIM)</label>
                    <span>:</span>
                    <input type="text" id="nim" name="nim" placeholder="123456789">
                </div>
                <div class="label-container">
                    <label for="alamat">Alamat Mahasiswa</label>
                    <span>:</span>
                    <textarea id="alamat" name="alamat" rows="4" placeholder="Alamat Anda"></textarea>
                </div>
                <div class="label-container">
                    <label for="tanggal">Tanggal Lahir</label>
                    <span>:</span>
                    <select name="tanggal">
                        <option value=1 selected>01</option>
                        <option value=2>02</option>
                        <option value=3>03</option>
                        <option value=4>04</option>
                        <option value=5>05</option>
                        <option value=6>06</option>
                        <option value=7>07</option>
                        <option value=8>08</option>
                        <option value=9>09</option>
                        <option value=10>10</option>
                        <option value=11>11</option>
                        <option value=12>12</option>
                        <option value=13>13</option>
                        <option value=14>14</option>
                        <option value=15>15</option>
                        <option value=16>16</option>
                        <option value=17>17</option>
                        <option value=18>18</option>
                        <option value=19>19</option>
                        <option value=20>20</option>
                        <option value=21>21</option>
                        <option value=22>22</option>
                        <option value=23>23</option>
                        <option value=24>24</option>
                        <option value=25>25</option>
                        <option value=26>26</option>
                        <option value=27>27</option>
                        <option value=28>28</option>
                        <option value=29>29</option>
                        <option value=30>30</option>
                        <option value=31>31</option>
                    </select>
                    <select name="bulan">
                        <option value=1 selected>Januari</option>
                        <option value=2>Februari</option>
                        <option value=3>Maret</option>
                        <option value=4>April</option>
                        <option value=5>Mei</option>
                        <option value=6>Juni</option>
                        <option value=7>Juli</option>
                        <option value=8>Agustus</option>
                        <option value=9>September</option>
                        <option value=10>Oktober</option>
                        <option value=11>November</option>
                        <option value=12>Desember</option>
                    </select>
                    <select name="tahun">
                        <option value=1 selected>1990</option>
                        <option value=2>1991</option>
                        <option value=3>1992</option>
                        <option value=4>1993</option>
                        <option value=5>1994</option>
                        <option value=6>1995</option>
                        <option value=7>1996</option>
                        <option value=8>1997</option>
                        <option value=9>1998</option>
                        <option value=10>1999</option>
                        <option value=11>2000</option>
                        <option value=12>2001</option>
                        <option value=13>2002</option>
                        <option value=14>2003</option>
                        <option value=15>2004</option>
                        <option value=16>2005</option>
                        <option value=17>2006</option>
                        <option value=18>2007</option>
                        <option value=19>2008</option>
                        <option value=20>2009</option>
                        <option value=21>2010</option>
                        <option value=22>2011</option>
                        <option value=23>2012</option>
                        <option value=24>2013</option>
                        <option value=25>2014</option>
                        <option value=26>2015</option>
                        <option value=27>2016</option>
                        <option value=28>2017</option>
                        <option value=29>2018</option>
                        <option value=30>2019</option>
                        <option value=31>2020</option>
                        <option value=32>2021</option>
                        <option value=33>2022</option>
                        <option value=34>2023</option>
                        <option value=35>2024</option>
                    </select>
                </div>     
                <div class="label-container">     
                    <label for="jenis kelamin">Jenis Kelamin</label>
                    <span>:</span>
                    <input type="radio" name="gender" value="pria" id="pria" checked>
                    <label for="pria">Pria</label>
                    <input type="radio" name="gender" value="wanita" id="wanita">
                    <label for="wanita">Wanita</label>                 
                </div>
                <div class="label-container">
                    <label for="upload foto">Upload Foto</label>
                    <span>:</span>
                    <input type="file" name="file">
                </div>
                <div class="label-container">
                    <label for="url website">URL Website</label>
                    <span>:</span>
                    <input type="text" id="url website" name="url website" placeholder="URL Website Anda">
                </div>
                <div class="label-container">
                    <label for="perguruan tinggi">Perguruan Tinggi</label>
                    <span>:</span>
                    <input type="text" id="perguruan tinggi" name="perguruan tinggi">
                </div>
            </fieldset>
        </form>
        <form action="" method="post">
            <fieldset>
                <legend>Info Akun</legend>
                <div class="label-container">
                    <label for="email">Email</label>
                    <span>:</span>
                    <input type="email" name="email_form" size="20" placeholder="Email Anda">
                </div>
                <div class="label-container">
                    <label for="username">Username</label>
                    <span>:</span>
                    <input type="username" name="username_form" size="20" placeholder="Username Anda">
                </div>
                <div class="label-container">
                    <label for="password">Password</label>
                    <span>:</span>
                    <input type="password" name="password_form" size="20" placeholder="Password Anda">
                </div>
                <div class="label-container">
                    <label for="ulangi password">Ulangi Password:</label>
                    <span>:</span>
                    <input type="ulangi password" name="ulangi password_form" size="20" placeholder="Password Anda">
                </div>
            </fieldset>
        </form>
        <form action="" method="post">
            <fieldset class="kemampuan-dasar">
                <legend>Kemampuan Dasar</legend>
                <p>
                    <input type="checkbox" name="checkbox1" value="checkbox1" id="checkbox1"><label for="checkbox1">HTML</label>
                    <input type="checkbox" name="checkbox2" value="checkbox2" id="checkbox2"><label for="checkbox2">CSS</label>
                    <input type="checkbox" name="checkbox3" value="checkbox3" id="checkbox3"><label for="checkbox3">JavaScript</label>
                    <input type="checkbox" name="checkbox4" value="checkbox4" id="checkbox4"><label for="checkbox4">PHP</label>
                    <input type="checkbox" name="checkbox5" value="checkbox5" id="checkbox5"><label for="checkbox5">MySQL</label>
                    <input type="checkbox" name="checkbox6" value="checkbox6" id="checkbox6"><label for="checkbox6">Laravel</label>
                    <input type="checkbox" name="checkbox7" value="checkbox7" id="checkbox7"><label for="checkbox7">React Native</label>
                </p>
            </fieldset>
        </form>
        <p>
            <input type="reset" value="Reset">
            <input type="submit" value="Simpan">
            <input type="button" value="Button" onclick="">
        </p>
    </div>
</body>
</html>
