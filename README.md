## Prepare to run the plugin on a server

1. Build the plugin using `npm install` and `npm run build`

2. Go to `plugin-jatos-waiting-room/dist` and copy the file `index.browser.js`

3. Go to `test-jatos-waiting-room/jspsych` and paste the file, rename to `plugin-jatos-waiting-room.js`

## Run on local server

1. Locate where your `study-assets-root` folder is. When you open the page localhost:9000, you'll see the address.

2. Create a `New Study` on the JATOS server homepage. This will create a new folder in the `study-assets-root` folder, with a randomly-generated UUID.

3. Copy the **content** of `test-jatos-waiting-room` into this new folder.

4. On the JATOS server homepage, click on `Properties`, then make sure `Group Study` is toggled on.

5. Add the html file: Click on `New Component`, put in a title and the location of the `index.html` file. If you're using the same structure, then you should just put `index.html` file in the box.

6. To test, press `Run`. To share with other people, click `Study Links`. Easiest option is to toggle on `General Multiple` (General --> many people can use the same link, Multiple --> one person can use one link many times). More information on [link types](https://www.jatos.org/Run-your-Study-with-Study-Links.html). 

7. 
