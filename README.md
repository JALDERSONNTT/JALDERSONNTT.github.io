# Contact Form - GitHub Pages

A simple, modern contact form webpage hosted on GitHub Pages. Users can submit their photo, name, company, and email.

## Features

- 📸 Photo capture and preview
- 👤 Name input
- 🏢 Company input
- 📧 Email input
- ✨ Clean, modern UI with gradient background
- 📱 Responsive design (works on mobile and desktop)

## Setup Instructions

### 1. Configure Email

Open `index.html` and find this line (around line 182):

```javascript
const response = await fetch('https://formsubmit.co/ajax/YOUR_EMAIL@example.com', {
```

Replace `YOUR_EMAIL@example.com` with your actual email address.

### 2. Deploy

The site is already live at: `https://JALDERSONNTT.github.io`

Just push any changes to the `main` branch and they'll be live in seconds!

## How It Works

- The form uses **FormSubmit.co** - a free service that sends form submissions to your email
- Photos are Base64 encoded and sent with the email
- No backend server needed!
- All processing happens in the browser

## First Time Setup (FormSubmit)

When someone submits the form for the first time, they'll receive a confirmation email from FormSubmit. You need to click the confirmation link to activate email delivery. After that, all submissions will come to your inbox.

## Customization

You can customize:
- **Colors**: Change the gradient in the `<style>` section
- **Text**: Update the heading and labels
- **Styling**: Modify CSS to match your brand

Enjoy your new contact form! 🎉