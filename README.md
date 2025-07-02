from docx import Document
from datetime import datetime

# Create a README.md styled GitHub profile as Word document first
doc = Document()
doc.add_heading('GitHub Profile - Sunmeet Kaur', 0)

doc.add_paragraph("🧠 **Welcome to my GitHub Profile!**")

# Add animated matrix banner suggestion
doc.add_heading('🎥 Animated Banner:', level=1)
doc.add_paragraph("""
You can use an animated GIF as a banner just like the matrix effect.
1. Create a GIF (like matrix rain) or download one from Giphy.
2. Upload it to your repository or use a public image host.
3. Embed it at the top of your README.md like this:

```md
<img src="https://link-to-your-gif.gif" width="100%" />
