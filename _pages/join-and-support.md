---
layout: page
title: Join & Support
permalink: "/support/"
image_path: "/images/about.jpg"
menu: true
menu_position: 4

---
Membership in the AAS is open to everyone. The AAS membership includes a broad range of people, from those with a passing interest in archaeology or history, to people who are passionate about archaeological artifacts, to avocational archaeologists, to professional archaeologists. Membership benefits include opportunities to work with archaeologists on digs around the state, field trips to archaeological sites, semi-annual state meetings, the annual edition of the Journal of Alabama Archaeology, and the Stones & Bones newsletter.

Pay your dues or send a donation online! We are working on an automated method for paying dues and making donations, but until that is available you can avoid sending a check in the mail by logging into your personal PayPal account and sending money to the AAS PayPal account. Follow these simple steps:

1. Log in to your PayPal account at (link: http://paypal.com).
2. Choose the Send Money tab.
3. Type **alabamaarchaeology@gmail.com** in the To (Email or mobile phone) field.
4. Type the amount of money that you wish to send to the AAS (see the membership types and associated dues at the bottom of this page).
5. Type a message to tell us what you are sending the money for, i.e. a donation for a particular AAS fund, or dues for a foreign family lifetime membership. Important: If you are joining AAS or renewing your membership, include your USPS address in this message.

OR

Use this guest check out:

<div id="smart-button-container"> <div style="text-align: center"><label for="description">Please leave a detailed note of what the donation is for (i.e. membership dues, scholarship donation, etc.) </label><input type="text" name="descriptionInput" id="description" maxlength="127" value=""></div> <p id="descriptionError" style="visibility: hidden; color:red; text-align: center;">Please enter a description</p> <div style="text-align: center"><label for="amount">$ </label><input name="amountInput" type="number" id="amount" value="" ><span> USD</span></div> <p id="priceLabelError" style="visibility: hidden; color:red; text-align: center;">Please enter a price</p> <div id="invoiceidDiv" style="text-align: center; display: none;"><label for="invoiceid"> </label><input name="invoiceid" maxlength="127" type="text" id="invoiceid" value="" ></div> <p id="invoiceidError" style="visibility: hidden; color:red; text-align: center;">Please enter an Invoice ID</p> <div style="text-align: center; margin-top: 0.625rem;" id="paypal-button-container"></div> </div> <script src="[https://www.paypal.com/sdk/js?client-id=sb&enable-funding=venmo&currency=USD](https://www.paypal.com/sdk/js?client-id=sb&enable-funding=venmo&currency=USD "https://www.paypal.com/sdk/js?client-id=sb&enable-funding=venmo&currency=USD")" data-sdk-integration-source="button-factory"></script> <script> function initPayPalButton() { var description = document.querySelector('#smart-button-container #description'); var amount = document.querySelector('#smart-button-container #amount'); var descriptionError = document.querySelector('#smart-button-container #descriptionError'); var priceError = document.querySelector('#smart-button-container #priceLabelError'); var invoiceid = document.querySelector('#smart-button-container #invoiceid'); var invoiceidError = document.querySelector('#smart-button-container #invoiceidError'); var invoiceidDiv = document.querySelector('#smart-button-container #invoiceidDiv'); var elArr = \[description, amount\]; if (invoiceidDiv.firstChild.innerHTML.length > 1) { invoiceidDiv.style.display = "block"; } var purchase_units = \[\]; purchase_units\[0\] = {}; purchase_units\[0\].amount = {}; function validate(event) { return event.value.length > 0; } paypal.Buttons({ style: { color: 'blue', shape: 'rect', label: 'checkout', layout: 'vertical', }, onInit: function (data, actions) { actions.disable(); if(invoiceidDiv.style.display === "block") { elArr.push(invoiceid); } elArr.forEach(function (item) { item.addEventListener('keyup', function (event) { var result = elArr.every(validate); if (result) { actions.enable(); } else { actions.disable(); } }); }); }, onClick: function () { if (description.value.length < 1) { descriptionError.style.visibility = "visible"; } else { descriptionError.style.visibility = "hidden"; } if (amount.value.length < 1) { priceError.style.visibility = "visible"; } else { priceError.style.visibility = "hidden"; } if (invoiceid.value.length < 1 && invoiceidDiv.style.display === "block") { invoiceidError.style.visibility = "visible"; } else { invoiceidError.style.visibility = "hidden"; } purchase_units\[0\].description = description.value; purchase_units\[0\].amount.value = amount.value; if(invoiceid.value !== '') { purchase_units\[0\].invoice_id = invoiceid.value; } }, createOrder: function (data, actions) { return actions.order.create({ purchase_units: purchase_units, }); }, onApprove: function (data, actions) { return actions.order.capture().then(function (orderData) { // Full available details console.log('Capture result', orderData, JSON.stringify(orderData, null, 2)); // Show a success message within this page, e.g. const element = document.getElementById('paypal-button-container'); element.innerHTML = ''; element.innerHTML = '<h3>Thank you for your payment!</h3>'; // Or go to another URL: actions.redirect('thank_you.html'); }); }, onError: function (err) { console.log(err); } }).render('#paypal-button-container'); } initPayPalButton(); </script>

[For those that prefer US Mail, please click this box to fill out our Membership Form, and mail it along with payment to:](/uploads/aasmembership.pdf){: .button.button-primary}

Alabama Archaeological Society

UWA Station 22

University of West Alabama

Livingston, AL 35470

| **Member Type** | **U.S. Address** | **Foreign Address** |
| **Annual Associate (younger than 18)** | **$15.00** | **$20.00** |
| **Annual Individual** | **$25.00** | **$30.00** |
| **Annual Family** | **$30.00** | **$35.00** |
| **Annual Institutional** | **$50.00** | **$55.00** |
| **Annual Sustaining Individual** | **$35.00** | **$40.00** |
| **Annual Sustaining Joint** | **$40.00** | **$45.00** |
| **Life Individual** | **$500.00** | **$600.00** |
| **Life Joint** | **$600.00** | **$700.00** |

<div style="clear:both;"> </div>