# PerancanganWeb
<!DOCTYPE html>
<html>
<head>

	<title>Layout</title>
	<style type="text/css">
		input {
			border-radius: 25px;
			height: 20px;
		}
		td {
			border-radius: 25px;
		}
	</style>
</head>
<body bgcolor="white">
	<table width="1000px" align="center" cellpadding="0" cellspacing="20" border="0">
		<tr>
			<td align="center" bgcolor="#5a9af2" colspan="3"><font size="20" color="white"><p>Universitas Tanjungpura</p></font></td>
		</tr>
		<tr>
			<td align="center" bgcolor="#5a9af2" colspan="2" width="75%" height="10px">	
				<table border="0" cellspacing="0" width="100%">
					<tr>
						<td align="center" height="100" width="33%"><a href="file:///D:/HTML/Perancangan%20Web/Contoh%20Peweb/Tugas%20Layout.html"><font size="5" color="white"><p>HOME</p></font></td></a>
						<td align="center" height="100" width="33%"><a href="#form"><font size="5" color="white"><p>FORM</p></font></td></a>
						<td align="center" height="100" width="33%"><a href="#FOOTER"><font size="5" color="white"><p>FOOTER</p></font></td></a>
					</tr>
				</table>
			</td>

			<td align="center" bgcolor="5a9af2" width="50" height="10px">
				<label for="search">Search</label>
				<input type="search" type="text/css" placeholder="type anything" class="input1" name="">
			</td>
		</tr>
		<tr>
			<td align="center" height="500" width="30%" bgcolor="#5a9af2"><font size="5" color="white"><p>SIDEBAR</p></font></td>
			<td align="center"  bgcolor="#5a9af2" width="0" colspan="2" >
				<table border="0" cellspacing="20" bgcolor="#f2f2f2" style="border-radius: 25px" >
					<tr id="form">
						<h1>ISI FORMULIR DI BAWAH INI</h1>
					</tr>
					<tr>
						<td>
							<form id="form1" name="form1"  method="POST" action="proses.html">
							  	<label for="nama"><b>Nama Depan</b></label><br>
							  	<input type="text" name="nama1" id="nama1" size="60%"><br></br>
							  	<label for="nama"><b>Nama Belakang</b></label><br>
								<input type="text" name="nama" id="nama" size="60%"><br></br>
								<label for="nama"><b>Alamat Sekarang</b></label><br>
								<input type="text" name="nama" id="nama" size="60%"><br></br>
								<label for="nama"><b>Kota Asal</b></label><br>
								<select id="kota" name="Kota" style="width: 430px; height: 30px; border-radius: 25px">
									<option value="Mempawah">Mempawah</option>
									<option value="Pontianak">Pontianak</option>
									<option value="Singkawang">Singkawang</option>
									<option value="None" selected="">None</option>
								</select><br></br>
								<input type="submit" value="Input" size="60%" style="width: 60px; height: 40px" >
							</form><br>
							<button onclick="myFunction()">Tampilkan Data</button>
								<p id="demo"></p>
								<script>
								function myFunction() {
								    var x = document.getElementById("form1");
								    var text = "";
								    var i;
								    for (i = 0; i < x.length ;i++) {
								        text += x.elements[i].value + "<br>";
								    }
								    document.getElementById("demo").innerHTML = text;
								}
								</script>
						</td>						
					</tr>
				</table>
			</td>
		</tr>
		<tr id="FOOTER">
			<td align="center" bgcolor="#5a9af2" colspan="3"><font size="5" color="white"><p>Create By Adhetya Putra Perdana</p></font></td>
		</tr>
	</table>

</body>
</html>
