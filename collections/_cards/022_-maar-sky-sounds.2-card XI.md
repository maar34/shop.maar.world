---
layout: article
show_title: false
header:
  theme: dark
  background: 'linear-gradient(135deg, rgb(0, 255, 0), rgb(139, 34, 139, .1))'
#tags: Maar SkySounds Card
cover: https://www.dropbox.com/s/k3dljl4kkz9quxv/Thumb_SkySounds_2_11.jpg?raw=1

titles:
  # @start locale config
  en      : &EN       Maar Sky Sounds Card XI
  en-GB   : *EN
  en-US   : *EN
  en-CA   : *EN
  en-AU   : *EN

  # @end locale config
key: world-information
---
<br>
<div class="item">
  <div class="item__image">
    <img class="image image--lg" src="https://www.dropbox.com/s/t2z1dc1o4q8mh00/SkySounds2_11.jpg?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h2>Card XI:</h2>
    </div>
    <div class="item__description">
      <p>Electricity is not just a source of power, but a manifestation of the energy of the suns. It fuels all living things, from the tiniest microbe to the largest tree, and it is the force that drives the natural world. The energy of the suns is not just a physical phenomenon, but also a spiritual one. It is the force that animates all living things, and it is the source of inspiration for music and dance. This energy, known as prana, flows through all living things, sustaining them and giving them life. The inhabitants of this world understand that by tapping into this energy, they can not only light their homes and power their machines, but also nourish their souls and inspire their creativity. 

</p>
    </div>
  </div>
</div>


<div class="p-4">
  <div class="padding: ($spacer * 1.5); margin-top: $spacer*4;">
    <select class="select" id="link-selector">
      <option value="https://maarworld.gumroad.com/l/skysound1">ENT</option>
      <option value="https://maarworld.gumroad.com/">Physical</option>
      <option value="https://opensea.io/">Digital</option>
    </select>
    <button class="button button--primary  button--rounded" id="go-button">Buy</button>

    <div id="display-text" style="margin-top: 20px;"></div>

  </div>
</div>

<script>
  const linkSelector = document.querySelector("#link-selector");
  const displayText = document.querySelector("#display-text");

  linkSelector.addEventListener("change", function() {
    const selectedValue = linkSelector.value;
    switch (selectedValue) {
      case "https://maarworld.gumroad.com/l/skysound1":
        displayText.innerHTML = "Buy ENT Card - 0.34 eth";
        break;
      case "https://maarworld.gumroad.com/":
        displayText.innerHTML = "Buy Physical Card - 0.34 eth";
        break;
      case "https://opensea.io/":
        displayText.innerHTML = "Buy NFT Card - 0.34 eth ";
        break;
      default:
        displayText.innerHTML = "< Select your Card Type";
    }
  });

  // Trigger the change event manually to show the selected option value on page load
  linkSelector.dispatchEvent(new Event('change'));

  const goButton = document.querySelector("#go-button");
  goButton.addEventListener("click", function() {
      const selectedLink = linkSelector.value;
      window.open(selectedLink, "_blank");
    });
</script>

### Snippet

Please <a href="https://support.apple.com/en-gb/HT208353" rel="unmute" target="_blank"> unmute</a> 
your device and press PLAY ?????? button. 

<div class="container">
  <iframe class="responsive-iframe" src="https://play.maar.world/?g=8&d=0&c=0" style="border: 0" ></iframe>
</div>











