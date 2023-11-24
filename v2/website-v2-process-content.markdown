<style>@import url("//readme.codeadam.ca/readme.css");</style>

## Process

IN this project we wil be adding pages to the [BrickMMO Website](https://brickmmo.com/) for each of the systems created or in development. 

---

### Already Completed

The BrickMMO Website website already exists and has most pages near completion. The website [home page](https://brickmmo.com/) lists three of the existing systems and a link to the [systems page](https://brickmmo.com/systems). 

*** 

### Steps


For each system listed on the [systesm page](https://brickmmo.com/systems) you will create a page. You will need to follow these steps:

1. Create a route using the format `systems-<SYSTEM_NAME>`. For example, the GPS system URL would be `systems-gps`.

2. Create a folder for the new page. The page files are in `/src/views/pages` folder. The folder name will be `Systems<SYSTEM_NAME>` using pascal case. For example the folder name for the GPS system would be `SystemGps`.

3. Copy the page files from `/src/pages/CommissionsHumber`. The layout for each system page will follow that of a commissioned projet. Review the [Humber Logo](https://brickmmo.com/commissions-humber) project for an example.

4. Rename `/src/pages/SystemsGps/CommissionsHumber.js` to `/src/pages/SystemsGps/SystemGps.js`.

5. Open the `/src/pages/SystemsGps/SystemGps.js` file and update the `const` line and the `export default` line.

6. Update the import files. You will need to update the following files ro reference the new filename:

    - `/src/pages/index.js`
    - `/src/pages/SystemsGps/index.js`

7. Update the page title to the system name. The rest of teh content wil lbe updated at a later date.

[&#10132; Back to V2](/radio-about/v2)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
