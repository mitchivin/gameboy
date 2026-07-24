# MI Boy Color

Open-source **handheld shell** for MI Boy Color. Device chrome HTML, CSS, and face assets only. No emulator, menus, or ROM library in this repo.

Live demo: [builds.doodledev.app/#/miboy](https://builds.doodledev.app/?go=1#/miboy).

The shell was designed in **[DoodleDev](https://doodledev.app)** and sits in the page as normal HTML/CSS. No framework, no runtime deps.

<p align="center">
  <img src="https://github.com/user-attachments/assets/3d5f50f4-df81-4053-91f8-c0950d3c4fdf" alt="MI Boy Color handheld shell" />
</p>

## Features

- Inlined DoodleDev Game Boy Color style shell
- Face art for the chassis and A / B buttons
- Physical press visuals on the D-pad and face buttons
- Top-left help menu (DoodleDev + social links)
- Static shell demo page (LCD card, no games)
- Plain static site. Serve the folder from anywhere

<p align="center">
  <img src="https://github.com/user-attachments/assets/19578b7e-8336-4505-9b39-42e93df11548" alt="MI Boy Color shell demo LCD" />
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
Emulation by **[Grant Galitz / GameBoy-Online](https://github.com/taisel/GameBoy-Online)**.

## License

MIT. See [LICENSE](./LICENSE).
