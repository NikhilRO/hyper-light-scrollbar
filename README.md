# hyper-light-scrollbar
Made minor changes for personal use. 

### Instructions for use
* Download/Clone this repo and put the unzipped folder in `c/users/{username}/.hyper_plugins/local`
* Edit the .hyper.js file as such:
``` javascript 
plugins:[
    //your plugins
    'hyper-dark-scrollbar'
  ],
localPlugins: [
     //your plugins
    'hyper-light-scrollbar'
  ],
 ```
 * Now, one should be able to make their own changes to `index.js` in `c/users/{username}/.hyper_plugins/local/hyper-light-scrollbar` folder according to their own preference. Restart the Hyper terminal to see your changes.
 
Below are the original instructions for the `hyper-dark-scrollbar`
---------

# hyper-dark-scrollbar
Pretty scrollbar for [hyper](https://github.com/zeit/hyper).

A plugin that stylizes the chunky Windows-ish scrollbar into a more sleek scrollbar.

The scrollbar is designed for [hyperterm-atom-dark](https://github.com/mdo/hyperterm-atom-dark), however, it also looks great on the standard theme, and should look fine on dark themes. Please do create a fork if you want your own custom, personal style, or to fit your theme better.

![screenshot](https://dev.moso.io/hyper/hyper-dark-scrollbar/screenshot.png)

### Changelog
**1.1.0**
- [henrikdahl](https://github.com/henrikdahl) magic - see [e6124e7](https://github.com/moso/hyper-dark-scrollbar/commit/e6124e7640291940acf46883d4022bef900ada60) for changes.

**1.0.0**
- Initial release.

### Install

**Manually**:

1. Open hyper's preferences with `Ctrl+,` (or manually at `~/.hyper.js`) with your editor.
2. Update your list of plugins to include hyper-dark-scrollbar, like so:

        plugins: [
            'hyper-dark-scrollbar'
        ],

3. Reload (`Ctrl+Shift+R`) or restart hyper and voila!

**hpm**:

1. Install using `hpm i hyper-dark-scrollbar`
2. Reload (`Ctrl+Shift+R`) or restart hyper and voila!

### Related

- [hyper-arc-dark-controls](https://github.com/moso/hyper-arc-dark-controls)

### License

MIT
