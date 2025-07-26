# Auth Frontend

A modern React authentication frontend with JWT token management, built for deployment on Netlify.

## Features

- 🔐 **JWT Authentication** - Secure login/register system
- 🛡️ **Protected Routes** - Dashboard accessible only when authenticated  
- 📱 **Responsive Design** - Works perfectly on desktop and mobile
- ✨ **Modern UI** - Beautiful gradient design with smooth animations
- 🔄 **Auto Token Validation** - Automatic session management
- ⚡ **Fast & Lightweight** - Single HTML file with CDN dependencies

## Backend Integration

This frontend connects to: `https://btechng-backend.onrender.com`

API Endpoints used:
- `POST /api/auth/register` - User registration
- `POST /api/auth/login` - User login  
- `GET /api/user` - Protected user data

## Quick Deploy to Netlify

### Method 1: Git Integration (Recommended)
1. Fork or clone this repository
2. Connect your Netlify account to GitHub
3. Select this repository for deployment
4. Deploy settings:
   - Build command: (leave empty)
   - Publish directory: `/` (root)
5. Deploy!

### Method 2: Manual Upload
1. Download all files from this repository
2. Drag the folder into Netlify's deploy area
3. Your app will be live instantly!

## Local Development

Simply open `index.html` in your browser - no build process required!

## File Structure

```
├── index.html          # Main application file
├── _redirects          # Netlify routing configuration
└── README.md          # This file
```

## Technologies Used

- React 18 (via CDN)
- React Router DOM 6
- Modern CSS with gradients and animations
- JWT token management
- Local Storage for persistence

## Customization

To modify the backend URL, update line 94 in `index.html`:
```javascript
const API_BASE_URL = 'https://your-backend-url.com';
```

## Browser Support

- ✅ Chrome/Edge 88+
- ✅ Firefox 85+  
- ✅ Safari 14+
- ✅ Mobile browsers

---

Built with ❤️ for modern web authentication
