# 🌟 Private Brawl Stars Server - Website Template

A **simple HTML template** to help you create your own website for a private Brawl Stars server.  
No advanced coding needed — just customize texts, images, colors, and upload it.

## 📦 What’s inside

- Modern mobile-friendly design  
- Image slider (gallery)  
- Download APK button  
- Server rules section  
- Contact section  
- Social links (Discord & Telegram)  
- Easy color customization

---

## ✏️ How to customize

All customization is inside the `index.html` file.  
You can edit it with any code editor (e.g., VS Code, Sublime, Atom) or even on your phone with [Acode](https://play.google.com/store/apps/details?id=com.foxdebug.acodefree).

### 📝 Change texts

In the HTML file, look for:

- Website title:  
  ```html
  <h1>Private Brawl Stars Server</h1>

Descriptions:

<p>Simple template to create your private server website...</p>

Server rules: inside <li> tags

Footer:

<footer>Project created by NebuX - Private Brawl Stars Server</footer>


Edit these texts to match your project.


---

🖼️ Add your own images

This template uses local images, so your images must be placed in the same folder as index.html (or in a folder like /images if you adjust the paths).

Example in the HTML:

<img src="image1.jpg" alt="Image 1">
<img src="image2.jpg" alt="Image 2">
<img src="image3.jpg" alt="Image 3">

Replace:

image1.jpg, image2.jpg, image3.jpg with your actual image filenames.

Make sure your images are in the same directory as index.html or adjust the path accordingly (e.g., images/image1.jpg).


Recommended size: similar aspect ratio, e.g., 1920x1080 or 1280x720.


---

📥 Add your APK

Replace the APK download link in this section:

<a href="yourfile.apk" target="_blank">Download APK</a>

Put your APK file (yourfile.apk) in the same folder as index.html
Or use an external link (e.g., MediaFire, Google Drive).


---

🔗 Change social & contact links

Replace these placeholders in the HTML:

Section	Placeholder	Replace with

Discord	https://discord.gg/your-server	Your Discord invite link
Telegram	https://t.me/your-telegram	Your Telegram group/channel link
Contact	contact@yourserver.com	Your contact email address



---

🎨 Change colors

At the top of the HTML file, you’ll find CSS variables:

:root {
  --bg-color: #121212;
  --text-color: #e1e1e6;
  --primary-color: #7f5af0;
  --secondary-color: #b86bff;
}

Just change the hex codes to your preferred colors.

Example:

--primary-color: #FF5722;
--secondary-color: #FFC107;

💡 You can find color codes on colorhunt.co or coolors.co.


---

🧪 How to test the website locally (before hosting)

You don’t need to publish the website right away. You can test it locally on your device or computer.

✅ Testing on Android with Acode

1. Download and install Acode from Google Play.


2. Open Acode.


3. Tap the menu icon (≡) → Open folder → Navigate to the folder where your website files are (index.html and images).


4. Tap index.html to open it.


5. Tap the Play ▶️ button (top-right corner) to open the webpage in Acode’s built-in browser.


6. Browse your site and check images, texts, links, etc.


7. If you make any changes, save and reload the page in the browser.




---

📦 How to prepare your project folder and create a ZIP using ZArchiver (Android)

To share or upload your website, you need to create a ZIP file with your index.html, images, and APK.

Step-by-step:

1. Make sure all your website files are together in one folder on your device (for example, MyServerWebsite):

index.html

Images (image1.jpg, image2.jpg, image3.jpg, etc.)

APK file (yourfile.apk) if you want to include it



2. If your images have different names, rename them to match the references in the HTML file:

Open ZArchiver.

Navigate to your folder (MyServerWebsite).

Long press on an image file → choose Rename.

Enter the exact name used in the HTML (image1.jpg, etc.) and confirm.



3. After confirming all filenames are correct, go back to the folder list in ZArchiver.


4. Tap and hold the folder name (MyServerWebsite) to select it.


5. Tap the three dots menu icon and select Compress → ZIP.


6. Name the ZIP file (e.g., MyServerWebsite.zip).


7. Choose the destination folder and tap OK.


8. Your ZIP file is ready to share or upload.




---

💡 Tips

Keep filenames simple and lowercase to avoid issues (image1.jpg instead of Image1.JPG).

Double-check the image names and paths in your index.html match exactly.

To view the website locally on a PC, just open the index.html file in any browser.



---

☁️ How to host your website

✅ Neocities (free & simple)

1. Sign up at https://neocities.org


2. Create a new site → Upload your index.html and images/APK


3. Your site will be online at:
https://yourname.neocities.org



When you update, just upload the new files.


---

✅ GitHub Pages (also free)

1. Create a GitHub account and new repository


2. Upload index.html, images and APK to the repo


3. Go to Settings → Pages


4. Choose branch: main → folder: /root


5. Click Save → your website will be live at:
https://yourusername.github.io/repositoryname




---

✅ Credits

Original template & design: NebuX

Game assets © Supercell (this is a fan project, not official)



---

> ⚠️ Important:
This is only a website template for private servers and fan projects.
It does not include the actual game or any private server software.
