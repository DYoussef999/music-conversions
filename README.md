# Coptic Font Visualizer

A web-based tool for viewing and analyzing Coptic text in various fonts from the HCOC-Coptic-Fonts collection.

## Features

- **Multiple Fonts**: Choose from 49 different Coptic fonts
- **Character Keyboard**: On-screen keyboard with all Coptic Unicode characters (U+2C80 - U+2CF3)
- **Character Inspector**: View each character individually with Unicode code points
- **Responsive Design**: Works on desktop and mobile devices

## Deployment to Vercel

### Prerequisites
- A GitHub account
- Vercel account (free at https://vercel.com)

### Steps

1. **Create a GitHub repository** with the following structure:
   ```
   music-conversions/
   ├── index.html
   ├── hazzat1_10a.ttf
   ├── vercel.json
   └── HCOC-Coptic-Fonts/
       └── (all font files)
   ```

2. **Connect to Vercel**:
   - Go to https://vercel.com/new
   - Select "Import Git Repository"
   - Connect your GitHub repository
   - Click "Deploy"

3. **That's it!** Your site will be live at a Vercel URL

## Local Testing

Before deploying, test locally:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server
```

Then open `http://localhost:8000` in your browser.

## File Structure

- `index.html` - Main application file
- `hazzat-visualizer.html` - Alternative version (same content as index.html)
- `hazzat1_10a.ttf` - Hazzat font file
- `HCOC-Coptic-Fonts/` - Directory containing all 49 Coptic fonts
- `vercel.json` - Vercel configuration

## Fonts Included

Abraham, Antoni10, Antoni12, Antonio0-7, AntonioA, Athanasius, Avva Shenouda, Avva ShenoudaNormal, Bishop Tadros, Bishoy, Cog, CogB, Copt, Coptic, Coptic1, Coptic II, CopticNew, Courier variants, CS fonts, FaithSym, Georges, Koptos, Kyri, Kyrillos, Marcos, Marina, Mark, Mena, NewAth, Nopher, Pishoi, Pope Shenouda, SpacMim, Hazzat

## License

This project uses fonts from the HCOC-Coptic-Fonts collection.
