  <!-- Hi there! Feel free to make this your own but don't use my data -->
  
<div align="center">
  <a href="https://stephenajulu.com"><img src="images/stephenajulu header 2.png" alt="Ajulu's Header"></a>

  <br>
  
<h3>Hi there! 👋🤓<br>I'm Stephen Ajulu<br>an I.T Consultant, Web Developer, <br>Entrepreneur, Designer, <br>Creator and Cybsecurity Strategist</h3>

<h4> <a href="https://links.stephenajulu.com">Socials</a> • <a href="https://stephenajulu.com">Website</a> • <a href="https://ajulusthoughts.stephenajulu.com">Blog</a> • <a href="https://stephenajuluscard.carrd.co/">Business Card</a> </h4>

<a href="https://stephenajulu.com"><img src="images/rsz 300w asset_1.png" width="100"></a>

<hr width="50%" style="height:5px;">

<h3>📕 My Latest Articles, Podcasts and Videos</h3>

<!-- BLOG-POST-LIST:START -->
- [Gradient Wallpaper Pack Version 1 is Out](https://ajulusthoughts.stephenajulu.com/post/gradient-wallpaper-pack-version-1-is-out/)
- [Ajulu's Thoughts Tech Stack](https://ajulusthoughts.stephenajulu.com/post/ajulu-s-thoughts-tech-stack/)
- [Key Ideas In "The Big Fat Surprise" by Nina Teicholz](https://ajulusthoughts.stephenajulu.com/post/key-ideas-in-the-big-fat-surprise-by-nina-teicholz/)
- [Investment Opportunities](https://ajulusthoughts.stephenajulu.com/post/investment-opportunities/)
- [How to Become Healthy + My Tips](https://ajulusthoughts.stephenajulu.com/post/how-to-become-healthy-my-tips/)
<!-- BLOG-POST-LIST:END -->

<h3>💼 What & Where I am currently working at/on/as</h3>

<p>
<a href="https://owlsectechnologies.co.ke">OwlSec Technologies: Founder and Consultant 💼</a><br>
<a href="https://thebistronewsletter.netlify.app">The Bistro Ke Daily Newsletter: Founder, Editor in Chief and Developer ☕</a><br>
<a href="https://saoainc.netlify.app">SAOA Media, Tech and Agriculture: Founder, Designer and Developer 💼</a><br>
<a href="https://thenoesismagazine.netlify.app">The Noesis Magazine: Chief Editor, Developer and Founder ✒</a><br>
<a href="https://stephenajulu.com">Open World: Freelance 🌐</a><br>
Sepochi Co Online Store: Founder and Dev 🚀 <em>coming soon</em><br>
<a href="https://stephenajulu.com">Stephen Ajulu's Personal Portfolio, Blog and Notes Website: Owner and Developer</a>  🚀 ....<br>
<a href="https://greeetincard.carrd.co">GreeetinCard: Founder, Developer and Designer</a>  🚀 <em>coming soon</em><br>
Tech6: Founder and Developer  🚀 <em>coming soon</em><br>
<a href="https://this1.netlify.app">T.H.I.S: Founder, Developer and Data Entry</a>  🚀 <em>coming soon</em><br>
BioEmergency & Biomme: Founder and Developer  🚀 <em>coming soon</em><br>
Lofyd  🚀 <em>coming soon</em>
</p>

<h3>Kindly Support Me</h3>
  
<script type="text/javascript" src="https://cdnjs.buymeacoffee.com/1.0.0/button.prod.min.js" data-name="bmc-button" data-slug="stephenajulu" data-color="#FFDD00" data-emoji=""  data-font="Bree" data-text="Buy me some coffee" data-outline-color="#000000" data-font-color="#000000" data-coffee-color="#ffffff" ></script>
  
  <div id="smart-button-container">
      <div style="text-align: center;">
        <div style="margin-bottom: 1.25rem;">
          <p>Support Me</p>
          <select id="item-options"><option value="1 USD/100 KES" price="1">1 USD/100 KES - 1 USD</option><option value="5 USD/500 KES" price="5">5 USD/500 KES - 5 USD</option><option value="10 USD/1000 KES" price="10">10 USD/1000 KES - 10 USD</option><option value="50 USD/5000 KES" price="50">50 USD/5000 KES - 50 USD</option><option value="0.50 USD/50 KES" price="0.50">0.50 USD/50 KES - 0.50 USD</option></select>
          <select style="visibility: hidden" id="quantitySelect"></select>
        </div>
      <div id="paypal-button-container"></div>
      </div>
    </div>
    <script src="https://www.paypal.com/sdk/js?client-id=AVGpuNkOeI1IIjuGtAfpztXYkFDzvep9x4LHo6kGS96QEeTwdL1ChBorldoVIsawmGCrQzs5h06CC1ZC&enable-funding=venmo&currency=USD" data-sdk-integration-source="button-factory"></script>
    <script>
      function initPayPalButton() {
        var shipping = 0;
        var itemOptions = document.querySelector("#smart-button-container #item-options");
    var quantity = parseInt();
    var quantitySelect = document.querySelector("#smart-button-container #quantitySelect");
    if (!isNaN(quantity)) {
      quantitySelect.style.visibility = "visible";
    }
    var orderDescription = 'Support Me';
    if(orderDescription === '') {
      orderDescription = 'Item';
    }
    paypal.Buttons({
      style: {
        shape: 'rect',
        color: 'gold',
        layout: 'vertical',
        label: 'paypal',
        
      },
      createOrder: function(data, actions) {
        var selectedItemDescription = itemOptions.options[itemOptions.selectedIndex].value;
        var selectedItemPrice = parseFloat(itemOptions.options[itemOptions.selectedIndex].getAttribute("price"));
        var tax = (0 === 0) ? 0 : (selectedItemPrice * (parseFloat(0)/100));
        if(quantitySelect.options.length > 0) {
          quantity = parseInt(quantitySelect.options[quantitySelect.selectedIndex].value);
        } else {
          quantity = 1;
        }

        tax *= quantity;
        tax = Math.round(tax * 100) / 100;
        var priceTotal = quantity * selectedItemPrice + parseFloat(shipping) + tax;
        priceTotal = Math.round(priceTotal * 100) / 100;
        var itemTotalValue = Math.round((selectedItemPrice * quantity) * 100) / 100;

        return actions.order.create({
          purchase_units: [{
            description: orderDescription,
            amount: {
              currency_code: 'USD',
              value: priceTotal,
              breakdown: {
                item_total: {
                  currency_code: 'USD',
                  value: itemTotalValue,
                },
                shipping: {
                  currency_code: 'USD',
                  value: shipping,
                },
                tax_total: {
                  currency_code: 'USD',
                  value: tax,
                }
              }
            },
            items: [{
              name: selectedItemDescription,
              unit_amount: {
                currency_code: 'USD',
                value: selectedItemPrice,
              },
              quantity: quantity
            }]
          }]
        });
      },
      onApprove: function(data, actions) {
        return actions.order.capture().then(function(details) {
          alert('Transaction completed by ' + details.payer.name.given_name + '!');
        });
      },
      onError: function(err) {
        console.log(err);
      },
    }).render('#paypal-button-container');
  }
  initPayPalButton();
    </script>
  
  <h4>Affiliate Links</h4>
  <a href="https://santaluciafragrance.com/?ref=kuzqn53jomp-">Santa Lucia Fragrance</a>
  <a href="https://www.esntls.co/?ref=kuzqn53jomp-">ESNTLS Clothing</a>
  <a href="https://www.jadeblack.co/?ref=kuzqn53jomp-">JadeBlack Eyewear</a>
  
  </div>
