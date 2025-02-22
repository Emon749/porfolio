@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800;900&display=swap');
*{
margin: 0;
padding: 0;
box-sizing: border-box;
font-family: 'poppins',sans-serif;
.logo {
    font-weight: bold;
    font-size: 24px; /* Optional: Increase size */
}

}
body{
    background-color: #474e9f;
}
a{
    color: #ffffff;
    text-decoration: none;
}
.navbar{
    position: fixed;
    left: 0;
    top: 0;
    width: 100%;
    padding: 25px 9%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    z-index: 100;
}
.navbar.logo {
   font-size: 30px;
   font-weight: 700;
}
.navbar ul{
    display: flex;
}
.navbar ul li{
    list-style: none;
    margin-left: 35px;
}
.navbar ul li a {
    font-size: 20px;
    font-weight: 500;
    transition: .5s;
    
}
.navbar ul li:hover a,
.navbar ul li.active a{
   color: hwb(105 3% 3%);
}
.home{
    display: flex;
    align-items: center;
    height: 100vh;
    padding: 60px 9% 0;
    color: #fafafa;
}
.home-info h1{
    font-size: 55px;
}
.home-info h2{
    font-size: 32px;
    margin-top: -10px;

}
.home-info p {
    font-size: 16px;
    margin: 10px 0 25px;
}
.home-info  .btn-sci{
    display: flex;
    align-items: center;
}
.btn{
    display: inline-block;
    padding: 10px 30px;
    background: orangered ;
    border: 2px solid orangered;
    border-radius: 40px;
    box-shadow: 0 0 10px orangered;
    font-size: 16px;
    color: black;
    font-weight: 600;
    transition: .5s;
}
.btn:hover{
    background: transparent;
    color: orangered;
    box-shadow: none;
}
.home-info .btn-sci .sci{
    margin-left: 20px;
}
.home-info .btn-sci.sci a{
    display: inline-flex;
    padding: 8px;
    border: 2px solid orangered;
    border-radius: 50%;
    font-size: 20px;
    color: orangered;
    margin: 0 8px;
    transition: .5s;
   
}
.home-info .btn-sci .sci a:hover{
    background: orangered;
    color: black;
    box-shadow: 0 0 10px orangered;
}
.sci {
    display: flex; 
    gap: 15px; 
    margin-top: 10px;
}

.sci a i {
    font-size: 24px; 
    color: hwb(0 100% 0%); 
}
.sci a i:hover{
    background: orangered;
    color: black;
    box-shadow: 0 0 10px orangered;
}
.profile-pic {
    width: 400px; 
    height: 400px;
    border-radius: 50%;
    overflow: hidden; 
    position: absolute; 
    right: 10%; 
    top: 50%; 
    transform: translateY(-50%);
    background-color: #6a5acd; 
    display: flex;
    justify-content: center;
    align-items: center;
}

.profile-pic img {
    width: 100%;
    height: 100%;
    object-fit: cover; 
}
.welcome-text {
    position: absolute;
    top: 15%; 
    left: 50%;
    transform: translateX(-50%);
    font-size: 40px;
    font-weight: bold;
    color: hsl(29, 100%, 50%); 
    text-align: center;
    font-family: 'Poppins', sans-serif;
}
