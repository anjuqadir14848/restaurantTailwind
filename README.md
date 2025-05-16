✅ How to Deploy a Website on Hostinger
🔹 Step 1: Log in to Hostinger
Go to https://www.hostinger.com

Log in to your Hostinger account

Go to “Websites” → Select your site → Click "Manage"

🔹 Step 2: Upload Your Website Files
You have two main options:

✅ Option A: Use File Manager (Easy for Static Sites)
Go to “Files” → “File Manager”

Navigate to public_html directory

Click Upload and select your website files (e.g., index.html, CSS, JS files)

If uploading a ZIP, unzip it after upload (right-click → Extract)

✅ Option B: Use FTP (e.g., FileZilla)
Go to “FTP Accounts” in Hostinger’s dashboard to find your FTP credentials

Connect via FileZilla

Host: ftp.yourdomain.com or your server IP

Username/password: from FTP settings

Upload files to the /public_html/ folder

🔹 Step 3: Point Your Domain (if not already done)
If you bought the domain on Hostinger, it’s usually auto-connected

If external:

Go to your domain registrar (e.g., GoDaddy)

Set the domain’s nameservers to Hostinger’s:

ns1.dns-parking.com

ns2.dns-parking.com

🔹 Step 4: Check and Set Up Index File
Make sure the homepage file is named index.html or index.php

Hostinger will load this by default when someone visits your site

🔹 Step 5: Set Up Database (If Needed)
For dynamic sites (PHP, WordPress, etc.):

Go to Databases → MySQL Databases

Create a database, username, and password

Use those credentials in your app config (e.g., config.php)

🔹 Step 6: Enable HTTPS (Free SSL)
Go to Website → SSL

Activate SSL for your domain

Hostinger provides free SSL (Let's Encrypt)

It may take a few minutes to propagate

🔹 Step 7: Test Your Website
Open https://yourdomain.com

Make sure everything loads correctly

🚨 Troubleshooting Tips
500 Internal Server Error: Check .htaccess file or PHP version

404 Not Found: Ensure files are inside public_html

No styles or broken images: Check paths in your HTML/CSS
