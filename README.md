# Web IPTV Player 📺

A web-based IPTV player that works in any browser, similar to VLC. Watch live TV channels directly from an M3U playlist with an easy-to-use interface.

## 🌟 Features

- 📺 Browse and play IPTV channels from M3U playlists
- 🎯 Channel list sidebar for easy navigation
- 🔍 Search channels by name
- 📱 Responsive design that works on desktop and mobile
- 🎨 Modern dark theme interface
- ⚡ Fast and lightweight - single HTML file

## 🚀 Live Demo

Check out the live player: [https://arummani.github.io/arutv/](https://arummani.github.io/arutv/)

## 📋 Prerequisites

- A GitHub account
- Basic knowledge of Git (optional, can use GitHub web interface)

## 🔧 Setup Instructions

### Option 1: Fork This Repository (Recommended)

This is the easiest way to get your own copy:

1. Click the **Fork** button at the top right of this repository
2. Wait for GitHub to create your fork
3. Go to your forked repository settings:
   - Click on **Settings** tab
   - Scroll down to **Pages** section (left sidebar)
   - Under "Source", select **main** branch
   - Click **Save**
4. Wait 1-2 minutes for deployment
5. Access your player at: `https://YOUR_USERNAME.github.io/arutv/`

### Option 2: Clone and Deploy

If you want to work locally first:

#### Step 1: Clone the Repository

```bash
# Clone this repository
git clone https://github.com/arummani/arutv.git

# Navigate into the directory
cd arutv
```

#### Step 2: Make Changes (Optional)

Edit `index.html` to customize:
- Change the playlist URL (line 30)
- Modify colors and styling
- Add your own features

#### Step 3: Push to Your Own Repository

```bash
# Create a new repository on GitHub first (e.g., YOUR_USERNAME/my-iptv-player)
# Then update the remote URL
git remote set-url origin https://github.com/YOUR_USERNAME/my-iptv-player.git

# Push your changes
git push -u origin main
```

#### Step 4: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under "Source", select **main** branch
4. Click **Save**
5. Your site will be live at: `https://YOUR_USERNAME.github.io/my-iptv-player/`

## 🎬 How to Use

1. Open the player in your browser
2. Browse the channel list on the left sidebar
3. Use the search box to find specific channels
4. Click on any channel name to start playing
5. Use the video controls to play/pause, adjust volume, or go fullscreen

## 🔄 Updating the Playlist

To use a different M3U playlist:

1. Open `index.html` in an editor
2. Find line 30: `const playlistUrl = 'https://iptv-org.github.io/iptv/index.m3u';`
3. Replace the URL with your playlist URL
4. Save and commit the changes

```bash
git add index.html
git commit -m "Update playlist URL"
git push
```

## 📱 Sharing with Friends

Your friends can access your player directly using your GitHub Pages URL:
```
https://YOUR_USERNAME.github.io/arutv/
```

No installation needed - just share the link!

## 🛠️ Technical Details

- **Video Player**: Video.js with HLS support
- **Styling**: Custom CSS with flexbox layout
- **Playlist Format**: Standard M3U/M3U8
- **Hosting**: GitHub Pages (free static hosting)

## 📝 Project Structure

```
arutv/
├── index.html          # Main player file (contains HTML, CSS, and JavaScript)
└── README.md          # This file
```

## 🤝 Contributing

Feel free to:
- Report issues
- Suggest new features
- Submit pull requests
- Fork and customize for your needs

## 📄 License

This project is open source and available for personal and educational use.

## 🙏 Credits

- Video player powered by [Video.js](https://videojs.com/)
- Default playlist from [IPTV.org](https://github.com/iptv-org/iptv)
- Cloudflare CDN for libraries

## 💡 Tips

- For best performance, use channels with stable streams
- Some channels may be geo-restricted
- If a channel doesn't play, try another one
- Use modern browsers (Chrome, Firefox, Safari, Edge) for best compatibility

## 🐛 Troubleshooting

**Channel list is empty:**
- Check that the M3U playlist URL is accessible
- Verify the playlist format is correct
- Check browser console for errors

**Video won't play:**
- Try a different channel
- Check your internet connection
- Some streams may require specific codecs

**GitHub Pages not working:**
- Ensure repository is public
- Wait 2-3 minutes after enabling Pages
- Check Settings → Pages for deployment status

---

Made with ❤️ for IPTV enthusiasts
