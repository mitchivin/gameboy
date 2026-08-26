# MI Boy Color

Open-source **handheld shell** for MI Boy Color. Device chrome HTML, CSS, and face assets only. No emulator, menus, or ROM library in this repo. The working Game Boy Color emulator is on [MitchIvin XP](https://mitchivin.com/).

Live demo: [builds.doodledev.app/#/miboy](https://builds.doodledev.app/?go=1#/miboy).

The shell was designed in **[DoodleDev](https://doodledev.app)** and sits in the page as normal HTML/CSS. No framework, no runtime deps.

<p align="center">
<img width="1664" height="936" alt="recording-1787750536840-2026-08-26T13-22-53" src="https://github.com/user-attachments/assets/d34f688a-5980-4f5d-9937-9c511a2e2852" alt="MI Boy Color shell demo LCD" />
</p>


## Features

- Inlined DoodleDev Game Boy Color style shell
- Face art for the chassis and A / B buttons
- Physical press visuals on the D-pad and face buttons
- Top-left help menu (DoodleDev + social links)
- Static shell demo page (LCD card, no games)
- Plain static site. Serve the folder from anywhere

<p align="center">
<img width="1664" height="936" alt="recording-1787750536840-2026-08-26T13-22-58" src="https://github.com/user-attachments/assets/00f0e6e6-30f5-412f-b787-ac284e608c1e" alt="MI Boy Color handheld shell" />
</p>

## Run locally

```bash
git clone https://github.com/mitchivin/miboy.git
cd miboy
npx serve .
```

Open whatever URL it prints (usually `http://localhost:3000`). You should see the handheld with a shell demo LCD.

## Layout

```
|-- index.html          # page + inlined device markup
|-- css/
|   `-- gameboy-bundle.css
|-- js/
|   `-- shellPress.js   # press visuals + help menu
|-- public/
|   |-- base.webp
|   |-- button-a.webp
|   |-- button-b.webp
|   |-- keys-standalone.webp
|   `-- meta/
`-- LICENSE
```

## Stack

- Vanilla HTML / CSS
- Shell from [DoodleDev](https://doodledev.app)

## Related

- [DoodleBuilds](https://builds.doodledev.app/?go=1) - shared live demo host
- [MiPod](https://github.com/mitchivin/mipod) - click-wheel shell
- [MitchIvin XP](https://mitchivin.com/) - Windows XP portfolio desktop

## Credits

Built by **[Mitch Ivin](https://mitchivin.com/)**.  
Shell designed in **[DoodleDev](https://doodledev.app)**.

## License

MIT. See [LICENSE](./LICENSE).
