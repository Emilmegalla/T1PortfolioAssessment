# My Software development Portoflio

## Overview 
This is a portfolio website for dispalying the services that me as software developer provide. This is in development phase and I will keep on adding more features in this readme.


## Components

### Header
Header has logo and name of the company along with navigation bar. Here is the code for the header.

```html
<header>
    <div class="logo-name">
        <a href="./index.html"><img src="./images/developer.png" alt="Software developer logo" width="100px" height="100px"></a>
        <p class="name">
            <span class="coder-text">Emil</span> 
            <span class="academy-text">Megalla</span>
        </p>
    </div>

    <nav class="nav-items">
        <a href="./html/about.html" target="_blank">About</a>
        <a href="./html/service.html" target="_blank">Services</a>
        <a href="./html/contact.html" target="_blank">Contact</a>
    </nav>
    <div class=""></div>
</header>
```


 ### Footer 

 Footer has the devloper social media icons and contact details
 
 ```html
  <footer>
        <div class="social-media">
            <a href=""><i class="fa-brands fa-github"></i></a>
            <a href=""><i class="fa-brands fa-linkedin"></i></a>
            <a href=""><i class="fa-solid fa-blog"></i></a>
        </div>

        <div class="info">
            <p>Contact: 0404040404</p>
            <p>Address: 1 Street st Subrub</p>
        </div>
    </footer>
```

## Pages

### Home
Home page, for now just display some lorem inum text. Code is below
```html
 <main>
      <section>
        <div class="jumbotrin">
          <img src="./images/jumbotron.jpg" alt="" />
        </div>

        <div class="details">
          <p>
            Lorem ipsum text
        </div>
      </section>
    </main>
```
### Services
Services page displays the list of services that we provide .

### Contact
Contact page can be use to contact the company.

## Styeling

### Components
These will contain the styling of individual componets which are as following 
- Header
- Footer

### Defaults 
This will contain the default variables such as colors, breakpoints, etc

### Pages
This will contain the styling of each individual HTML pages

