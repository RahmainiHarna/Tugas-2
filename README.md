<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tugas 2</title>

<style>
    .dftr-pilihan {background-color:rgb(200, 172, 137);
                   color:rgb(22, 22, 22);
                   text-align:center;  
                  }

    .Radio {background-color:rgb(203, 205, 210);
           color:rgb(22, 22, 22);
           }

    .Font {background-color: rgb(158, 112, 90);
          color:rgb(251, 246, 246);
          font-size: 20px;
          font-style: oblique;
          background-size:10%;
          }

    .Genre{background-color:rgb(200, 172, 137);
           color:rgb(22, 22, 22);
           text-align:center;
          }
</style>
</head>
<body>
<form action=".">
    <table>
        <tr>
            <td class="Genre" width="150"><label for="Uname">Nama(*)</label> 
            <td><input type="text" id="uname" name="Username"></td>
        </tr>

   
   <tr>
       <td class="Genre">Password(*)</td>
       <td><input type="passwoord"></td>
   </tr>
  


<tr>
    <td class="Genre"><label for="NIM">NIM(*)</label></td>
    <td><input type="NIM" placeholder="~~ Hanya Angka ~~" onkeypress="return hanyaAngka(event);" value="" ></td>
    <script type="text/javascript">
            function hanyaAngka(evt){
            var charcode = (evt.which) ? evt.which : event.keycode
            if (charcode > 31 && (charcode < 48 || charcode > 57))
            return false;
            return true;
            }
    </script>
</tr>



<tr>
    <td class="dftr-pilihan">Hobi</td>            
    <td>
        <input type="Radio" name="radio">
        <span class="Radio"> Rebahan </span>
    </td>
</tr>  


<tr><td>
    <td>
        <input type="Radio" name="radio">
        <span class="Radio"> Membaca </span>
    </td>
</tr></td>
   
<tr><td>
    <td>
       <input type="Radio" name="radio">
       <span class="Radio"> Scroll TikTok </span>
    </td>
</tr></td>


<tr>
    <td class="Genre Musik">Genre Musik</td>
    <td class="Radio"><input type="Checkbox"> K-Pop</td>      
</tr>

        
<tr><td>
    <td class="Radio"><input type="Checkbox"> Pop </td>
</tr></td>
             
<tr><td>
     <td class="Radio"><input type="Checkbox"> R&B </td>
</tr></td>


 <tr>
    <td class="Genre">    Asal Sekolah </td>
    <td class="Radio"><select name="prodi" id="Prodi">
    <option value="#"> -- Pilih Salah Satu -- </option>
    <option class="Radio" value="ilkom">MAN 1 Medan </option>              
    <option value="ilkom">MAN 2 Medan </option>
    <option class="Radio" value="ilkom">MAN 3 Medan </option>
    <option value="ilkom">MAN IC Serpong </option>
    </select>
    </td> 
</tr>



<tr>
    <td class="Genre"><label for="Alasan Masuk TI">Alasan Masuk TI</label></td>
    <td>
        <textarea class="Radio" name="Alasan" id="Alasan"> Alasan Saya...
                </textarea>                
    </td>
</tr>



<tr>
   <td>
   <input type="submit" value="Daftar">    
   </td>    
   <td>
   <input type="reset" value="Reset">
    </td>
</tr>
  


       
      
                

   


       
          
          
  
