# Digital Ambassadors — AI Creator Lab

Responsive static website for the first tutorial. No build tools or framework are needed.

## Files
- `index.html` — content and YouTube embeds
- `styles.css` — responsive design
- `README.md` — deployment notes

## Publish using GitHub + Render
1. Create a new GitHub repository named `digital-ambassadors-ai-creator-lab`.
2. Upload these three files to the repository root.
3. In Render, select **New → Static Site** and connect the repository.
4. Set branch to `main` (or your default branch), leave **Build command** blank, and set **Publish directory** to `.`.
5. Create the site. Render will provide a public `onrender.com` address.
6. With auto-deploy enabled, future commits to the connected branch will redeploy the site.

The video files remain on YouTube; this site embeds them, so it does not need to store or serve the video files. Check that each video is Public or Unlisted and embedding is allowed.
