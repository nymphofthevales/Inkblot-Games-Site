![Company logo](/public/media/logo_small.png)
# Inkblot-Games-Site
A business website for a video game company. Made in Svelte with <a href="https://github.com/Tom-Siegel/multi-page-svelte">Tom Siegel's multi-page-svelte</a>.<br>
```src``` is where the whole show happens.<br> 
```public``` is where the project compiles to (don't edit there unless you're adding assets to ```media```; your changes will be overwritten on next compile if you do).<br>
Any pages added to the site will need to be included in ```rollup-pages-config.js``` as an entry in the ```inputs``` object.<br>
Once dependencies are installed, run ```npm start``` and navigate to localhost to see the site.<br>
If you've made updates and changes, run ```npm run build``` to compile before commiting or viewing the site.
