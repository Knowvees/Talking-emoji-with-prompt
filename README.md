# Talking-emoji-with-prompt
A talking emoji that collects text through a prompt box

The code is very simple, but the effect is very interesting. The emoji looks like it is talking.

link to working code https://jsbin.com/kifobufagi/edit?html,css,js,output

setInterval(_=>{
  document.body.innerHTML = [
    ..."😮😀😁😐😑😬"
  ][~~(Math.random()*6)]
},95)
