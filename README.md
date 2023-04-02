<div style="position:relative;">
  <img src="https://avatars.githubusercontent.com/u/1?v=4" width="200" height="200" style="border-radius:50%;"/>
  <div style="position:absolute; top:0; left:0; width:100%; height:100%; background-color:rgba(255,255,255,0.8); z-index:1; border-radius:50%; transform:scale(0); transition: transform 0.5s;"></div>
</div>

<script>
document.querySelector('div').addEventListener('mouseenter', () => {
  document.querySelector('div > div').style.transform = 'scale(1)';
});

document.querySelector('div').addEventListener('mouseleave', () => {
  document.querySelector('div > div').style.transform = 'scale(0)';
});
</script>
