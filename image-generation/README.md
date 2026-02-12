# Image Generation Toolkit

Generate images using Google's Gemini 3 Pro (Nano Banana Pro) directly from Cursor.

## Setup

1. **Get your API key:**
   - Go to https://aistudio.google.com/
   - Click "Get API Key" → "Create API key"
   - Copy your key (starts with "AIza...")

2. **Set up billing:**
   - In Google AI Studio: Settings → Plan information → "Set up Billing"
   - Costs ~$0.10 per image (this entire toolkit will cost less than $5)

3. **Create `.env` file:**
   ```
   GEMINI_API_KEY=your_actual_key_here
   ```

4. **Install dependencies:**
   ```bash
   pip install google-genai pillow python-dotenv
   ```

## Quick Start

### Generate an Image

```python
from image_gen import generate

output_path = generate(
    prompt="A professional product mockup for a mobile app",
    aspect_ratio="16:9",
    resolution="1K"
)
```

### Use a Style from Your Library

```python
from get_style import get_style
from image_gen import generate

# Get style #4
style = get_style(4)
prompt = f"{style['prompt']}\n\nYour subject: [describe what you want]"

output_path = generate(prompt=prompt, aspect_ratio="16:9")
```

### Extract Style from Any Image

```python
from style_extract import extract_style

# Extract style from any image
style_description = extract_style("path/to/image.jpg")
print(style_description)

# Now use it to generate new images
from image_gen import generate
prompt = f"{style_description}\n\nYour new subject: [describe]"
output_path = generate(prompt=prompt)
```

## Style Library

Open `style-library.html` in your browser to browse all your saved styles.

**To add a new style:**
1. Generate an image you like
2. Tell Cursor: "Add this style to my library"
3. Refresh the HTML file to see it

**To use a style:**
- Just say: "Use style #4 to generate [your subject]"
- Or reference it by name: "Use the Hand-Drawn Sketch Journey Map style"

## Parameters

- **aspect_ratio:** `"1:1"`, `"16:9"`, `"9:16"`, `"3:4"`, `"4:5"`, `"3:2"`
- **resolution:** `"1K"` (fast, ~20s), `"2K"` (slower, ~30s), `"4K"` (slowest, ~45s, costs more)
- **reference_images:** List of image paths to use as style/subject references

## Golden Rules of Prompting

1. **Edit, don't re-roll** — If 80% correct, ask for specific changes
2. **Use natural language** — Write like you're talking to a designer
3. **Be specific and descriptive** — Gemini can handle lots of detail
4. **Provide context** — Tell the "why" or "for whom"

## Workflow Tips

- **Generate variants:** Create 2-3 versions, pick your favorite, then iterate
- **Use reference images:** Single image for style, multiple images for better subject accuracy
- **Build your library:** Save prompts you love, extract styles from images you admire
- **Iterate:** Continue sessions to refine images step-by-step

## Files

- `image_gen.py` — Main generation module (handles API, sessions, saving)
- `style_extract.py` — Extract style descriptions from any image
- `get_style.py` — Retrieve prompts from your style library
- `style-library.html` — Browse your saved styles (open in browser)
- `thumbnails/` — Preview images for your styles
- `outputs/` — Generated images are saved here

## Example Use Cases

- **PM Mockups:** UI concepts, wireframes, landing pages
- **Personas:** User portraits, lifestyle shots, context imagery
- **Diagrams:** Journey maps, flowcharts, architecture diagrams
- **Presentations:** Slide decks, infographics, visualizations
- **Marketing:** Social posts, ads, announcements

---

**Note:** This toolkit requires a Gemini API key with billing enabled. See setup instructions above.
