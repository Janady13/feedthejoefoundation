# 🍕 Feed The Joe - AI Fundraising Website

A hilarious charity-style website where people can donate to "feed Joe" while getting AI agents and automation tools in return!

## 🎯 Features

- **Funny & Engaging Design**: Animated coffee cups, bouncing text, and interactive elements
- **Multiple Donation Tiers**: From $5 coffee to $100+ custom solutions
- **Direct Stripe Payment Links**: No API keys needed - payments work instantly!
- **Google AdSense Integration**: Monetization ready
- **AI Rewards System**: Each donor gets AI tools based on their contribution level
- **Responsive Design**: Works perfectly on all devices

## 💳 Stripe Products & Payment Links (ALL SET UP!)

All your payment links are ready to go - no configuration needed!

1. **Coffee Supporter ($5)**: [Payment Link](https://buy.stripe.com/eVq8wR9lBexv9yWeoT2Nq0Z)
2. **Pizza Patron ($25)**: [Payment Link](https://buy.stripe.com/14A7sNcxNbljfXk4Oj2Nq10)
3. **Buffet Boss ($50)**: [Payment Link](https://buy.stripe.com/cNi14p2Xdcpn4eCeoT2Nq11)
4. **Grocery God ($100)**: [Payment Link](https://buy.stripe.com/6oU7sN55l4WVbH42Gb2Nq12)
5. **Monthly Hero ($10/mo)**: [Subscription Link](https://buy.stripe.com/bJeaEZ0P560Z26udkP2Nq13)

## 🚀 Deployment Instructions (SUPER SIMPLE!)

### Deploy to Netlify in 2 Minutes:

1. **Drag and Drop Method** (Easiest):
   - Go to [Netlify Drop](https://app.netlify.com/drop)
   - Drag the entire project folder onto the page
   - Done! Your site is live!

2. **Command Line Method**:
   ```bash
   # Install Netlify CLI
   npm install -g netlify-cli
   
   # Deploy
   netlify deploy --prod --dir=.
   ```

3. **Connect to Your Domain**:
   - In Netlify dashboard, go to Domain Settings
   - Add custom domain: feedthejoe.com
   - Follow DNS instructions

That's it! No environment variables, no API keys, no complex setup!

## 📂 File Structure

```
/
├── index.html           # Main website with donation tiers
├── success.html         # Thank you page after donation
└── README.md           # This file
```

## 🎨 Customization

### Want to Change Payment Amounts?

Just update the payment links in index.html:
```javascript
const paymentLinks = {
    coffee: 'your_new_link_here',
    // etc...
};
```

### Want to Add New Tiers?

1. Create a new product in [Stripe Dashboard](https://dashboard.stripe.com/products)
2. Create a payment link for it
3. Add to the HTML and JavaScript

## 🤖 AI Agent Delivery

After someone donates, you'll see the payment in your [Stripe Dashboard](https://dashboard.stripe.com/payments):

1. Check who donated and what tier
2. Send them the appropriate AI tool:
   - **$5**: Basic chatbot template
   - **$25**: Custom AI assistant setup
   - **$50**: Full automation package
   - **$100**: Enterprise solution
   - **Monthly**: Ongoing access to all tools

## 📊 Track Your Success

- **Stripe Dashboard**: See all payments at https://dashboard.stripe.com
- **Google AdSense**: Track ad revenue
- **Netlify Analytics**: Monitor traffic

## 💰 You're Making Money Two Ways!

1. **Donations**: Direct payments through Stripe
2. **Ad Revenue**: Google AdSense (ca-pub-1158174357019592)

## 🎉 You're Ready to Launch!

Everything is configured and working:
- ✅ All payment links active
- ✅ Google AdSense integrated  
- ✅ No API keys needed
- ✅ No server functions required
- ✅ Just deploy and share!

## 🚦 Test First!

Before going live, test each payment link:
- Click each donation button
- Verify it goes to Stripe checkout
- Use test card: 4242 4242 4242 4242

---

*Made with 💜, ☕, and zero patience for complex setups*

**Just deploy and start collecting donations!** 🚀
