# Aroohi and the Little Birthday Universe ✨

A self-contained birthday story game with **ten chapters**: collect stars, match keepsakes, decorate a cake, choose flowers, open postcards, pop balloons, play a color rhythm, choose a story route, answer a silly quiz, and connect a constellation. The finale reveals a long birthday letter and lets Aroohi save the **entire letter** as a PNG.

## Try it

Open `index.html` in a browser. It works without an internet connection. Tap **Sound off** if you want little game sounds. Progress is saved in that browser.

## Make it personal

1. Open `index.html?edit=1` in a browser. If opening a local file, append `?edit=1` to the file URL in the address bar. For example: `file:///.../index.html?edit=1`.
2. Click **Edit story**. You can change the opening line, three memory cards, one message in each of the ten chapters, four postcards, and the entire final letter.
3. Click **Save & download game**. This downloads a complete, personalized `index.html` file. Those words are baked into the file and will appear for everyone who visits the published page.
4. Replace the original `index.html` with this downloaded one before uploading to GitHub.

You can also edit the `birthday-config` JSON block near the top of `index.html` in a text editor. This version already includes Aahil's car-window apology flower, the pre-event hair rescue, Aroohi's music taste, the AI pigeon meme, and their inside-joke nickname. Review the letter and notes before publishing if you want to adjust any wording.

## Put it on GitHub Pages

1. Create a new GitHub repository, for example `aroohi-birthday`.
2. Upload the personalized `index.html` to the **root** of the repository and commit it. You may include this README.
3. In the repository, open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, choose your main branch and `/ (root)`, then save.
4. Once GitHub Pages finishes publishing, share the URL shown in Pages settings. It normally resembles `https://YOUR-USERNAME.github.io/aroohi-birthday/`.

GitHub Pages sites are publicly accessible by default. Keep private memories or contact details out of the story if you do not want them visible to anyone with the link.

## Technical notes

Plain HTML, CSS, and JavaScript. No dependencies, tracking, cookies, API keys, image downloads, or build step. The sound is synthesized in the browser and starts only after it is turned on. Animation respects reduced-motion settings. Game progress stays in local browser storage; it is not sent anywhere.
