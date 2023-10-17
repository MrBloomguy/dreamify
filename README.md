<img
    src="https://github.com/MrBloomguy/JiGi/blob/main/.github/jigilogoo.png"
    align="center"
    width="100"
    alt="Jigi"
    title="JíGí"
  />
  <h1 align="center">JíGí</h1>
</p>

<p align="center">
   Bring local stories to live with JíGí AI art generator 🎨
</p>

<p align="center">
  🚀 Over 500 generations!
</p>

## 🚀 Concept

JiGi is a JíGí fork. It is a web application that allows you to generate images with AI. It uses the [Stable Diffusion](https://stability.ai/blog/stable-diffusion-public-release) model to generate images. The model is run on cloud with [Replicate](https://replicate.com/).

### 🎨 Stable Diffusion

[Stable Diffusion](https://en.wikipedia.org/wiki/Stable_Diffusion) is a deep learning, text-to-image model released in 2022. It is primarily used to generate detailed images conditioned on text descriptions, though it can also be applied to other tasks such as inpainting, outpainting, and generating image-to-image translations guided by a text prompt.

This Diffusion Model is run on cloud with [Replicate](https://replicate.com/). Replicate is a platform for running and sharing machine learning models. JíGí uses the Replicate API to run the model.

### ✨ User Interface

JiGi is built with [Tailwind CSS](https://tailwindcss.com/). Components like the Buttons, Inputs, Modals and Progress Bar are developed with [Shadcn/ui](https://ui.shadcn.com/docs), a collection of re-usable components built using [Radix UI](https://www.radix-ui.com/).

## 📦 Deployment

JiGi is deployed on [Vercel](https://vercel.com/).

## 🚀 Core Development

JíGí is built with [Next.js 13.2](https://nextjs.org/), [React](https://reactjs.org/) and [Tailwind CSS](https://tailwindcss.com/).

Since it's the latest build of Next.js, it uses many of the new features like [Image Component](https://nextjs.org/docs/api-reference/next/image), [File System Routing](https://nextjs.org/docs/routing/introduction) and [Incremental Static Regeneration](https://nextjs.org/docs/basic-features/data-fetching#incremental-static-regeneration).

If you want to run JíGí locally, after clone this repository and run the following commands:

```bash
# Install dependencies
npm install

# Create .env.local
touch .env.local
```

In order to run Stable Diffusion model, you need to create an account on [Replicate](https://replicate.com/) and get your API Key.

Then, add the following environment variables to `.env.local`:

```bash
REPLICATE_API_TOKEN="YOUR_API_KEY"
```

And that's it! Now you can run the following command to start the development server:

```bash
npm run dev
```

## 🤲 Contributing

JíGí is an open source project forked from [https://dreamify.art/]


## 📃 License

Distributed under the MIT License.
See [`LICENSE`](./LICENSE) for more information.
