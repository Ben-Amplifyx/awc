# Image Setup Guide

## Your Cat Images

I've updated the code to use your three cat images. Here's how to add them to your project:

### Image Files Required

You have these images in `/Users/bjcro/Downloads/AWCats/`:
- **home.jpeg** - Used on the homepage hero section
- **facts.jpeg** - Used on the Fun Facts page
- **breeds.jpeg** - Used on the Cat Breeds/Blog page

### How to Copy Images to Your Project

**Option 1: Using Terminal**

Find your project location first:
```bash
# Find your awc project
find ~ -name "awc" -type d 2>/dev/null | grep -v node_modules
```

Then copy the images (replace `YOUR_PROJECT_PATH` with the actual path):
```bash
# Create the directory
mkdir -p YOUR_PROJECT_PATH/public/assets/images/cats

# Copy all images
cp /Users/bjcro/Downloads/AWCats/*.jpeg YOUR_PROJECT_PATH/public/assets/images/cats/

# Verify
ls -la YOUR_PROJECT_PATH/public/assets/images/cats/
```

**Option 2: Using Finder (Mac)**

1. Open Finder
2. Navigate to your `awc` project folder
3. Go to: `public/assets/images/`
4. Create a new folder called `cats`
5. Copy `home.jpeg`, `facts.jpeg`, and `breeds.jpeg` from your Downloads/AWCats folder
6. Paste them into `public/assets/images/cats/`

**Option 3: Using VS Code (or your code editor)**

1. Open your `awc` project in VS Code
2. In the file explorer, navigate to `public/assets/images/`
3. Right-click and create a new folder called `cats`
4. Drag and drop the three .jpeg files from your Downloads/AWCats folder into this cats folder

## Where Each Image Appears

- **home.jpeg** → Homepage hero (first thing visitors see)
- **facts.jpeg** → Fun Facts page (/cats/fun-facts)
- **breeds.jpeg** → Cat Breeds page (/blog)

## Testing

Once you copy the images:
1. Run `npm run dev` in your project
2. Open `http://localhost:4321`
3. You should see your cat images on the homepage, fun facts page, and breeds page!

## Need Help?

If the images don't show up:
1. Check that the filenames are exactly: `home.jpeg`, `facts.jpeg`, `breeds.jpeg`
2. Check that they're in: `public/assets/images/cats/`
3. Restart your dev server: `npm run dev`
