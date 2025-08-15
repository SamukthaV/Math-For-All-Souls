# Math for All Souls — Starter (HTML only)

Hi, Samuktha! This folder is a ready-to-publish static website with a `pdfs/` directory.

## What's inside
- `index.html` — homepage with your "From the Author" note, contact, and a PDFs section
- `pdfs/` — put all your PDF files here (already includes "Boyd chapter 2.pdf" if provided)
- `assets/` — optional images or other files

## How to view locally
- Double-click `index.html` to open in your web browser.

## How to add more PDFs
1) Copy your PDF into the `pdfs/` folder (e.g., `pdfs/my-paper.pdf`).  
2) Open `index.html` in any text editor.  
3) Find the "Research PDFs" section and add another list item like:
   ```html
   <li><a class="btn" href="pdfs/my-paper.pdf" target="_blank" rel="noopener">Open: my-paper.pdf</a></li>
   ```
4) (Optional) Update the `<iframe class="pdf-embed" src="...">` below to preview your new PDF.

## How to publish on GitHub Pages
1) Create a new GitHub repository (e.g., `math-for-all-souls`).  
2) Upload the files (or use git from the command line).  
3) In your GitHub repo, go to **Settings → Pages**, choose **Deploy from a branch**, and select `main` and **/ (root)**.  
4) Your site will appear at `https://<YOUR_USERNAME>.github.io/math-for-all-souls/`.

## Custom domain (optional)
- Buy a domain and set it in **Settings → Pages → Custom domain**.  
- Add a CNAME record (e.g., `www`) in your DNS pointing to `<YOUR_USERNAME>.github.io`.

— Enjoy sharing the fruit of knowledge!
