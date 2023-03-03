<div align="center">
    <h1>lubby</h1>
    🐧 Yet another Linux system fetcher written in Bash.
    <br /><br />
    <img alt="Screenshot of lubby in action" src="screenshot.png">
</div>
<br />

This project's goal is to display system information elegantly that's at least faster than stock neofetch on my machine (pictured above).

## Installing

> **Note**
> You'll need `xprop`, `bash 5+` and a [`Nerd Font`](https://www.nerdfonts.com/) to run this script.

Download the `lubby` script to your `$PATH` and mark it as executable (`chmod +x lubby`)

## Customizing

All of the customization is done inside the script itself.

Everything that you may need to change is located at the top of the file, with some more stuff at the bottom `draw()` function.

## Credits

- [grabby v2][url_grabby] *(now deleted)*
    - For being the main thing that inspired me to create my own fetch script.
- [nitch][url_nitch]
    - For serving as a huge inspiration on the aesthetic side of things
- [hyfetch][url_hyfetch]
    - On having some good code that I could always refer to
- [fet.sh][url_fet.sh]
    - Provided a quality guide on how to accomplish some of the tasks I've faced when building my own.

<!-- Inspirations -->
[url_grabby]: https://github.com/sannfdev/grabby
[url_nitch]: https://github.com/dylanaraps/pfetch
[url_hyfetch]: https://github.com/hykilpikonna/hyfetch
[url_fet.sh]: https://github.com/6gk/fet.sh