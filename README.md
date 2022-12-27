[![Author](https://img.shields.io/badge/Dev-Nadi%20Duno-blueviolet%20)](https://portfolio-nadi.vercel.app/)
[![Social](https://img.shields.io/twitter/follow/nadiduno?label=%40nadiduno&style=social)](https://twitter.com/nadiduno)
[![Linkedin](https://img.shields.io/badge/in-Nadi%20Duno-blue)](https://www.linkedin.com/in/nadiduno/)
<br />
<br />

# APIVanilla
Consumindo dados da API GitHub 


#Link da aplicação --> https://apiv-anilla-nadiduno.vercel.app/


Design e layout by 
[@nadiduno](https://www.instagram.com/nadiduno.csv/)

```
async function bucarDados(){
  try{
    const response = await fetch ('https://api.github.com/users/nadiduno');
  const body = await response.json();
  return body;
  } catch (err){
    console.log("Erro")
  } finally{
    console.log("Finally")
  }
}
bucarDados().then(body => {
  console.log(body); 
  //var name=body.name;
  //GURDAR EM UMA VARIAVEL
  //document.body.innerText=JSON.stringify(Object.values(body));
  // MOSTAR EM TELA
}
```
Nadi Duno
