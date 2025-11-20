# Restaurant Management System

A comprehensive restaurant ordering system with multi-language support (English, Amharic, Afan Oromo) and separate panels for guests, kitchen staff, and owners.

## Features

- **Guest Panel**: Browse menu, place orders, view order history
- **Kitchen Panel**: Manage orders, update status, send notifications
- **Owner Panel**: Full control, menu management, analytics, customization
- **Multi-language Support**: English, አማርኛ (Amharic), Afan Oromo
- **Order Management**: Real-time order tracking and status updates
- **Customization**: Logo, colors, background, social media links
- **Export & Print**: Order history export to CSV and print functionality

## Default Login Credentials

- **Owner**: 
  - Username: `admin`
  - Password: `admin123`

- **Kitchen Staff**: 
  - Username: `kitchen`
  - Password: `kitchen123`

- **Guest**: No login required

## Project Structure

```
restaurant-management/
├── index.html          # Main application file
├── vercel.json         # Vercel configuration
└── README.md           # This file
```

## Deploy to Vercel

### Method 1: Using Vercel CLI

1. Install Vercel CLI:
```bash
npm i -g vercel
```

2. Navigate to your project folder:
```bash
cd your-project-folder
```

3. Deploy:
```bash
vercel
```

4. Follow the prompts and your site will be live!

### Method 2: Using Vercel Dashboard

1. Go to [vercel.com](https://vercel.com)
2. Sign up or log in
3. Click "Add New Project"
4. Import your Git repository (GitHub, GitLab, or Bitbucket)
5. Vercel will automatically detect the configuration
6. Click "Deploy"

### Method 3: Deploy from Local Folder

1. Go to [vercel.com](https://vercel.com) and log in
2. Install Vercel CLI: `npm i -g vercel`
3. In your project folder, run: `vercel`
4. Follow the prompts to deploy

## Local Development

Simply open `index.html` in your web browser. No build process required!

## Technologies Used

- HTML5
- CSS3 (Tailwind CSS via CDN)
- Vanilla JavaScript
- LocalStorage for data persistence
- Font Awesome for icons

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## License

MIT License - feel free to use for your restaurant or hotel!
