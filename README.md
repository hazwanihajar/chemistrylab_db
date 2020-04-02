<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body {
      font-family: Arial, Helvetica, sans-serif;
      background-color: #bbbbbb;
      background-image:url(nh2.jpg);
      background-size: 1370px 620px;
	  background-repeat: no-repeat;
	}


h2{text-align: center;
    padding-bottom: 0px;
    padding-top: 0px;
    border-bottom-width: 90px;
    border-top-width: 20px;
    font-size: 29;   
	margin-bottom: 40px;
    margin-left: 330px;
    margin-right: 10px;
    margin-top: 40px;



}

img {
    float: right;
    margin-bottom: 0px;
    margin-top: 0px;
    padding-top: 0px;
    padding-left: 235px;
    height: 165px;
    width: 165px;
	padding-right: 0px;
    padding-bottom: 0px;

}


.navbar {
  overflow: hidden;
  background-color: #333;
}

.navbar a {
  float: left;
  font-size: 16px;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

.dropdown {
  float: left;
  overflow: hidden;
}

.dropdown .dropbtn {
  font-size: 16px;  
  border: none;
  outline: none;
  color: white;
  padding: 14px 16px;
  background-color: inherit;
  font-family: inherit;
  margin: 0;
}

.navbar a:hover, .dropdown:hover .dropbtn {
  background-color: #269293;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

.dropdown-content a {
  float: none;
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.dropdown-content a:hover {
  background-color: #33ffad;
}

.dropdown:hover .dropdown-content {
  display: block;
}
</style>
</head>
<body>


<table>
	 <th></th>	   
       <tr><td><h2>SISTEM PENGURUSAN  MAKMAL KIMIA <br> SMK BUKIT JANA     </h2><td>
     <td> <h3> <img src="SMKBJ.png" width="165" height="165" style="float:right"></h3></td></tr>
</table>


<div class="navbar">
  <a href="fpengurusanBhn.php">Pengurusan Bahan</a>
  
     <div class="text">
	<a href="SenaraiBahan.php">Laporan Penuh </a>
  </div>

  <div class="dropdown">
    <button class="dropbtn">Senarai  
      <i class="fa fa-caret-down"></i>
	  
    </button>
    <div class="dropdown-content">
      <a href="SenaraiBahanPengguna.php">Bahan</a>
      <a href="SenaraiPembekalPengguna.php">Pembekal</a>
      <a href="SenaraiLokasiPengguna.php">Lokasi</a>
	 
    </div>
  </div> 

    <div class="dropdown">
    <button class="dropbtn">Import
      <i class="fa fa-caret-down"></i>
	  
    </button>
    <div class="dropdown-content">
      <a href="upload.php">Bahan</a>
      <a href="uploadPembekal.php">Pembekal</a>
      <a href="uploadLokasi.php">Lokasi</a>
	 
    </div>
  </div> 
  
  
   <div class="text">
	<a href="carian.php">Carian 
	<i class="fa fa-search"></i></a>
  </div>
  

 <div> <i style="float:right"  style="font-family: Helvetica"><a href="index.php">LOG KELUAR <span class="glyphicon glyphicon-log-out"></span></a></i></div>
</div>


</body>
</html>
