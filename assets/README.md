# Birthday App Assets Folder

Place all your custom memory photos and gift photos inside this folder!

## Filename Conventions
To easily link these photos in your code, you can name them like:
- `memory1.jpg`
- `memory2.jpg`
- `memory3.jpg`
- `memory4.jpg`
- `gift1.jpg` to `gift9.jpg`

## Updating the Code
To use these images, open the `index.html` file, scroll down to the `CONFIG` section, and update the `image` paths:
```javascript
const MEMORIES = [
  {
    id: 1,
    image: "assets/memory1.jpg", // Link to your custom local photo here!
    speaker: "Laughs & Celebrations ✨",
    text: "..."
  },
  ...
];
```
