# CLIO Research Project Webpage

This is a professional webpage for the CLIO research project.

## Features

- Responsive design that works on desktop and mobile
- Sections for abstract, introduction, method, results
- Figure grid layout for research images
- Video demonstration sections (local and YouTube)
- Citation section
- Professional gradient styling

## How to Use

### Adding Images

1. Create an `images` folder in this directory
2. Add your images (PNG, JPG, etc.)
3. In `index.html`, replace the placeholder divs with:
   ```html
   <img src="images/your-image.png" alt="Description">
   ```

### Adding Local Videos

1. Create a `videos` folder in this directory
2. Add your video files (MP4, WebM, etc.)
3. In `index.html`, replace the placeholder divs with:
   ```html
   <video controls>
       <source src="videos/your-video.mp4" type="video/mp4">
       Your browser does not support the video tag.
   </video>
   ```

### Adding YouTube Videos

Replace the placeholder with:
```html
<iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID" allowfullscreen></iframe>
```

Get the VIDEO_ID from your YouTube URL (the part after `v=` or `youtu.be/`)

## Customization

Edit the following in `index.html`:

- **Title and description**: Update the header section
- **Authors**: Replace "Author 1", "Author 2", etc.
- **Abstract**: Replace the placeholder text with your research abstract
- **Content**: Update all sections with your research content
- **Links**: Update the "Paper", "Code", "Dataset" buttons with actual URLs
- **Citation**: Update the BibTeX with your paper information
- **Colors**: Modify the CSS gradient colors (currently purple/blue theme)

## Opening the Webpage

Simply open `index.html` in any web browser:
- Double-click the file, or
- Right-click and select "Open With" → your browser

## Hosting Online

To host this webpage:

1. **GitHub Pages**: Push to a GitHub repo and enable Pages in settings
2. **Netlify**: Drag and drop the folder to netlify.com
3. **Your university server**: Upload via FTP/SFTP

## File Structure

```
clio/
├── index.html          # Main webpage
├── README.md          # This file
├── images/            # Create this folder for your figures
│   ├── architecture.png
│   ├── results.png
│   └── ...
└── videos/            # Create this folder for your video files
    ├── demo1.mp4
    ├── demo2.mp4
    └── ...
```

Enjoy showcasing your research!
