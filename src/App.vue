<template>
<body>
  <header>
      <div id="nav"><h1>GamePoint</h1>    
        <router-link to="/">Home</router-link> 
        <router-link to="/reviews">Reviews</router-link> 
        <router-link to="/about">About</router-link> 
        <router-link to="/contact">Contact</router-link> 
        <router-link to="/login">Login</router-link> 
      </div>
  </header>
      <router-view/>
 </body>
</template>

<style>
/*general format for text*/
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: dosis;
  text-align: center;
}
/*Colour and shadow for the navbar*/
header {
  background-color: rgb(46, 195, 221);
  box-shadow: 0px 3px 6px rgba(0, 0, 0, 0.1);
}
/*Some spacing for the navbar*/
#nav {
  padding: 10px 100px;
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  margin-left: 10%;
  margin-right: 10%;
}
/*background colour behind white-box*/
body {
  background-color: #EEE;
}
/*Create a box for content, add some shadow for a floaty feeling*/
main {
  margin-top: 2%;
  margin-bottom: 2%;
  padding: 5% 3%;
  border-radius: 20px;
  background-color: #FFF;
  box-shadow: 0px 3px 6px rgba(0, 0, 0, 0.1);
  margin-left: 10%;
  margin-right: 10%;
}
/*Styling for the links/tabs*/
#nav a {
  display: block;
  padding: 15px 30px;
  text-decoration: none;
  color: #FFF;
  cursor: pointer;
}
/*Simple hover effect for tabs*/
#nav a:hover {
  background-color: #7712c9;
  border-radius: 8px;
}
/*Current active tab is highlighted*/
#nav a.router-link-exact-active {
  background-color: #7712c9;
  border-radius: 1px;
  font-weight: 700;
  border-radius: 8px;
}
.footer {
  position: relative;
  margin-right: 10%;
}
</style>
