<div align="center">
    <p>
        <img src="./resources/images/main-logo.png">
        <a href="https://roots.io/sage/">
            <img alt="Sage" src="https://cdn.roots.io/app/uploads/logo-sage.svg" height="50">
        </a>
    </p>
    <p>
        <img src="https://img.shields.io/badge/wordpress-grey?style=for-the-badge&logo=wordpress">
        <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white">
    </p>
</div>
  
Wordpress theme made with Sage 10 and based on the one provided by <a href="https://wp.ditsolution.net/techpros/">Template Monster</a>. The version made with vanilla CSS and PHP is available at <a href="https://github.com/FabioLace/techpros-theme">this link</a>.

# Info
* PHP ^8.0
* Roots/acorn: ^3.2
* Node.js >= 16.0.0
  
### DEV Dependencies

```sh
"@roots/bud": "^6.15.2",
"@roots/bud-sass": "^6.15.2",
"@roots/sage": "^6.15.2"
```

### External Libraries
* <a href="https://animate.style/">Animate.css 4.1.1</a>
* <a href="https://getbootstrap.com/">Bootstrap 4.5.2</a> 
* <a href="https://fontawesome.com/">Fontawesome 6.4.2</a>
* <a href="https://swiperjs.com/">Swiper.js</a>

# Deploy
* Download the repo in the "themes" folder of your Wordpress project.
* Open themes/techpros-sage in your terminal and launch these commands:
```sh
composer require roots/acorn
composer install
yarn
yarn build
```

* Even if Sage 10 docs recommends yarn,you can also use npm:
```sh
npm install
npm run build
```

* Activate the theme from CMS

# See also
* <a href="https://roots.io/sage/docs/installation/">Sage Docs</a>
