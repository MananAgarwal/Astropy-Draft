# Astropy-Draft
This repo has the built html drafts of the learn astropy website

To see the website proceed as follows:
```
git clone https://github.com/MananAgarwal/Astropy-Draft.git
cd Astropy-Draft
python -m http.server 8000
```
You can also use 'SimpleHTTPServer' instead of 'http.server'

Now you can open the learn astropy website on 'http://localhost:8000' in any web browser.

Ensure that you have **CORS(Cross-Origin Resource Sharing) disabled** on your web browser for best results.

To disable CORS in Safari
- Safari -> Preferences -> Advanced then tick "Show Develop Menu in menu bar"
- Select "Disable Cross-Origin Restrictions" from the develop menu.

To disable CORS in Chrome
- For OSX, run in terminal: open -a Google\ Chrome --args --disable-web-security --user-data-dir
- For Linux, run in terminal: google-chrome --disable-web-security
