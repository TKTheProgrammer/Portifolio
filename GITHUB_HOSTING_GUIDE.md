# How to Host Your Portfolio on GitHub Pages

## Step-by-Step Guide for Beginners

This guide will walk you through hosting your portfolio on GitHub Pages from scratch. No prior GitHub experience needed!

---

## 📋 What You'll Need

- [ ] A GitHub account (we'll create one if you don't have it)
- [ ] Your portfolio files:
  - `index.html`
  - `Bots_commission_NB.png`
  - `README.md` (optional but recommended)

---

## 🚀 Method 1: Using GitHub Web Interface (Easiest - Recommended for Beginners)

### Step 1: Create a GitHub Account (Skip if you already have one)

1. Go to [https://github.com](https://github.com)
2. Click **"Sign up"** in the top right corner
3. Enter your email, create a password, and choose a username
4. Complete the verification
5. Verify your email address

**Important:** Remember your username! You'll need it for the next step.

---

### Step 2: Create a New Repository

1. **Log in to GitHub**
2. **Click the "+" icon** in the top right corner of the page
3. **Select "New repository"** from the dropdown menu

   ![Where to find New Repository button]

4. **Fill in the repository details:**
   - **Repository name:** `tktheprogrammer.github.io`
     - ⚠️ **CRITICAL:** It MUST be exactly: `your-username.github.io`
     - Replace "your-username" with YOUR actual GitHub username
     - Example: If your username is "tktheprogrammer", name it "tktheprogrammer.github.io"
   
   - **Description:** (Optional) "My game development portfolio"
   
   - **Public/Private:** Select **Public** (must be public for free GitHub Pages)
   
   - **Initialize repository:** Leave all checkboxes UNCHECKED
     - Don't add README
     - Don't add .gitignore
     - Don't choose a license

5. **Click "Create repository"** (green button at the bottom)

---

### Step 3: Upload Your Files

You'll now see a page with instructions. Here's what to do:

1. **Look for the section that says:** "...or upload an existing file"
   
2. **Click "uploading an existing file"** (it's a blue link)

3. **You'll see a file upload page with two options:**
   - Drag and drop files
   - Click "choose your files"

4. **Upload your files:**
   
   **Option A - Drag and Drop:**
   - Open the folder where you saved your portfolio files
   - Select `index.html` and `Bots_commission_NB.png`
   - Drag them into the upload area on GitHub
   
   **Option B - Click to Choose:**
   - Click "choose your files"
   - Navigate to your portfolio files
   - Select `index.html` and `Bots_commission_NB.png`
   - Click "Open"

5. **You should see both files listed:**
   - `index.html`
   - `Bots_commission_NB.png`
   - (Optionally add `README.md` too)

6. **Scroll down to "Commit changes"**
   - In the text box, you'll see "Add files via upload"
   - You can change this to: "Initial portfolio upload" (optional)
   - Leave "Commit directly to the main branch" selected

7. **Click "Commit changes"** (green button)

---

### Step 4: Enable GitHub Pages

1. **Click on "Settings"** (top navigation bar of your repository)
   - It's the gear icon on the far right

2. **In the left sidebar, click "Pages"**
   - It's under the "Code and automation" section

3. **Under "Source":**
   - Click the dropdown that says "None"
   - Select **"Deploy from a branch"**

4. **Under "Branch":**
   - Click the first dropdown and select **"main"**
   - Click the second dropdown and select **"/ (root)"**
   - Click **"Save"**

5. **You'll see a blue box appear that says:**
   "Your site is ready to be published at https://tktheprogrammer.github.io"

---

### Step 5: Wait for Deployment (1-5 minutes)

1. **Refresh the Settings → Pages page after 1-2 minutes**

2. **The blue box will turn green and say:**
   "Your site is live at https://tktheprogrammer.github.io"

3. **Click the "Visit site" button** or go to:
   `https://tktheprogrammer.github.io`

---

### Step 6: Verify Your Portfolio is Live! 🎉

Visit your URL and you should see:
- Your name and title
- About section
- Skills
- BOTS project with the game cover image
- Contact information with all your links

**Congratulations!** Your portfolio is now live on the internet! 🚀

---

## 🔄 Method 2: Using GitHub Desktop (Good for Frequent Updates)

### Step 1: Download GitHub Desktop

1. Go to [https://desktop.github.com](https://desktop.github.com)
2. Download and install GitHub Desktop for your operating system
3. Open GitHub Desktop and sign in with your GitHub account

### Step 2: Create Repository

1. **Click "File" → "New Repository"**
2. **Fill in the details:**
   - Name: `tktheprogrammer.github.io`
   - Local path: Choose where to save it on your computer
   - Click "Create Repository"

3. **Click "Publish repository"** in the top toolbar
   - Make sure "Keep this code private" is UNCHECKED
   - Click "Publish repository"

### Step 3: Add Your Files

1. **Open the repository folder on your computer**
   - Click "Repository" → "Show in Explorer" (Windows)
   - Or "Repository" → "Show in Finder" (Mac)

2. **Copy your portfolio files into this folder:**
   - `index.html`
   - `Bots_commission_NB.png`
   - `README.md` (optional)

3. **GitHub Desktop will detect the changes automatically**

### Step 4: Commit and Push

1. **In GitHub Desktop, you'll see your files listed**

2. **At the bottom left:**
   - Summary: "Add portfolio files"
   - Description: (optional)

3. **Click "Commit to main"**

4. **Click "Push origin"** in the top toolbar

### Step 5: Enable GitHub Pages

Follow the same steps as Method 1, Step 4 (Settings → Pages → Enable)

---

## 🔄 How to Update Your Portfolio Later

### Using Web Interface:

1. Go to your repository on GitHub
2. Click on the file you want to edit (e.g., `index.html`)
3. Click the pencil icon (✏️) to edit
4. Make your changes
5. Scroll down and click "Commit changes"
6. Wait 1-2 minutes for changes to appear on your live site

### Using GitHub Desktop:

1. Edit your files on your computer
2. Open GitHub Desktop
3. It will show your changes
4. Add a commit message
5. Click "Commit to main"
6. Click "Push origin"
7. Wait 1-2 minutes for changes to go live

---

## 🛠️ Troubleshooting

### "Repository name is already taken"
- Someone already has that username
- Make sure you're using YOUR exact GitHub username
- The repository name must match your username exactly

### "404 - Site not found"
- Wait 5-10 minutes after enabling GitHub Pages
- Make sure repository name is exactly `username.github.io`
- Check that repository is Public, not Private
- Verify GitHub Pages is enabled in Settings → Pages

### "Changes not showing up"
- Clear your browser cache (Ctrl+Shift+R or Cmd+Shift+R)
- Wait 1-5 minutes for GitHub to rebuild your site
- Make sure you pushed/committed your changes

### "Site shows code instead of website"
- Make sure your file is named exactly `index.html` (not Index.html or index.htm)
- Check that the file is in the root directory, not in a subfolder

### "Image not showing"
- Make sure `Bots_commission_NB.png` is uploaded
- Check that the filename in your HTML matches exactly (case-sensitive)
- Verify both files are in the same directory

### "CSS/Styling not working"
- This shouldn't happen as CSS is inside the HTML file
- Try hard refresh: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)

---

## 📱 Testing Your Site

### On Desktop:
1. Open your portfolio URL in different browsers:
   - Chrome
   - Firefox
   - Safari
   - Edge

### On Mobile:
1. Open your portfolio on your phone
2. Check that everything looks good
3. Test all the links work

### Using Browser DevTools:
1. Press F12 in Chrome/Firefox
2. Click the device toolbar icon (📱)
3. Test different screen sizes

---

## 🎯 Quick Checklist

Before you share your portfolio, make sure:

- [ ] All links work (click each one)
- [ ] BOTS image displays correctly
- [ ] Email link opens your email client
- [ ] GitHub link goes to your profile
- [ ] Google Play and GX.games links work
- [ ] LinkedIn link is correct
- [ ] Lexaloffle link works
- [ ] Site looks good on mobile
- [ ] Site looks good on desktop
- [ ] No typos in your text

---

## 🌟 Next Steps

Once your portfolio is live:

1. **Share it!**
   - Add to your LinkedIn profile
   - Put it in your email signature
   - Share on social media
   - Add to your resume

2. **Add more projects**
   - As you create new games, add them to the portfolio
   - Follow the same format as the BOTS project

3. **Keep it updated**
   - Update skills as you learn new technologies
   - Add new achievements
   - Keep contact info current

4. **Get feedback**
   - Ask friends or mentors to review it
   - Make improvements based on feedback

---

## 🆘 Need More Help?

- **GitHub Pages Documentation:** [docs.github.com/pages](https://docs.github.com/pages)
- **GitHub Desktop Help:** [docs.github.com/desktop](https://docs.github.com/desktop)
- **Markdown Guide:** [markdownguide.org](https://markdownguide.org)

---

## 📝 Common Questions

**Q: Can I use a custom domain (like www.myname.com)?**
A: Yes! Buy a domain, then add a CNAME file to your repository and configure DNS settings. See GitHub Pages documentation for details.

**Q: How much does GitHub Pages cost?**
A: It's completely FREE for public repositories!

**Q: Can I have multiple portfolios?**
A: Your main site is `username.github.io`, but you can create additional project sites at `username.github.io/project-name`

**Q: How do I delete my portfolio?**
A: Go to repository Settings → scroll to bottom → "Delete this repository"

**Q: Can I use this for my resume too?**
A: Absolutely! You can create additional HTML pages and link to them from your main portfolio.

**Q: What if I want to make my code private?**
A: GitHub Pages requires public repositories for free hosting. If you need privacy, consider GitHub Pro or other hosting services.

---

**You've got this! 🚀 Your portfolio will be live in just a few minutes!**

If you get stuck at any step, refer back to this guide or the troubleshooting section.

Good luck with your portfolio, Takudzwa! 🎮💻
