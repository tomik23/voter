## WYBORNIK
The site can be useful for photographers. You provide photos to the client who selects the size and number of photos for printing.

<img src="wybornik-example.png">

## What you will need
The `images` folder with photos in the main folder.
In the main folder there should also be two configuration files: `.env.dev` and `.env.prod`

The `.env.prod` file should contain production data

## Clone the repo and install dependencies
```bash
git clone https://github.com/tomik23/wybornik.git
cd wybornik
yarn
# or
npm i
```

## Watch/Build the app
Watch the app, just call:

```bash
yarn dev
# or
npm run dev
```

Build app:

```bash
yarn prod
# or
npm run prod
```

## Two versions of the site
We have access to two layouts of this page. After starting the first one, we enable the second one by adding `?s=print` to the url address.  
This parameter changes the look by adding a photo size selection box and a `send email` button.  
Clicking on the button collects all information about the number and size of photos and opens the default e-mail program.