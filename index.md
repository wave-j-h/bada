<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8" />
<link href="m.icon" rel="shortcut icon" type="image/x-icon">
<img src="name3.png" width="150" class="name" >
<title>파도</title>
<style>
			img { display: block; margin: 0px auto; }
      .헤더{font-size:30px; text-align:center;}
		</style>

    <script type="text/javascript">
        var imgArray= new Array();
        imgArray[0]="000.jpg";  //사진
        imgArray[1]="001.jpg"; 
        imgArray[2]="002.jpg";    
        imgArray[3]="003.jpg";   
        imgArray[4]="004.jpg";   
        imgArray[5]="005.jpg";    
        imgArray[6]="006.jpg";    
        imgArray[7]="007.jpg";   
        imgArray[8]="008.jpg";  
        imgArray[9]="009.jpg";  		
        imgArray[10]="010.jpg";  
        imgArray[11]="011.jpg";  
        imgArray[12]="012.jpg";  
        imgArray[13]="013.jpg";  
        imgArray[14]="014.jpg";  
        imgArray[15]="015.jpg";  
        imgArray[16]="016.jpg";  
        imgArray[17]="017.jpg";  
        imgArray[18]="018.jpg";  
        imgArray[19]="019.jpg";  
        imgArray[20]="020.jpg";  
        imgArray[21]="021.jpg";  
        imgArray[22]="022.jpg";  
        imgArray[23]="023.jpg";  
        imgArray[24]="024.jpg";  
        imgArray[25]="025.jpg";  
        imgArray[26]="026.jpg";  
        imgArray[27]="027.jpg";  
        imgArray[28]="028.jpg";  
        imgArray[29]="029.jpg";  
        imgArray[30]="030.jpg";  
        imgArray[31]="031.jpg";  
		imgArray[32]="032.jpg";  
        imgArray[33]="033.jpg";  
        imgArray[34]="034.jpg";  
        imgArray[35]="035.jpg";  
        imgArray[36]="036.jpg";  
        imgArray[37]="037.jpg";  
        imgArray[38]="038.jpg";  
        imgArray[39]="039.jpg";  
        imgArray[40]="040.jpg";  
        imgArray[41]="041.jpg";  
        imgArray[42]="042.jpg";  
        imgArray[43]="043.jpg";  
        imgArray[44]="044.jpg";  
        imgArray[45]="045.jpg";  
        imgArray[46]="046.jpg";  
        imgArray[47]="047.jpg";  
        imgArray[48]="048.jpg";  
        imgArray[49]="049.jpg";  
        imgArray[50]="050.jpg"; 
        imgArray[51]="051.jpg";  
		imgArray[52]="052.jpg";  
        imgArray[53]="053.jpg";  
        imgArray[54]="054.jpg";  
        imgArray[55]="055.jpg";  
        imgArray[56]="056.jpg";  
        imgArray[57]="057.jpg";  
        imgArray[58]="058.jpg";  
        imgArray[59]="059.jpg";  
        imgArray[60]="060.jpg";  		
        imgArray[61]="061.jpg";  
        imgArray[62]="062.jpg";  
        imgArray[63]="063.jpg";  
        imgArray[64]="064.jpg";  
        imgArray[65]="065.jpg";  
        imgArray[66]="066.jpg";  
        imgArray[67]="067.jpg";  
        imgArray[68]="068.jpg";  
        imgArray[69]="069.jpg";  
        imgArray[70]="070.jpg"; 
        imgArray[71]="071.jpg";  
		imgArray[72]="072.jpg";  
        imgArray[73]="073.jpg";  
        imgArray[74]="074.jpg";  
        imgArray[75]="075.jpg";  
        imgArray[76]="076.jpg";  
        imgArray[77]="077.jpg";  
        imgArray[78]="078.jpg";  
        imgArray[79]="079.jpg";  
        imgArray[80]="080.jpg";  		
        imgArray[81]="081.jpg";  
		imgArray[82]="-01.jpg"; 
        imgArray[83]="-02.jpg";    
        imgArray[84]="-03.jpg";   
        imgArray[85]="-04.jpg";   
        imgArray[86]="-05.jpg";    
		
        function showImage()
        {
            var imgNum=Math.round(Math.random()*86);
            var objImg=document.getElementById("introImg");
            objImg.src=imgArray[imgNum];
        }
    </script>
</head>
<body onload="showImage()">
    <img id="introImg" border="0"
   height="500"  >
</body>
</html>
