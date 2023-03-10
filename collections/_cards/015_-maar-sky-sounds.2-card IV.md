---
layout: article
show_title: false
header:
  theme: dark
  background: 'linear-gradient(135deg, rgb(0, 255, 0), rgb(139, 34, 139, .1))'
#tags: Maar SkySounds Card
cover: https://www.dropbox.com/s/wydoxppqaz7dq79/Thumb_SkySounds_2_4.jpg?raw=1


titles:
  # @start locale config
  en      : &EN       Maar Sky Sounds.2 Card IV
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
  <img class="image image--lg" src="https://www.dropbox.com/s/sg8htvfqg1t9rf3/SkySounds2_4.png?raw=1"/>
  </div>
  <div class="item__content">
    <div class="item__header">
      <h2>Card IV:</h2>
    </div>
    <div class="item__description">
      <p>High up in the clouds, strange birds can be seen riding the wind in groups of six, a phenomenon known as flocking. These creatures possess an almost magical ability to navigate the skies in harmony, their synchronized movements creating a mesmerizing dance. The flocks of birds are an awe-inspiring sight, a reminder of the beauty and mystery of nature. The birds singing and descending to the ground is a ritual that happens every year. The inhabitants of this world look upon these birds with wonder and respect, for they represent the freedom and wildness of the natural world. They are a reminder that there is always something new to discover and that nature is full of surprises. Even though the inhabitants of this world have learned to predict and understand this ritual, they still see it with wonder and gratitude. 
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








