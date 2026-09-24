# Das Rad

A spinning wheel with a Bauhaus look: primary colours, simple geometric shapes, a strict grid and the Jost typeface.

Open `index.html` in a browser. It has no build step and no dependencies.

- Add or remove choices (2–24) in the panel.
- Press **Spin**, click the centre hub, or press **Space**.
- Each peg that passes the pointer makes a click, and the pointer flicks back with it. A spin starts with a whoosh and ends with a chime. The sounds are made in the browser with the Web Audio API, so there are no audio files. Use the **Sound on/off** button in the result box to mute them.
- Your choices, odds, sound setting and the last 8 results are saved in `localStorage`.

## The secret

Every slice looks the same size, but a hidden menu can change how likely each choice is.

<details>
<summary>How to open it</summary>

Press and **hold the full stop** at the end of *"Form follows function."* in the footer for 1.5 seconds. A normal click does nothing.

The **Werkstatt** (workshop) menu opens. Its sliders set a weight for each choice and show the resulting percentage. **Equalize** resets every choice to equal odds. The wheel still stops at a natural-looking spot inside the chosen slice.
</details>
