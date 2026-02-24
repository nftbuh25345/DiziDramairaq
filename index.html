<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>بحث المسلسلات</title>

<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;700&display=swap" rel="stylesheet">

<style>

:root{
--bg:#0b0f14;
--card:#121821;
--card-hover:#18202b;
--text:#ffffff;
--text-muted:#9aa4b2;
--accent:#229ED9;
--badge:#0b0f14cc;
--border:#1f2937;
}

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Cairo',sans-serif;
-webkit-tap-highlight-color: transparent;
}

body{
background:var(--bg);
color:var(--text);
}

/* الهيدر */

.header {
  background: #0f141b;
  padding: 16px;
  font-size: 22px;
  font-weight: 700;
  border-bottom: 1px solid var(--border);
  position: sticky;
  top: 0;
  z-index: 50;
  
  display: flex;
  justify-content: space-between;
  align-items: center;
}

/* زر طلب مسلسل */

.request-btn{

position:absolute;
left:12px;
top:10px;

display:flex;
align-items:center;
gap:6px;

background:var(--accent);
color:#fff;
border:none;
padding:8px 12px;
border-radius:10px;
font-size:14px;
cursor:pointer;

transition:0.2s;

}

.request-btn:hover{
background:#1b8bc3;
}

.request-btn:active{
transform:scale(0.95);
}

/* ايقونة telegram */

.telegram-icon{
width:18px;
height:18px;
fill:white;
}

/* البحث */

.search-box{
padding:14px;
background:#0f141b;
border-bottom:1px solid var(--border);
}

.search-box input{

width:100%;
padding:12px;
border-radius:12px;
border:1px solid var(--border);
background:#0b0f14;
color:white;
font-size:15px;
outline:none;

}

.search-box input:focus{
border-color:var(--accent);
}

/* النتائج */

.container{
padding:14px;
}

.grid{

display:grid;
grid-template-columns:repeat(auto-fill,minmax(150px,1fr));
gap:14px;

}

/* الكرت */

.card{

background:var(--card);
border-radius:14px;
overflow:hidden;
cursor:pointer;
transition:0.25s;
border:1px solid var(--border);

}

.card:hover{
transform:translateY(-4px);
background:var(--card-hover);
}

/* الصورة */

.poster{
position:relative;
}

.poster img{

width:100%;
aspect-ratio:2/3;
object-fit:cover;
display:block;

}

/* سنة */

.year-badge{

position:absolute;
top:8px;
left:8px;

background:var(--badge);
backdrop-filter:blur(4px);

padding:4px 8px;
font-size:11px;
border-radius:8px;
border:1px solid var(--border);

}

/* معلومات */

.card-info{
padding:10px;
}

.card-title{

font-size:14px;
font-weight:600;
line-height:1.5;

display:-webkit-box;
-webkit-line-clamp:2;
-webkit-box-orient:vertical;
overflow:hidden;

}

/* لا توجد نتائج */

.no-results{

text-align:center;
margin-top:40px;
color:var(--text-muted);
display:none;
font-size:15px;

}

</style>
</head>
<body>


<div class="header">
  
  <div class="header-title">
    بحث المسلسلات
  </div>
  
  <button class="request-btn" onclick="requestSeries()">
  
    <svg class="telegram-icon" viewBox="0 0 24 24">
      <path d="M9.04 15.47l-.39 5.49c.56 0 .81-.24 1.11-.53l2.66-2.54 5.51 4.03c1.01.56 1.73.27 1.98-.93l3.59-16.84.01-.01c.3-1.38-.5-1.92-1.49-1.55L1.64 9.33c-1.34.52-1.32 1.27-.23 1.61l5.59 1.75L19.02 5.2c.56-.34 1.07-.15.65.19" />
    </svg>
    
    طلب مسلسل
    
  </button>
  
</div>


<div class="search-box">
<input type="text" id="searchInput" placeholder="ابحث عن مسلسل...">
</div>


<div class="container">

<div class="grid" id="results"></div>

<div class="no-results" id="noResults">
لا توجد نتائج
</div>

</div>


<script>

/* رابط التليجرام */

const TELEGRAM_URL = "https://t.me/Hayal_215";


/* زر الطلب */

function requestSeries(){

window.open(TELEGRAM_URL,"_blank");

}


/* البيانات */

const series = [

{
  title: "Breaking Bad",
  year: "2008",
  img: "https://a.top4top.io/p_3707rbvys1.jpg",
  url: "https://t.me/+UZRKIzxpB_BkZmYy", // ضع رابط التليجرام هنا
  search: ["breaking bad", "بريكنغ باد", "bb"]
},

{
title:"Peaky Blinders",
year:"2013",
img:"https://i.imgur.com/2.jpg",
url:"#",
search:["peaky blinders","بيكي"]
}

];


/* عرض */

function showResults(list){

const results = document.getElementById("results");
const noResults = document.getElementById("noResults");

results.innerHTML="";

if(list.length==0){

noResults.style.display="block";
return;

}

noResults.style.display="none";

list.forEach(item=>{

const card=document.createElement("div");

card.className="card";

card.onclick=()=>{
window.location.href=item.url;
};

card.innerHTML=`

<div class="poster">

<img src="${item.img}">

<div class="year-badge">
${item.year}
</div>

</div>

<div class="card-info">
<div class="card-title">${item.title}</div>
</div>

`;

results.appendChild(card);

});

}


/* البحث */

document.getElementById("searchInput").addEventListener("input",function(){

const value=this.value.toLowerCase().trim();

const filtered=series.filter(item=>

item.title.toLowerCase().includes(value)

||

(item.search && item.search.some(s=>
s.toLowerCase().includes(value)
))

);

showResults(filtered);

});


/* بدء */

showResults(series);

</script>

</body>
</html>
