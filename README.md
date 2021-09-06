  <!-- Hi there! Feel free to make this your own but don't use my data -->
<div align="center">  
<h3>Hi there! 👋🤓<br>My name is Stephen Ajulu<br>I'm a Web Developer, Designer(Graphic, Web) & Creator(Content, Products)</h3>

<h4> <a href="https://links.stephenajulu.com">Links</a> • <a href="https://stephenajulu.com">Website</a> • <a href="https://ajulusthoughts.stephenajulu.com">Blog</a></h4>

<a href="https://stephenajulu.com"><img src="images/rsz 300w asset_1.png" width="100"></a>

<hr width="50%" style="height:5px;">

<h3>📕 My Latest Articles, Podcasts and Videos</h3>

<!-- BLOG-POST-LIST:START -->
- [5 Free Tools For Creating Ebooks](https://ajulusthoughts.stephenajulu.com/post/5-free-tools-for-creating-ebooks/)
- [Gradient Wallpaper Pack 3 is Out](https://ajulusthoughts.stephenajulu.com/post/gradient-wallpaper-pack-3-is-out/)
- [Simple Way To Be Healthy](https://ajulusthoughts.stephenajulu.com/post/simple-way-to-be-healthy/)
- [High Value In-Demand Skills](https://ajulusthoughts.stephenajulu.com/post/high-value-in-demand-skills/)
- [How To Build Wealth in Your Teens and 20s(Updated)](https://ajulusthoughts.stephenajulu.com/post/how-to-build-wealth-in-your-teens-and-20s/)
<!-- BLOG-POST-LIST:END -->

<h3>💼 What & Where I am currently working at/on/as</h3>

<p>
<a href="https://stephenajulu.com">Stephen Ajulu's Personal Portfolio Website: Freelancer</a>  🚀 <br>
<a href="https://uravity.netlify.app">Uravity: Director 💼</a> 🚀 <em>coming soon</em<br>
Sepochi Co Online Store: Founder and Dev 🚀 <em>coming soon</em><br>
PafectDate: Creator  🚀 <em>coming soon</em><br>
Purfolios: Creator  🚀 <em>coming soon</em><br>
The Noesis Magazine: Founder and Content Creator   🚀 <em>coming soon</em><br>
BioEmergency & Biomme: Founder and Developer  🚀 <em>coming soon</em><br>
Lofyd  🚀 <em>coming soon</em>
</p>

<h3>Kindly Support Me</h3>
  <a href="https://www.buymeacoffee.com/stephenajulu">Buy Me A Coffee ☕ </a>
  <p>Bitcoin Address: 1DmhaQPZ9Dt6ShHvypVZWFUqAiFdNpce84</p>
  <p>Ethereum Address: 0x4859A76fA806A533636024F30BB818Fb9787F22C</p>
  <p>CoinBase: @stephenajulu</p>
  <p><script type="text/javascript" src="https://cdnjs.buymeacoffee.com/1.0.0/button.prod.min.js" data-name="bmc-button" data-slug="stephenajulu" data-color="#FFDD00" dataemoji="" data-font="Cookie" data-text="Buy me a coffee" data-outline-color="#000000" data-font-color="#000000" data-coffee-color="#ffffff" ></script></p>
  <p><div id="smart-button-container"><div style="text-align: center;"><div id="paypal-button-container"></div></div></div></p>
  
  <h4>Affiliate Links</h4>
  <a target="_blank" href="https://santaluciafragrance.com/?ref=kuzqn53jomp-">Santa Lucia Fragrance: 10% OFF</a><br>
  <a target="_blank" href="https://www.esntls.co/?ref=kuzqn53jomp-">ESNTLS Clothing: 10% OFF</a><br>
  <a target="_blank" href="https://www.jadeblack.co/?ref=kuzqn53jomp-">JadeBlack Eyewear: 10% OFF</a><br>
  <a target="_blank" href="https://www.amazon.com/?&_encoding=UTF8&tag=stephenajulu-20&linkCode=ur2&linkId=bd4b7207444320b149d2437e9e3b0622&camp=1789&creative=9325">Amazon</a>
  
  </div>
  
  <script src="https://www.paypal.com/sdk/js?client-id=AVGpuNkOeI1IIjuGtAfpztXYkFDzvep9x4LHo6kGS96QEeTwdL1ChBorldoVIsawmGCrQzs5h06CC1ZC&enable-funding=venmo&currency=USD" data-sdk-integration-source="button-factory"></script>
  <script>
    function initPayPalButton() {
      paypal.Buttons({
        style: {
          shape: 'pill',
          color: 'silver',
          layout: 'vertical',
          label: 'paypal',
          
        },

        createOrder: function(data, actions) {
          return actions.order.create({
            purchase_units: [{"description":"Kindly Support Me by Donating via PayPal","amount":{"currency_code":"USD","value":5}}]
          });
        },

        onApprove: function(data, actions) {
          return actions.order.capture().then(function(orderData) {
            
            // Full available details
            console.log('Capture result', orderData, JSON.stringify(orderData, null, 2));

            // Show a success message within this page, e.g.
            const element = document.getElementById('paypal-button-container');
            element.innerHTML = '';
            element.innerHTML = '<h3>Thank you for your payment!</h3>';

            // Or go to another URL:  actions.redirect('thank_you.html');
            
          });
        },

        onError: function(err) {
          console.log(err);
        }
      }).render('#paypal-button-container');
    }
    initPayPalButton();
  </script>
