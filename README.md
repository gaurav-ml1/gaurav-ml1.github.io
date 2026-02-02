# Full Stack Developer Roadmap - Interactive Website

An interactive, engaging website featuring a complete Full Stack Development learning roadmap with progress tracking.

## ✨ Features

### Interactive Elements
- **Flip Cards** on homepage - Click cards to see detailed tech stacks
- **Animated Counters** - Statistics that count up when scrolled into view
- **Progress Tracking** - Click skills to mark as completed (saves to browser)
- **Real-time Progress Bar** - Visual representation of your learning journey
- **Responsive Design** - Perfect on mobile, tablet, and desktop

### Pages
1. **Home** - Eye-catching hero with interactive flip cards
2. **About** - Learn about the roadmap and learning phases
3. **Roadmap** - Complete interactive roadmap with 30+ skills to track
4. **Contact** - Get in touch form with community links

## 🎯 Interactive Roadmap Features

The roadmap page includes:
- ✅ **Click to Complete** - Click any skill to mark it as learned
- 📊 **Progress Tracking** - See your completion percentage
- 💾 **Auto-Save** - Progress saved in your browser
- 🔄 **Reset Option** - Start fresh anytime
- 🎨 **Visual Feedback** - Completed skills turn green with checkmarks

## 🚀 How to Deploy on GitHub Pages (FREE)

### Step 1: Create a GitHub Account
1. Go to https://github.com
2. Click "Sign up" and create a free account

### Step 2: Create a New Repository
1. Once logged in, click the "+" icon in top right corner
2. Select "New repository"
3. Name it: `your-username.github.io` (replace `your-username` with your actual GitHub username)
   - Example: If your username is "johnsmith", name it `johnsmith.github.io`
4. Make it **Public**
5. DO NOT initialize with README
6. Click "Create repository"

### Step 3: Upload Your Website Files
1. On the repository page, click "uploading an existing file"
2. Drag and drop ALL these files:
   - index.html
   - about.html
   - roadmap.html
   - contact.html
   - style.css
3. Scroll down and click "Commit changes"

### Step 4: Enable GitHub Pages
1. Go to your repository Settings (tab at the top)
2. Scroll down to "Pages" in the left sidebar
3. Under "Source", select "main" branch
4. Click "Save"

### Step 5: Access Your Website
After 1-2 minutes, your website will be live at:
`https://your-username.github.io`

## 🎨 Customization Guide

### Change the Site Name
Open all HTML files and replace "Full Stack Roadmap" with your desired name.

### Change Colors
Open `style.css` and modify these colors:
- `#667eea` and `#764ba2` - Main gradient colors (purple theme)
- `#2c3e50` - Dark blue (navbar, footer, headings)
- `#28a745` - Green (completed skills)

### Customize the Roadmap
Edit `roadmap.html` to:
- Add or remove skills
- Change learning phases
- Modify phase descriptions
- Add your own learning resources

### Add More Interactive Features
The site uses vanilla JavaScript for interactivity:
- Flip cards animation (index.html)
- Counter animation (index.html)
- Progress tracking with localStorage (roadmap.html)

### Update Content
Edit the HTML files to change:
- Text content
- Email, contact information
- Roadmap skills and phases
- Learning resources and links

### Add Your Own Images
1. Create an `images` folder
2. Upload images to GitHub
3. Reference them in HTML: `<img src="images/your-image.jpg">`

## 🎮 Using the Interactive Features

### Progress Tracking
- Your progress is automatically saved in your browser
- Click any skill on the roadmap to mark it complete
- Data persists even if you close the browser
- Use the "Reset Progress" button to start over

### Flip Cards
- Click the cards on the homepage to flip them
- Front shows category, back shows detailed tech stack
- Click again to flip back

### Animated Counters
- Statistics animate when you scroll to them
- Numbers count up from 0 to target value
- Creates engaging visual effect

## Making Contact Form Work

The contact form is currently just a demo. To make it functional, you can use:

1. **Formspree** (easiest):
   - Go to https://formspree.io
   - Create free account
   - Get your form endpoint
   - Update contact.html form action

2. **EmailJS**:
   - Go to https://www.emailjs.com
   - Follow their integration guide

3. **Netlify Forms** (if you switch to Netlify):
   - Just add `netlify` attribute to form tag

## Alternative Deployment Options

### Netlify (Also Free)
1. Go to https://netlify.com
2. Sign up for free
3. Drag and drop your website folder
4. Get a URL like `your-site.netlify.app`
5. Can add custom domain later

### Vercel (Also Free)
1. Go to https://vercel.com
2. Sign up for free
3. Import from GitHub or upload files
4. Get instant deployment

## Support

Your website is now live and will remain free forever on GitHub Pages!

To update your website in the future:
1. Edit the files on your computer
2. Go to your GitHub repository
3. Click "Add file" > "Upload files"
4. Upload the updated files
5. Changes will be live in 1-2 minutes

## License
Free to use and modify for personal or commercial projects.
