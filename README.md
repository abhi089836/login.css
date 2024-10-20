*{
  padding:0;
  margin:0;
  box-sizing:border-box;
  text-decoration:none;
  font-family:Verdana,Georgia;
}
div-login-container{
  min-height:100vh;
  padding:0 7%;
  margin-top:50px;
  display:flex;
  align-items:center;
  justify-content:space-between;
  border-radius:20px;
}
div-loginPage-image{
  width:70%;
  border-radius:30px;
}
div-loginPage-image img{
  width:70%;
}
div-login{
  display:flex;
  align-items:center;
  flex-direction:column;
  box-shadow: 0 0 150px rgb(239,121,30,0.5);
  padding:40px;
  width:40%;
  border-radius:20px;
}
form{
  width:100%;
  
}
div-login h2{
  margin-bottom:20px;
  font-size:30px;
  color:rgb(239,121,30);
}
div-login-container label,div-login-container input{
  display:block;
}
div-login label{
  font-size:13px;
  font-weight:600;
  margin-top:15px;
  margin-bottom:5px;
}
div-login input{
  padding:10px;
  outline:none;
  width:100%;
  border:1px solid rgb(128,128,128,0.1);
  border-radius:5px;
  background-color:rgb(128,128,128,0.09);
}
div-login p-forgot{
  text-align:left;
  color:rgb(82,82,82);
  font-size:12px;
  margin-top:5px;
  cursor:pointer;
}
div-login a-btn{
  width:100%;
  padding:10px;
  border-radius:5px;
  margin-top:20px;
  display:block;
  text-align:center;
}
div-login a-btn:hover{
	transform:translationX(0);
}
div-login p-signup{
	color:rgb(82,82,82);
	font-size:13px;
	text-align:center;
	margin-top:20px;
}
div-login p-signup span{
	font-weight:100;
	color:black;
}
a-btn{
  background-color:rgb(239,122,30);
  border:none;
  color:white;
  border-radius:20px;
  font-size:15px;
  padding:10px 20px;
  cursor:pointer;
}
