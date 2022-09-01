# APIVanilla
consumindo dados da API GitHub 


#Link da aplicação --> https://apiv-anilla-nadiduno.vercel.app/


Design e layout by 
[@nadiduno](https://www.instagram.com/nadiduno.csv/)

´´´
async function bucarDados(){
  try{
    const response = await fetch ('https://api.github.com/users/nadiduno');
  const body = await response.json();
  return body;
  } catch (err){
    console.log("Deu")
  } finally{
    console.log("Deu")
  }
}
bucarDados().then(body => {
  // console.log(body);
  var avatar_url=body.avatar_url;
  var name=body.name;
´´´´
