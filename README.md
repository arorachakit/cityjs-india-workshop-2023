# Next.js and Storyblok Workshop- CityJS India 2023

This repository is a Next.js project with [Storyblok](https://www.storyblok.com). 
## Requirements

To use this project you have to have a Storyblok account. If you don't have one yet you can register at [Storyblok](https://www.storyblok.com), it's free.

### Find the slides [here](https://docs.google.com/presentation/d/1t7WzL531xew8GDkNNTvr9oxYBwvmhuGs_YsZA-il84Y/edit?usp=sharing)
### Find the notion page [here](https://storyblok.notion.site/CityJS-India-Go-Headless-with-Next-js-13-and-Storyblok-0bd2e8be30964eb9b062309228d60ab5)

### Deployed URL - https://cityjs-india-workshop-2023.vercel.app/


## How to get started?

### 1. Clone the repo

```sh
  $ git clone https://github.com/arorachakit/cityjs-india-2023-workshop.git
```

### 2. Install all dependecies 
```sh
$  npm install # or yarn
```

### 3. Adding the Access token
Create a new empty Space and exchange the preview token with your own in ```app/layout.js``` and ```components/StoryblokProvider.js```.

```js
storyblokInit({
  accessToken: "your-preview-token",
  use: [apiPlugin],
});
```

### 4. Run your project
Set the preview domain in <strong>Storyblok</strong> to `http://localhost:3000/`

```sh
# to run in developer mode
$ npm run dev #or yarn dev
```

```sh
# to build your project
$ npm run build # or yanr build
```



## Resources

- [Next.js docs](https://nextjs.org/docs/#setup)
- [Storyblok Tutorial](https://www.storyblok.com/tp/add-a-headless-cms-to-next-js-13-in-5-minutes)