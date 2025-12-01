# HabitFlow Legal Documents

This repository contains the legal documents for HabitFlow, including Privacy Policy, Terms and Conditions, and Cookie Policy.

## 📁 File Structure

```
habitflow-legal/
├── index.html                    # Landing page with links to all documents
├── privacy-policy.html          # Privacy Policy
├── terms-and-conditions.html    # Terms and Conditions
├── cookie-policy.html           # Cookie Policy
├── css/
│   └── style.css               # Styling for all pages
├── CNAME                        # Custom domain configuration
└── README.md                    # This file
```

## 🚀 GitHub Pages Setup

### Step 1: Enable GitHub Pages

1. Go to your repository **Settings**
2. Navigate to **Pages** (in the left sidebar)
3. Under **Source**, select:
   - **Branch**: `main` (or `master`)
   - **Folder**: `/ (root)`
4. Click **Save**
5. Your site will be available at: `https://yourusername.github.io/habitflow-legal/`

### Step 2: Custom Domain (Optional)

If you want to use a custom domain like `legal.habitflow.com`:

1. **Purchase a domain** (if you haven't already)
   - Recommended: `legal.habitflow.com` or `docs.habitflow.com`

2. **Add CNAME file** (already included in this repo)
   - The `CNAME` file contains your custom domain
   - Update it with your actual domain name

3. **Configure DNS** with your domain provider:
   - **Type**: `CNAME`
   - **Name**: `legal` (or `docs`)
   - **Value**: `yourusername.github.io`
   - **TTL**: 3600 (or default)

4. **Update GitHub Pages settings**:
   - In repository Settings → Pages
   - Enter your custom domain in the "Custom domain" field
   - GitHub will automatically create/update the CNAME file

5. **Wait for DNS propagation** (can take up to 48 hours, usually much faster)

## 📝 Customization

### Update Contact Information

Edit the following files and replace placeholder text:
- `privacy-policy.html` - Update email and address in section 9
- `terms-and-conditions.html` - Update email and address in section 13
- `cookie-policy.html` - Update email and address in section 9

### Update Company Information

Search and replace:
- `[Your Company Address]` with your actual address
- `[Your Jurisdiction]` in terms-and-conditions.html with your legal jurisdiction

### Styling

Modify `css/style.css` to match your brand colors and design preferences.

## 🔄 Updating Documents

1. Edit the relevant HTML file
2. Update the "Last updated" date (automatically set to current date via JavaScript)
3. Commit and push changes
4. GitHub Pages will automatically rebuild (may take a few minutes)

## 📄 License

These legal documents are templates and should be reviewed by a legal professional before use.

## 🤝 Contributing

If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## 📞 Support

For questions about these legal documents, contact: legal@habitflow.com

