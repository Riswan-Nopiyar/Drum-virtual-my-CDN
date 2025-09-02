# 🎵 Drum Virtual Embed Guide
## Link demo <a href="https://riswan-nopiyar.github.io/Drum-virtual-my-CDN/">Open</a>
### 🇺🇸 Method 1: Direct iframe Embed  
### 🇮🇩 Cara 1: Langsung menggunakan iframe  

```html
<!-- Simple iframe embed -->
<iframe 
  src="https://riswan-nopiyar.github.io/Drum-virtual-my-CDN/" 
  width="100%" 
  height="500" 
  style="border:1px solid #ccc; border-radius:8px;">
</iframe>
```


### 🇺🇸 Method 2: Toggle Button with iframe (using script)
### 🇮🇩 Cara 2: Tombol buka/tutup dengan iframe (menggunakan script) 

```html
<!-- Button to toggle iframe -->
<button 
  onclick="var f=document.getElementById('drum-frame'); f.style.display = (f.style.display==='none' ? 'block':'none');" 
  style="padding:8px 16px; background:#007BFF; color:#fff; border:none; border-radius:6px; cursor:pointer;">
  🎶 Show / Hide Drum Virtual
</button>

<!-- Iframe hidden by default -->
<div id="drum-frame" style="margin-top:10px; display:none;">
  <iframe 
    src="https://riswan-nopiyar.github.io/Drum-virtual-my-CDN/" 
    width="100%" 
    height="500" 
    style="border:1px solid #ccc; border-radius:8px;">
  </iframe>
</div>
```
<img width="1085" height="591" alt="image" src="https://github.com/user-attachments/assets/89d35999-87fb-4b20-a756-1e2dc8cf476a" />
