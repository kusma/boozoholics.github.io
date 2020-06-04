---
layout: default
---

**Upcoming parties :**  
[Robinson Boozoe 2021!](http://dritings.no/robinson-boozoe/)

<script>
var link = document.querySelector('[href="http://dritings.no/robinson-boozoe/"]');
if (link) {
  var str = link.innerText;
  console.log(str);
  var p = document.createElement('span');
  p.classList.add('sine-scroller');
  for (var i = 0; i < str.length; i++) {
    var s = document.createElement('span');
    s.innerText = str.charAt(i);
    s.style['animation-delay'] = `-${i * 0.3}s`;
    if (str.charAt(i) == ' ')
      s.style['width'] = '0.5em';
    p.appendChild(s);
  }
  link.innerText = null;
  link.appendChild(p);
}
</script>
<style>
@keyframes curve {
    0% {
        transform: translateY(0.5em);
    }
    50% {
        transform: translateY(-0.5em);
    }
    100% {
        transform: translateY(0.5em);
    }
}

.sine-scroller span {
  display: inline-block;
  animation: curve 3s ease-in-out infinite;
}
</style>

**Summer 2004 Booze Conquest Tour :**

Sweden Rock Festival (done!), Hultsfred (done!), Solskogen (done!),
Roskilde (done!), Altstork (done!), Skral Festival (done!),
Scene Event (done!), Kotkan Meripäivät (done!), MFX+Kewlers (done!),
Assembly (done!), Wacken Open Air (done!), Øyafestivalen (done!),
Evoke (done!), Turboneger @ Momarkedet (done!), Deilig (done!),
Kindergarden, Function
