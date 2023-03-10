---
layout: article
show_title: false
header:
  theme: dark
  background: 'linear-gradient(135deg, rgb(0, 255, 0), rgb(139, 34, 139, .1))'
#tags: Maar SkySounds Card
cover: https://www.dropbox.com/s/sl2jwunm4p7q1wv/Thumb_SkySounds_34.jpg?raw=1

titles:
  # @start locale config
  en      : &EN       Sky Sounds.1 Card II
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
    <img class="image image--lg" src="https://www.dropbox.com/s/k2gdp6saf52082y/SkySounds34.png?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h2>Wild Card:</h2>
    </div>
    <div class="item__description">
      <p> 
The world of Maar is a place of wonder and secrets, where the stars dance in the sky and the colors of the earth sing. It is a Circumbinary planet, where two suns embrace, and four moons keep watch. A world where triune brain beings roam, creatures of infinite creation and curiosity.
The Maar, a volcanic crater, is the heart of this world. It was born from a fiery kiss between the earth and the water, and it holds within it a lake as calm as a dream. The Maar is a place of pilgrimage, where the people of Maar come to listen to the whispers of the earth and the songs of the stars.
The Maar has been a source of inspiration for the people since ancient times. They have woven myths and legends around it, and they have created music that echoes its beauty and power. Music is woven into the fabric of their society, it is the rhythm of their days and the melody of their nights.
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







