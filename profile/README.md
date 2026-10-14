<p align="center">
  <img src="https://raw.githubusercontent.com/Sellest-AI/.github/main/profile/assets/sellest-banner.webp" alt="Sellest" width="100%" />
</p>

<p align="center">
  <strong>We build AI products that start from what you already have: your product, your closet, your kitchen.</strong>
</p>

<p align="center">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" />
  <img alt="Expo" src="https://img.shields.io/badge/Expo-React%20Native-000020?logo=expo&logoColor=white" />
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white" />
  <img alt="Convex" src="https://img.shields.io/badge/Convex-backend-EE342F" />
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
  <img alt="RunPod" src="https://img.shields.io/badge/RunPod-GPU%20serverless-673AB7" />
</p>

---

## 🚀 Products

### 🛍️ Sellest · [sellest.io](https://sellest.io)

An AI studio for product visuals. Upload a photo of your product and get studio-quality product
shots, new backgrounds and short marketing videos, without a photoshoot. An AI assistant ties the
tools together, so you can ask for what you want instead of clicking through them.

- 📸 **Product photos:** generate scenes around your real product from a prompt or a reference image
- ✂️ **Editing:** background removal, magic eraser, upscaling up to 4K
- 🎬 **Video:** turn a generated image into a short animated clip
- 💬 **Assistant:** one chat that drives every tool

<p align="center">
  <a href="https://vimeo.com/1133867151">
    <img src="https://raw.githubusercontent.com/Sellest-AI/.github/main/profile/assets/sellest-agent-video.webp" alt="Watch: Introducing the Sellest agent" width="85%" />
  </a>
  <br />
  <sub>▶️ <a href="https://vimeo.com/1133867151">Watch the Sellest agent in action</a></sub>
</p>

<sub>🔒 Source is private.</sub>

<br />

<table>
  <tr>
    <td width="50%" valign="top" align="center">
      <img src="https://raw.githubusercontent.com/Sellest-AI/.github/main/profile/assets/cooture-logo.webp" alt="Cooture" width="120" />
      <h3>👗 Cooture</h3>
      <p>Your own closet, in AI. Snap your clothes and they are cut out and tagged for you, build
      outfits from them, then see yourself wearing them in AI photoshoots.</p>
      <p>
        <a href="https://cooture.app">cooture.app</a> ·
        <a href="https://github.com/Sellest-AI/Cooture">Sellest-AI/Cooture</a>
      </p>
      <sub>iOS · Android · Web</sub>
    </td>
    <td width="50%" valign="top" align="center">
      <img src="https://raw.githubusercontent.com/Sellest-AI/.github/main/profile/assets/cuisko-logo.webp" alt="Cuisko" width="120" />
      <h3>🦊 Cuisko</h3>
      <p>The meal planner that starts with the food you already own. Plan a week from your kitchen,
      shop only for what is missing, waste nothing.</p>
      <p>
        <a href="https://cuisko.app">cuisko.app</a> ·
        <a href="https://github.com/Sellest-AI/Cuisko-App">App</a> ·
        <a href="https://github.com/Sellest-AI/cuisko-website">Website</a>
      </p>
      <sub>iOS · Android · Web</sub>
    </td>
  </tr>
</table>

## ⚙️ Infrastructure

The GPU services behind the apps. Both run as serverless workers on RunPod.

| | What it does | |
| --- | --- | --- |
| ✂️ **background-remover** | Background removal API built on BiRefNet, with an optional SAM 2 pass to close the subject's outline. Cuts out products, clothes and dishes. | 🔒 Private |
| 🎨 **comfyUI-serverless** | A RunPod worker that wraps ComfyUI and ships our image and video generation workflows, so an app only sends a workflow name and its parameters. | 🔒 Private |

## 📄 About our code

Our public repositories are published so they can be read. They are **not open source**: they may
not be used, copied, modified or redistributed without written permission. Each repository's
`LICENSE` has the full terms.
