# Shopee Voucher Auto Claim

#### Usage
1. Go to the website and press F12.
2. Copy and paste the script below and paste into your browser developer console.
3. Press `ENTER`.

```
setInterval( function () { var claimBtn = Array.from(document.querySelectorAll('button')) .find(el => el.textContent === 'Claim'); claimBtn.click() }, 100)
```
##### Disclaimer: This script is for educational purposes only. Use at your own risk, you may be banned from the site for botting activities.
