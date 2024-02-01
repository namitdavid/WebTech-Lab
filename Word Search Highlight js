let one = document.getElementById('one')
let searchbtn = document.getElementById('searchbtn')
searchbtn.addEventListener('click', ()=>{
    let input = document.getElementById('input').value;
    if(input!=="")
    {
        let reg=new RegExp(input,"gi");
        one.innerHTML=one.textContent.replace(reg,"<mark>$&</mark>");
    }
    
});
