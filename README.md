
# Smart Scroll

## overview
A light weight JQuery plugin that make it easy to navigate to page section
an sync navigation active link with the section aspect to it

[check out the demo line](https://smart-scroll.netlify.com/)

## how to use

 - initializing smart scroll 
            
        ` 
        smartScroll.init({
                         speed: 1000, // default 500
                         addActive: true, // default true
                         activeClass: "active", // default active
                         offset: 150 // default 100
                     });
        `
    
        
 - add `data-scroll` html custom attribute to the navigation links
 
    
         <nav>
                <ul>
                    <li><a href="#!" data-scroll="page1">page1</a></li>
                    <li><a href="#!" data-scroll="page2">page2</a></li>
                    <li><a href="#!" data-scroll="page3">page3</a></li>
                    <li><a href="#!" data-scroll="#page4">page4</a></li>
                    <li><a href="#!" data-scroll="page5">page5</a></li>
                </ul>
            </nav>
        
        
  - it should has the same value as the id used for the section
   
        
          <div id="#page3">page3</div>
          
          <li><a href="#!" data-scroll="page3">page3</a></li>

        
