# 🎷 Jazz in Code: A Mondrian-Inspired p5.js Animation

## 🖼️ Project Overview

This project is inspired by Piet Mondrian’s *Broadway Boogie Woogie* (1942–43), a painting in which Mondrian visualized his emotional and rhythmic response to New York’s jazz culture using abstract color and form.

As part of a group generative art exploration using **p5.js**, I created an individual variation focusing on the **trumpet** and the **piano**. These two instruments form the visual and conceptual centerpiece of my work. I extended the Mondrian-style color palette and geometric abstraction to express my own perception of jazz music, blending visual rhythm with musical dynamics.

---

## 🕹️ Interaction Instructions

To begin the experience, simply **click anywhere on the webpage** to start the jazz audio loop. No further interaction is needed — the animation progresses automatically in sync with the rhythm of the music.

---

## 🎛️ Animation Method

- **Animation Driver**: Audio-based (beat and amplitude)
- **Effect**: Visual elements (such as shapes, circles, and decorative notes) grow and shrink dynamically in response to the music’s low-frequency energy.
- **Technique Used**: `p5.sound.FFT().getEnergy()` to extract low-frequency amplitudes and map them to size and scale variations.

---

## 🎨 Visual Inspiration

The core layout and aesthetic are derived from **Mondrian’s compositional philosophy** — modular color blocks and musical abstraction. I reinterpreted the concept using jazz-themed imagery:

- A **trumpet** placed at the center, “blowing out” animated notes
- A **hand playing piano** in the lower left
- Rhythmic black, red, yellow, and blue shapes forming dynamic flows

> _You can see my visual sketch and draft here:_  
> 📎 ![21749533535_ pic_hd](https://github.com/user-attachments/assets/2076bdb5-6fb2-4be4-aed8-9e4cedd008da)

---

## 🧠 Technical Notes

This project uses `p5.js` and the `p5.sound` library to create an audio-reactive visual composition. The core functionality is driven by **real-time audio frequency analysis**, allowing the visual elements to respond dynamically to the rhythm and energy of the jazz soundtrack.

### 🎨 Visual Techniques

- Layered shapes are drawn using `beginShape()` and `vertex()` to emulate the painting’s abstract curves and structural flow.

### 🔊 Audio Analysis

- The animation is powered by `p5.FFT`, which performs a Fast Fourier Transform on the playing audio to extract frequency energy.

---

## 💭 Reflection

I invested significant time into detailed **visual rendering and layout precision**, which limited my time for implementing deeper interaction mechanisms. In the future, I plan to integrate:

- Real-time mouse or keyboard triggers  
- Responsive color schemes  
- Dynamic instrument motion  

These improvements will make the animation more interactive, immersive, and expressive of the jazz energy I aimed to portray.

---

## 📚 References

- [p5.js sound library documentation](https://p5js.org/reference/#/libraries/p5.sound)
- [p5.FFT → getEnergy()](https://p5js.org/reference/#/p5.FFT/getEnergy)
- *Broadway Boogie Woogie*, Piet Mondrian (1942–43)
