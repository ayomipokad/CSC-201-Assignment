# University Admission Checker - Assignment Screenshot Generator

A simple web application for students to generate assignment screenshots showing Python IDLE output and code.

## Features

- ✅ Input student information (name, O-level credits, JAMB score, age)
- ✅ Generate two screenshots:
  1. **Output Screenshot** - Shows the program execution with student's input and result
  2. **Code Screenshot** - Shows the Python code in IDLE editor
- ✅ Automatic eligibility checking based on criteria:
  - At least 5 O-level credits
  - JAMB score of 200 or above
  - Age 16 or above
- ✅ Download screenshots as PNG files

## How to Deploy on Vercel

### Method 1: Deploy via GitHub (Recommended)

1. **Create a GitHub repository:**
   - Go to [GitHub](https://github.com) and create a new repository
   - Name it something like `admission-checker`

2. **Upload files to GitHub:**
   - Upload `index.html` and `vercel.json` to your repository

3. **Deploy to Vercel:**
   - Go to [Vercel](https://vercel.com)
   - Sign in with your GitHub account
   - Click "Add New Project"
   - Import your GitHub repository
   - Click "Deploy"
   - Done! Your site will be live at `your-project-name.vercel.app`

### Method 2: Deploy via Vercel CLI

1. **Install Vercel CLI:**
   ```bash
   npm install -g vercel
   ```

2. **Deploy:**
   ```bash
   cd your-project-folder
   vercel
   ```

3. Follow the prompts and your site will be deployed!

### Method 3: Drag and Drop

1. Go to [Vercel](https://vercel.com)
2. Click "Add New Project"
3. Drag and drop your project folder
4. Click "Deploy"

## Usage

1. Open the website
2. Fill in the student information:
   - Student Name
   - Number of O-level Credits
   - JAMB Score
   - Student Age
3. Click "Generate Screenshots"
4. Download both screenshots:
   - Output screenshot (shows execution result)
   - Code screenshot (shows the Python code)

## File Structure

```
.
├── index.html       # Main application file (contains HTML, CSS, and JavaScript)
├── vercel.json      # Vercel deployment configuration
└── README.md        # This file
```

## Technical Details

- Pure HTML/CSS/JavaScript (no backend required)
- Uses HTML5 Canvas for screenshot generation
- Uses html2canvas library (loaded via CDN)
- Fully responsive design
- Client-side validation

## Notes

- All processing happens in the browser (no data is sent to any server)
- Screenshots are generated using Canvas API
- Works on all modern browsers
- No database or backend required

## Support

If you encounter any issues, make sure:
- You're using a modern browser (Chrome, Firefox, Safari, Edge)
- JavaScript is enabled
- You have a stable internet connection (for loading the html2canvas library)

## License

Free to use for educational purposes.
