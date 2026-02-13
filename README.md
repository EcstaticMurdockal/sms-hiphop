# SMS Hip-hop Club Website

Welcome to the SMS Hip-hop Club website! This website showcases the evolution, merchandise, performances, original songs, and memories of the Shenzhen Middle School Hip-hop Club.

## Features

- **Hero Section**: Eye-catching introduction with the club name and tagline
- **Timeline**: Key events and milestones in the club's evolution
- **Merchandise Section**: Display of club merchandise (t-shirts, necklaces, hoodies, caps)
- **Posters Gallery**: Performance posters with hover effects
- **Original Songs**: Display of original songs with lyrics and audio players
- **Photo Gallery**: Best memories with interactive hover effects
- **Links Section**: Links to social media and other platforms
- **Responsive Design**: Works on desktop, tablet, and mobile devices

## Color Theme

The website uses your specified colors:
- Primary: `#ede1a9` (warm beige)
- Secondary: `#7ebea5` (soft green)

## Files Structure

```
sms-hiphop/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript for interactivity
├── images/             # Folder for images
│   ├── tshirt-placeholder.jpg
│   ├── necklace-placeholder.jpg
│   ├── hoodie-placeholder.jpg
│   ├── cap-placeholder.jpg
│   ├── poster1-placeholder.jpg
│   ├── poster2-placeholder.jpg
│   ├── poster3-placeholder.jpg
│   ├── poster4-placeholder.jpg
│   ├── gallery1-placeholder.jpg
│   ├── gallery2-placeholder.jpg
│   ├── gallery3-placeholder.jpg
│   ├── gallery4-placeholder.jpg
│   ├── gallery5-placeholder.jpg
│   ├── gallery6-placeholder.jpg
│   ├── gallery7-placeholder.jpg
│   └── gallery8-placeholder.jpg
└── audio/              # Folder for audio files
    ├── rise-up.mp3
    ├── shenzhen-vibes.mp3
    └── unstoppable.mp3
```

## How to Add Your Content

### Images

Replace the placeholder images in the `images/` folder with your actual images:

1. **Merchandise Images**:
   - `tshirt-placeholder.jpg` - Your t-shirt photo
   - `necklace-placeholder.jpg` - Your necklace photo
   - `hoodie-placeholder.jpg` - Your hoodie photo
   - `cap-placeholder.jpg` - Your cap photo

2. **Poster Images**:
   - `poster1-placeholder.jpg` - Spring Festival 2023 poster
   - `poster2-placeholder.jpg` - Battle Night 2023 poster
   - `poster3-placeholder.jpg` - Winter Showcase 2024 poster
   - `poster4-placeholder.jpg` - New Year Celebration poster

3. **Gallery Images**:
   - `gallery1-placeholder.jpg` to `gallery8-placeholder.jpg` - Your best memories photos

### Audio Files

Add your original songs to the `audio/` folder:

1. `rise-up.mp3` - Your first original song
2. `shenzhen-vibes.mp3` - Your second original song
3. `unstoppable.mp3` - Your third original song

### Updating Lyrics

To update the lyrics in [index.html](index.html#L238), find the song cards in the "Our Original Songs" section and replace the placeholder lyrics with your actual song lyrics.

### Updating Timeline Events

To update the timeline in [index.html](index.html#L89), find the timeline items in the "Our Evolution" section and modify the years, titles, and descriptions to match your club's actual history.

### Updating Links

To update the social media links in [index.html](index.html#L415), find the "Connect With Us" section and replace the `href="#"` attributes with your actual social media URLs.

## How to Use

1. **Online Access**
   - Visit the live website at: [https://ecstaticmurdockal.github.io/sms-hiphop/](https://ecstaticmurdockal.github.io/sms-hiphop/)

2. **Local Development**
   - Open [index.html](index.html) in a web browser to view the website
   - Add your actual images to the `images/` folder
   - Add your audio files to the `audio/` folder
   - Update the content in [index.html](index.html) with your actual information
   - Refresh the browser to see your changes

## Customization

### Changing Colors

To modify the color scheme, update the CSS variables in [styles.css](styles.css#L9):

```css
:root {
    --primary-color: #ede1a9;
    --secondary-color: #7ebea5;
    --dark-color: #2c2c2c;
    --light-color: #f8f8f8;
    --accent-color: #ff6b6b;
    --text-color: #333;
    --text-light: #666;
}
```

### Adding More Songs

To add more songs, copy a song card block in [index.html](index.html) and paste it after the existing song cards. Remember to:
- Update the song title
- Update the audio source file
- Update the lyrics

### Adding More Gallery Images

To add more gallery images, add more `.gallery-item` divs in the gallery section of [index.html](index.html).

## Browser Compatibility

The website works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge
- Mobile browsers

## Features Implemented

- Smooth scrolling navigation
- Responsive hamburger menu for mobile
- Scroll animations for timeline, gallery, and merchandise
- Hover effects on cards and images
- Audio player for songs
- Lyrics display with scrollable text
- Gradient backgrounds
- Box shadows and transitions

## Tips

1. Use high-quality images for best results
2. Keep audio files in MP3 format for best compatibility
3. Test the website on different screen sizes
4. Optimize images for web (compress them to reduce file size)
5. Make sure all links work before publishing

Enjoy showcasing your SMS Hip-hop Club!