### **Xbox Linux:** _run Linux on your xbox_

### About

 - Xbox linux is a project to get linux running on your Xbox using the Microsoft Edge browser.
 - It is based on the browser-linux project.

   - See https://github.com/Darin755/browser-linux

 - It uses the following libraries

   - v86 [link](https://github.com/copy/v86), [LICENSE](https://github.com/Darin755/browser-linux/raw/master/lib/v86/LICENSE)

   - localforge [link](https://github.com/localForage/localForage), [LICENSE](https://github.com/Darin755/browser-linux/raw/master/lib/localForage/LICENSE)

   - xtermjs [link](https://github.com/xtermjs/xterm.js), [LICENSE](https://github.com/Darin755/browser-linux/raw/master/lib/xtermjs/LICENSE)

## How to save

 - it can take anywhere from 15-70 sec to boot depending on hardware

 - open the toolbox (the icon at the bottom) and press save now and/or enable autosave
 - See [saving.md](docs/saving.md)
## How to run
- First open the Microsoft edge browser.
- Next open this GitHub repo and open the GitHub Pages deployment
- Append "?mem=65" to the end of the url
- Once the Boot loader appears choose the third option (The Gui does not work yet)
- Scroll down and click on the setting icpn, once done click on the fullscreen button.
- Wait (This will probably take some time)
- Enjoy Tiny Core Linux on you Xbox

## How to embed

 - It is actually pretty simple to do.
 - See [Embed.md](docs/embed.md)
 - See the [example](https://darin755.github.io/browser-linux/embed.html)
 
## Documentation
 - How to save: [saving.md](docs/saving.md)
 - How to use the toolbox: [toolbox.md](docs/toolbox.md)
 - url parameters: [parameters.md](docs/parameters.md)
 - internet: [internet.md](docs/internet.md)
 - updates: [updates.md](docs/updates.md)
 - How to embed: [embed.md](docs/embed.md)
 - Static-get: [Static-get.md](docs/static-get.md)
 - Shared fs [9pfs.md](docs/9pfs.md)

## Limitations
 - It is a bit slow
   - It is fine for running simple programs but as soon as you try to run anything that requires cpu it will slow down immensely because the cpu is emulated by v86

## License

 - Browser linux itself is under GPLv3 License
 - see LICENSE
