<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body {
  margin: 0;
  font-family: "Times New Roman", Times, serif;
  background-color: #AFA4A4;
}

.topnav {
  overflow: hidden;
  background-color: #EECECE;
}

.topnav a {
  float: left;
  display: block;
  color: #06365F;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: white;
  color: #579EDC;
}

.topnav a.active {
  background-color: purple;
  color: white;
}

.topnav .icon {
  display: none;
}

@media screen and (max-width: 600px) {
  .topnav a:not(:first-child) {display: none;}
  .topnav a.icon {
    float: right;
    display: block;
  }
}

@media screen and (max-width: 600px) {
  .topnav.responsive {position: relative;}
  .topnav.responsive .icon {
    position: absolute;
    right: 0;
    top: 0;
  }
  .topnav.responsive a {
    float: none;
    display: block;
    text-align: left;
  }
}

div.elem-group {
  margin: 15px 5;
}

div.elem-group.inlined {
  width: 20%;
  display: inline-block;
  float: left;
  margin-left: 5%;
}

div.places-block {
  width: 70%;
  display:inline-block;
  float: left;
  margin-left: 5%;
  padding-bottom: 15px;
}

label {
  display: block;
  font-family: 'Nanum Gothic';
  padding-bottom: 10px;
  font-size: 1.15em;
}
div.elem-group.inlined input {
  width: 85%;
  display: inline-block;
}

div.places-block input {
  width: 70%;
  display: inline-block;
}

.coupon {
  border: 7px dotted #bbb;
  width: 150%;
  border-radius: 15px;
  margin: 0 auto;
  max-width: 200px;
  background-color: red;
  border-color: yellow;
  float: right;
  margin-right: 1%;
}
.transbox1 {
  margin: 15px;
  background-color: #AFA4A4;
  border-radius: 5px;
  opacity: 0.9;
}

.transbox1 p {
  margin: 15px;
  color: black;
 }


.container1 {
  padding: 2px 7px;
  background-color: red;
}

.container {
 width: 300%;
  border-radius: 10px;
  margin: 60px;
  max-width: 250px;
  background-size: 100%;
  float: left;
   margin-left: 5%;
   margin-right: 5%;
  color: white; 
  text-align:center;
  padding: 5px 5px;
  display: inline-block;
}

.transbox {
  margin: 15px;
  background-color: #AFA4A4;
  border-radius: 10px;
  opacity: 0.9;
}

.transbox p {
  margin: 0 auto;
  color: black;
 }

</style>
</head>
<body>

<div class="topnav" id="myTopnav">
  <a href="#home" class="active">Home</a>
  <a href="#news">News</a>
  <a href="#contact">Contact</a>
  <a href="#about">About</a>
  <a href="javascript:void(0);" class="icon" onclick="myFunction()">
    <i class="fa fa-bars"></i>
  </a>
</div>
<div style="padding-left:16px; color:white;background-image:url('https://velvetescape.com/wp-content/uploads/2018/09/IMG_3823-1280x920.jpg');background-size: 90% 100%;">
  <h1>DISCOVER MALAYSIA</h1>
  
  <div class="transbox1">
  <p style= "text-align: center;">Malaysia is a Southeast Asian country occupying parts of the Malay Peninsula and the island of Borneo. It's known for its beaches, rainforests and mix of Malay, Chinese, Indian and European cultural influences. The capital, Kuala Lumpur, is home to colonial buildings, busy shopping districts.</p>
</div>
</div>

<div class="form-header header-primary">
      <h4 style= "text-align: center; color:#06365F"><i class='fas fa-map-marker-alt'></i> TRIP AROUND MALAYSIA</h4>
    </div>
    
    <div class="coupon">
  <div class="container1">
    <h3 style="color: white; text-align:center">Special Deals 41% only</h3>
  </div>
  <img src="http://cf02.sdimgs.com/map/wrd/7/2_4/wrd_7_2_4_1045_1712.gif?v=1.0.1.45" alt="Avatar" style="width:90%; float:right;  margin-right: 4%" >
  <div class="container1" style="background-color:red; text-align: center"> 
    <p><br>At Melaka from RM 258.00</p>
  </div>
