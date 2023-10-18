<!--
**yash-khanted/yash-khanted** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<div id="header" align="center" >
  <img src="https://media.giphy.com/media/USV0ym3bVWQJJmNu3N/giphy.gif" width="100"/>
</div>
    
<h3>Calling the Web Services in HTML5</h3> 
<script> 
    var xhr = new XMLHttpRequest( ); 
    xhr.onload = (res)=>{ 
       if(res.target.status == 200){ 
         document.body.innerHTML +=  
         (res.target.responseText); 
       } 
    } 
    xhr.open("GET",".../todos/1",true); 
    xhr.send(); 
</script>

