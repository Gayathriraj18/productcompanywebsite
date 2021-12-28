# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
```
home coding
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Gayathri Software &co</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Gayathri Software &co.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/building.png" alt="Building" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product TallyPrime takes this to a new level, making your
            start to automation, or your switch to Tally simpler than ever
            before. You can now discover the product much more easily and make
            the product do more for you, without learning anything new. There is
            greater flexibility as the product adapts to your business and your
            way of working. And the transformed look and feel will only make you
            love the product even more.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Gayathri Software &co, Developed by Gayathri.
      </div>
    </div>
  </body>
</html>
```

```
product coding:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Gayathri Software &co.</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Gayathri Software &co.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/adobe.png" alt="product image">
                  </div>
                  <div class="itemname">adobe</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/apple.png"  alt="product image">
                  </div>
                  <div class="itemname">apple</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/cloud.png"  alt="product image">
                </div>
                <div class="itemname">cloud</div>
                <div class="itemprice">Price: Rs.10,000.00 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/excel.png"  alt="product image">
              </div>
              <div class="itemname">excel</div>
              <div class="itemprice">Price: Rs.10,000.00 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/exchange.png"  alt="product image">
            </div>
            <div class="itemname">exchange</div>
            <div class="itemprice">Price: Rs.10,000.00 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/firefox.jpg"  alt="product image">
          </div>
          <div class="itemname">firefox</div>
          <div class="itemprice">Price: Rs.10,000.00 </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/onenote.png"  alt="product image">
        </div>
        <div class="itemname">onenote</div>
        <div class="itemprice">Price: Rs.10,000.00 </div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/opera.jpg"  alt="product image">
      </div>
      <div class="itemname">opera</div>
      <div class="itemprice">Price: Rs.10,000.00 </div>
  </div>
  <div class="productitem"> 
    <div class="itemimage">
    <img src="/static/img/powerpoint.jpg"  alt="product image">
    </div>
    <div class="itemname">powerpoint</div>
    <div class="itemprice">Price: Rs.10,000.00 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/skype.png"  alt="product image">
  </div>
  <div class="itemname">skype</div>
  <div class="itemprice">Price: Rs.10,000.00 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/word.jpg"  alt="product image">
  </div>
  <div class="itemname">word</div>
  <div class="itemprice">Price: Rs.10,000.00 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/yahoo.png"  alt="product image">
  </div>
  <div class="itemname">yahoo</div>
  <div class="itemprice">Price: Rs.10,000.00 </div>
</div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Gayathri Software &co, Developed by Gayathri.
      </div>
    </div>
  </body>
</html>
```
people coding:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Gayathri Software &co</title>
    <link rel="stylesheet" href="./css/layout.css" />
   
  </head>

  <body>
    <div class="container">
      <div class="banner">Gayathri Software &co</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>  
        <div class="menuitemselected"><a href ="/static/people.html"></a>People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/p1.jpg"  alt="product image">
      </div>
         <div class="itemname">HEAD of the company
           <br>
           (Diana)
         </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/p2.jpg"  alt="product image">
      </div>
         <div class="itemname">Manager
           <br>
           (Selvi)
         </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/p3.jpg"  alt="product image">
      </div>
         <div class="itemname">Assistant class <br>(Berry)</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/p4.jpg"  alt="product image">
      </div>
         <div class="itemname">Product Department Head <br> (Jhon)</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/p5.jpg"  alt="product image">
      </div>
         <div class="itemname">Deliver Department Head <br> (Dev)</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/p6.jpg"  alt="product image">
      </div>
         <div class="itemname">Chennai Branch Head <br> (Lakshmi)</div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Gayathri Software &co, Developed by Gayathri
      </div>
    </div>
  </body>
</html>
```
```
contact coding:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Gayathri Software &co</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon2.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Gayathri Software &co</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>  
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      
        <div class="contact content">
           <h1>Our Contact Address</h1>  
        
          <div class="contacttext">
           Phone:6592001799
           <br>Email-address:gayathrisoftware@gmail.com
          </div>
        </div>

     
<div class="footer">
  Copyright &#169; 2021 Gayathri Software &co, Developed by Gayathri
</div>
</div>
</body>
</html>
```



## OUTPUT:

### Home Page:

![output](./images/Homepage.png)
![output](./images/Products.png)
![output](./images/People.png)
![output](./images/Contact.png)
## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
