---
layout: article
show_title: false
header:
  theme: dark
  background: 'linear-gradient(135deg, rgb(0, 255, 0), rgb(139, 34, 139, .1))'
#tags: Maar SkySounds Card
cover: https://www.dropbox.com/s/annm9o8t07jxrzs/Thumb_SkySounds_1_1.png?raw=1

titles:
  # @start locale config
  en      : &EN       Maar Sky Sounds Card I
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
    <img class="image image--lg" src="https://www.dropbox.com/s/qfzath7lo2pisex/SkySounds_1_1.png?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h2>Card I:</h2>
    </div>
    <div class="item__description">
      <p>
      <p>The north of Maar World is a place where the earth and water sing in harmony, yet it is also a place where the wildness of nature can be both beautiful and terrifying. The cliffs echo with the roar of the sea, and the forests rustle with the gentle flow of streams, creating a symphony of sound that is both serene and fierce. The inhabitants of the north have always listened to the songs of their land and they have woven them into their music, entangled flutes sing like the wind creating a melody that reflects the soundscapes of their surroundings. They have learned to appreciate the beauty and power of nature, yet also respect its potential dangers. The water and earth of the north have shaped their culture and society, teaching them to live in harmony with the elements and to respect their power. The soundscapes of the north are a reminder that we are all connected to the land and that there is always more to discover in the beauty and mystery of the multiverse.
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