</div>
    
    <form method="post" action="/" id="booking-form">
   <div class="places-block">
    <label for="destination">Destinations</label>
    <input type="text" id="places" name="place" required>
  </div>
  <br>
   <div class="elem-group inlined">
    <label for="checkin-date">Check-in Date</label>
    <input type="date" id="checkin-date" name="checkin" required>
  </div>
  <div class="elem-group inlined">
    <label for="checkout-date">Check-out Date</label>
    <input type="date" id="checkout-date" name="checkout" required>
  </div>
  <br><br><br><br><br><br><br><br><br><br><br><br><br><br>
    </form>
    
      <h4 style= "text-align: center; color:#06365F"><i class='fas fa-map-marker-alt'></i> TRIP AROUND MALAYSIA</h4>
    
    <div class="container" style=" background-image: url('http://static.asiawebdirect.com/m/kl/portals/kuala-lumpur-ws/homepage/klareas/pagePropertiesImage/kl-areas.jpg.jpg');">
    <h3 >KUALA LUMPUR</h3>
  <div class="transbox">
    <p><br>Kuala Lumpur comes spiked at the center by the two great spires of the Petronas Towers, packed with markets and heady hawker bazaars down Petaling Street, throbbing with the energy of Bukit Bintang - the entertainment city.</p>
     </div>
</div>

<div class="container" style=" background-image: url('https://images.squarespace-cdn.com/content/v1/5a87961cbe42d637c54cab93/1571338347141-BVVAI15K1GFZS2XP69H8/melaka-malaysia-travel-guide.jpg?format=1000w');">
    <h3 >MALACCA</h3>
  <div class="transbox">
    <p><br>Firmly rooted as Malaysia's historicalcity, visiting Malacca is like a journey back in time to witness the adventures and discoveries during Malacca's golden age. Today, there are many historical sites to visit that give you a glimpse of Malacca's glorious past.</p>
  </div>
</div>

<div class="container" style=" background-image: url('https://www.caridestinasi.com/wp-content/uploads/2016/04/senarai-tempat-menarik-cameron-highlands.jpg');">
    <h3 >PAHANG</h3>
  <div class="transbox">
    <p><br>Pahang is the largest state in Peninsular Malaysia with an area of nearly 36,000sq. km. It is thinly populated and vast tracts are given over to primeval rain forests, pristine national parks, huge freshwater lakes, formidable mountains and refreshingly cool hill stations.</p>
  </div>
</div>

<div class="container" style=" background-image: url('http://static.asiawebdirect.com/m/kl/portals/penang-ws/shared/teasersL/TOURS/tour-city/teaserMultiLarge/imageHilight/teaser.jpeg.jpg');">
    <h3 >PENANG</h3>
  <div class="transbox">
    <p><br>Located in the northern part of Peninsular Malaysia. This part of Malaysia is also known for its food, and anyone who loves to eat will truly find a culinary paradise here, much of which is down to the mix of influences in the city.</p>
  </div>
</div>

<div class="container" style=" background-image: url('https://assets.nst.com.my/images/articles/HARI_SARAWAK_2021_1633440931.jpg');">
    <h3 >SARAWAK</h3>
  <div class="transbox">
    <p><br>The largest among 13 states, with an area almost equal to Peninsular Malaysia. It has several prominent cave systems at Gunung Mulu National Park. Rajang River is the longest river in Malaysia; Bakun Dam, one of the largest dams in Southeast Asia.</p>
  </div>
</div>

<div class="container" style=" background-image: url('https://itc.gov.my/wp-content/uploads/2021/04/Masjid-Kristal-Kuala-Terengganu.jpg');">
    <h3 >TERENGGANU</h3>
  <div class="transbox">
    <p><br>Sitting on the east coast of Peninsular Malaysia, Terengganu is home to lovely mosques, seafood, breathtaking oceans and more.</p>
  </div>
</div>
 

<script type="text/javascript">
function myFunction() {
  var x = document.getElementById("myTopnav");
  if (x.className === "topnav") {
    x.className += " responsive";
  } else {
    x.className = "topnav";
  }
}

var currentDateTime = new Date();
var year = currentDateTime.getFullYear();
var month = (currentDateTime.getMonth() + 1);
var date = (currentDateTime.getDate() + 1);

if(date < 10) {
  date = '0' + date;
}
if(month < 10) {
  month = '0' + month;
}

var dateTomorrow = year + "-" + month + "-" + date;
var checkinElem = document.querySelector("#checkin-date");
var checkoutElem = document.querySelector("#checkout-date");

checkinElem.setAttribute("min", dateTomorrow);

checkinElem.onchange = function () {
    checkoutElem.setAttribute("min", this.value);
}
</script>

</body>
</html>


