# MQG AI Day UK Website

A clean, modern website featuring the Databricks brand anthem video and downloadable PDF resources for the UK AI Day event.

## Features

- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Embedded Video**: Local MP4 video player with full controls
- **PDF Downloads**: Clean grid layout for PDF resources
- **Modern UI**: Gradient backgrounds and smooth animations

## File Structure

```
mqg_ai_day_uk/
├── index.html                                      # Main HTML file
├── styles.css                                      # CSS styling
├── assets/                                         # Folder for media files
│   ├── databricks-brand-anthem-fy26-15-sec.mp4    # Video file
│   ├── Databricks for Macquarie Group.pdf         # Platform overview PDF
│   └── Appendix - Financial Instituion Examples.pdf # Industry examples PDF
└── README.md                                       # This file
```

## Local Testing

To test locally, simply open `index.html` in your web browser. The video and PDFs will load from the local `assets/` folder.

## Hosting Options

### Free Hosting Platforms:

1. **Netlify** (Recommended)
   - Drag and drop deployment
   - Custom domains
   - HTTPS included
   - Visit: netlify.com

2. **Vercel**
   - GitHub integration
   - Fast deployment
   - Visit: vercel.com

3. **GitHub Pages**
   - Free with GitHub account
   - Git-based deployment
   - Visit: pages.github.com

4. **Firebase Hosting**
   - Google's platform
   - Fast global CDN
   - Visit: firebase.google.com

## Deployment Steps (Netlify - Easiest)

1. Go to [netlify.com](https://netlify.com)
2. Sign up for free
3. Drag the entire project folder to Netlify's deploy area
4. Your site will be live instantly with a random URL
5. You can customize the URL or add a custom domain

## Customization

- **QR Code**: Replace the placeholder in the QR code section with an actual QR code image
- **Colors**: Edit the CSS gradient and color variables in `styles.css`
- **Fonts**: Change the font-family in the CSS
- **Layout**: Modify the grid layout for different arrangements
- **Content**: Update titles, descriptions, and add more sections as needed

## Next Steps

1. **Add QR Code**: Generate a QR code for your website URL and replace the placeholder
2. **Test PDFs**: Ensure all PDF links work correctly
3. **Test Video**: Verify the video plays on different devices
4. **Deploy**: Upload to your preferred hosting platform

## Technical Notes

- Video uses HTML5 `<video>` tag for local playback
- PDFs open in a new tab when clicked
- Fully responsive design with mobile-first approach
- No external dependencies required
