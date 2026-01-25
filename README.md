# 📸 ExactKB – Compress Image to Exact KB Size
ExactKB is a lightweight, browser-based image compressor that allows users to reduce images to an exact target size (in KB) — instantly and securely, without uploading files to any server.
## 🔒 100% client-side · ⚡ Fast · 📦 Exact size control
# 🚀 Features
- ✅ Compress images to an exact KB size
- ✅ Works fully offline in the browser
- ✅ No image upload — privacy friendly
- ✅ Supports JPG & PNG (PNG converted to JPG)
- ✅ Dark mode with persistent theme
- ✅ Automatic download after compression
- ✅ Clean and responsive UI
<img width="1919" height="903" alt="image" src="https://github.com/user-attachments/assets/94911501-fe17-445a-8b5a-e5e38dbd1318" />

# 🛠️ Tech Stack
- HTML5
- CSS3
- Vanilla JavaScript
- Canvas API
- Binary Search Algorithm for precise compression
# 📂 Project Structure
- ExactKB/
- │
- ├── index.html   # Complete application (HTML + CSS + JS)
- └── README.md    # Project documentation
# ⚙️ How It Works
1. User uploads an image
2. User enters the target size (in KB)
3. The image is drawn on a canvas
4. Binary search is used to adjust JPEG quality
5. Compression continues until the size is close to the target
6. The compressed image is automatically downloaded
# 🧠 Algorithm Used
- Binary Search on JPEG Quality
- Quality range: 0.05 → 0.95
- Stops when precision reaches ±0.01
- Ensures fast and accurate results
# 🧪 Example Usage
1. Open index.html in a browser
2. Upload an image
3. Enter target size (e.g. 150)
4. Click Compress & Download
5. Image downloads automatically 🎉
<img width="1919" height="903" alt="image" src="https://github.com/user-attachments/assets/4107fc04-6217-4a0c-b4e0-c4887acef91b" />

# 🌙 Dark Mode
- Toggle using the moon button 🌙
- Theme preference is saved using localStorage
# ⚠️ Limitations
1. Best results with JPG images
2. PNG images are converted to JPG
3. Extremely small target sizes may reduce image quality
# 👤 Author
Arghyadip Ghosh
© 2026 — All rights reserved
