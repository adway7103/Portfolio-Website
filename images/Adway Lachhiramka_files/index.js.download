function myFunction() {
  document.getElementById("myDropdown").classList.toggle("show");
}
function myFunction1() {
  document.getElementById("myDropdown1").classList.toggle("show");
}

// Close the dropdown if the user clicks outside of it
window.onclick = function (event) {
  if (!event.target.matches('.dropbtn')) {
    var dropdowns = document.getElementsByClassName("dropdown-content");
    var i;
    for (i = 0; i < dropdowns.length; i++) {
      var openDropdown = dropdowns[i];
      if (openDropdown.classList.contains('show')) {
        openDropdown.classList.remove('show');
      }
    }
  }
}
window.onclick = function (event) {
  if (!event.target.matches('.dropbtn1')) {
    var dropdowns = document.getElementsByClassName("dropdown-content1");
    var i;
    for (i = 0; i < dropdowns.length; i++) {
      var openDropdown = dropdowns[i];
      if (openDropdown.classList.contains('show')) {
        openDropdown.classList.remove('show');
      }
    }
  }
}
function myFunction2(){
  console.log("adw")
  var x = document.getElementById("mytopnav");
  if (x.className === "navbar") {
    x.className += " responsive";
  } else {
    x.className = "navbar";
  }
}
var btn=document.getElementById("btn")
var icon=document.getElementById("icon")
btn.onclick=function(){
  document.body.classList.toggle("dark-theme")
  if(document.body.classList.contains("dark-theme")){
    icon.src="images/sun.png"
    document.cookie="true"
  }
  else{
    icon.src="images/7148715_dark_mode_night_moon_icon.png"
    document.cookie="false"
  }
}
let x = document.cookie;
function message(e){
  // e.preventDefault();
  var name=document.getElementById("name")
  var email=document.getElementById("email")
  var success=document.getElementById("success")
  var message=document.getElementById("message")
  success.style.display='block';
  name.value=''
  email.value=''
  message.value=''
}
if(x==="true")
{
  document.body.classList.add("dark-theme")
  icon.src="images/sun.png"}
  else
  {
    document.body.classList.remove("dark-theme")
    icon.src="images/7148715_dark_mode_night_moon_icon.png"
  }
