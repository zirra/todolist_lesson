<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    
      <h4>A glimpse of all the cool things that I'm currently in to.</h4> 
  
<div class="box-1">
    <h3>Taekwondo</h3>
    <img alt="Taekwondo logo" src="../assets/images-wixmp-ed30a86b8c4ca887773594c2_wixmp_com-dddq35g-e23f4908-95a3-4af7-bc7b-e34000f5ed7f.png">
    <ul>
      <li><a href="https://www.southaustintkd.com/" target="_blank" rel="noopener">Taekwondo</a></li>
    </ul>
</div>
<div class="box-2">
    <h3>Dirt Biking</h3>
    <img alt="Dirt Bike logo" src="../assets/dirtbike_m.png">
    <ul>
      <li><a href="https://littlespeedsters.com/" target="_blank" rel="noopener">Dirt Bike</a></li>
    </ul>
  </div>
  <div class="box-3">
    <h3>Fitness and Technology</h3>
    <img alt="Fitness logo" src="../assets/Fitness-Industry-Technology-Trends.png">
    <ul>
      <li><a href="https://www.mirror.co/shop/mirror?utm_source=google_ads&utm_medium=search_cpc&utm_campaign=brand_mirror&utm_content=mirror_workout&utm_term=mirror%20workout" target="_blank" rel="noopener">Fitness and Technology</a></li>
    </ul>
  </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: {
      type: String
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
img {
  width: 100%;
  display: flex;
	justify-content: left;
}
.box-1 img{
  width: 20%;
}

h1 {
  color: blue;
}

* {
  background-color: yellow;
}

.box-1 h3{
  margin: 10px 0 0;
  display: flex;
	justify-content: left;
	margin-bottom: -9px;
	padding: 11px;
}

.box-1 ul{
  margin: 10px 0 0;
  display: flex;
	justify-content: left;
	margin-bottom: -9px;
	padding: 11px;	
}

.box-2 img{
  width: 20%;
  display: flex;
  margin: auto;
  justify-content: center;
}

.box-2 ul{
  margin: 10px 50 0;
  display: flex;
	justify-content: center;
	margin-bottom: -9px;
	padding: 30px;	
}

.box-2 h3{
  margin: 10px 50 0;
  display: flex;
	justify-content: center;
	margin-bottom: -9px;
	padding: 10px;	
}

.box-3 img{
  width: 20%;
  display: flex;
	float: right;
	margin-bottom: -9px;
  margin-top: -10px;
  margin-left: 950px;
	padding: 10px;	
}

.box-3 ul{
  margin: 45px 0 0;
  display: flex;
	float: right;
	margin-bottom: -9px;
  margin-top: 3px;
  margin-right: -8px;
	padding: 10px;
}

.box-3 h3{
  margin: 10px 0 0;
  display: flex;
	float: right;
	margin-bottom: -2px;
	padding: 11px;	
}

h3 {
  margin: 20px 0 0;
  display: flex;
	justify-content: left;
	margin-bottom: -9px;
	padding: 10px;
  color: blue;	
}

ul{
  margin: -20px 0 0;
  display: flex;
	justify-content: left;
	margin-bottom: -9px;
	padding: 11px;
}


ol li {
  display: list-item;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: red;
}
</style>


