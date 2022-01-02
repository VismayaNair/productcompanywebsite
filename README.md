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

 HOME PAGE:
 ```
 <!DOCTYPE html>
<html lang="en">
  <head>
    <title class="companyname">New Gen Software Pvt. Ltd.</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>
  <body>
    <div class="container">
      <div class="banner">New Gen Software Pvt. Ltd.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
          <h1 class="scrollingwelcome">Welcome to New Gen Software Pvt. Ltd.</h1>
        <div class="homecontent">
          <h1>About Us</h1>
          <img class="contentimg" src="img/building.jpg" alt="img">
          <div class="contenttext">
            New Gen Software Pvt. Ltd. is a global leader in next-generation digital services and consulting. We enable clients in more than 35 countries to navigate their digital transformation.</br>
<p>With over four decades of experience in managing the systems and workings of global enterprises, we expertly steer our clients through their digital journey. We do it by enabling the enterprise with an AI-powered core that helps prioritize the execution of change. We also empower the business with agile digital at scale to deliver unprecedented levels of performance and customer delight. Our always-on learning agenda drives their continuous improvement through building and transferring digital skills, expertise, and ideas from our innovation ecosystem.</p>
            <div>
              <table class="td5">
                <tr>
                  <td class="td4">1000+</br>Happy customers</td>
                  <td class="td4">40+</br>Years of Experience</td>
                  <td class="td4">35+</br>Countries</td>
                  <td class="td4">30</br>Global Offices</td>
                  <td class="td4">2500+</br>Employees</td>
                </tr>
              </table>
            </div>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 New Gen Software Pvt. Ltd., Developed by Vismaya Nair S
      </div>
    </div>
  </body>
</html>
```
PEOPLE PAGE:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title class="companyname">New Gen Software Pvt. Ltd.,</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
    <style>
          .td{
        width: 100%; 
        border: 0px;
        text-align: center;
        }
        .td2{
            width: 50%;
        text-align: center;
        padding-left: 5px;
        padding-bottom: 5px;
        }
        .td3{
            width: 33%;
        text-align: center;
        padding-left: 5px;
        padding-bottom: 5px;
        }
        img{
            height: 50px;
            width: 50px;
        }
    </style>
  </head>

  <body>
    <div class="container">
      <div class="banner">New Gen Software Pvt. Ltd.,</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
      <div class="content">
        <div class="productcontent">    
          <h1>Our Well Trained & Experienced Workers</h1>
          <div class="productitems">
            <table class="td">
              <th style="text-align: left;">Managing Director</th>
              <tr class="td1">
                <td>
                  <img src="img/alan.jpg" alt="hi"></br>
                  Mr.Alan</br>
                  MD,New Gen Software Pvt. Ltd.,
                </td>
          </table>
              <table class="td">
                  <th style="text-align: left;">Chief Members</th>
              <tr class="td2">
                <td>
                  <img src="img/ariana.jpg" alt="hi"></br>
                  Ariana</br>
                  CEO,New Gen Software Pvt. Ltd.,
                </td>
                <td>
                  <img src="img/emma.jpg" alt="hi"></br>
                  Emma Nadella</br>
                  VP,New Gen Software Pvt. Ltd.,
                </td>
              <table class="td">
                  <th colspan="3" style="text-align: left;">Office Of Software Services(OSS)<br>Icludes Software Development, App Development & Game Development</th>
                  <tr>
                    <td class="td3">
                      <img src="img/hyung.jpg" alt="hi"></br>
                      Mr. Hyung</br>
                      CEO,OSS,</br> New Gen Software Pvt. Ltd.,
                    </td>
                    <td class="td3">
                      <img src="img/james.jpg" alt="hi"></br>
                      James Bond</br>
                      Chief Manager,OSS,</br>New Gen Software Pvt. Ltd.,
                    </td>
                    <td class="td3">
                      <img src="img/jimmy.jpg" alt="nivash"></br>
                      Mr.Jimmy</br>
                      Cheif Project Manager,OSS,</br> New Gen Software Pvt. Ltd.,
                    </td>
                  </tr>
            </table>
            <table class="td">
              <th colspan="3" style="text-align: left;">Office Of Web Services(OWS)<br>Icludes Web Development, Server Side Development, Database Services & Cloud Services</th>
              <tr>
                <td class="td3">
                  <img src="img/jin.jpg" alt="hi"></br>
                  Jin Walker</br>
                  CEO,OWS,</br> New Gen Software Pvt. Ltd.,
                </td>
                <td class="td3">
                  <img src="img/krist.jpg" alt="hi"></br>
                  Mrs. Krist</br>
                  Chief Manager,OWS,</br> New Gen Software Pvt. Ltd.,
                </td>
                <td class="td3">
                  <img src="img/lily.jpg" alt="ashwin"></br>
                  Mrs. Lily Akash</br>
                  Cheif Project Manager,OWS,</br>New Gen Software Pvt. Ltd.,
                </td>
              </tr>
        </table>
        <table class="td">
          <th colspan="3" style="text-align: left;">Office Of Cyber Space(OCS)<br>Cyber Security & Ethical Hacking</th>
          <tr>
            <td class="td3">
              <img src="img/park.jpg" alt="hi"></br>
              Mr. Parker</br>
              CEO,OCS,</br> New Gen Software Pvt. Ltd.,
            </td>
            <td class="td3">
              <img src="img/pri.jpg" alt="hi"></br>
              Mrs. Priya</br>
              Chief Manager,OCS,</br> New Gen Software Pvt. Ltd.,
            <td class="td3">
              <img src="img/s.jpg" alt="jeeva"></br>
              Mr. Shawn</br>
              Cheif Project Manager,OCS,</br> New Gen Software Pvt. Ltd.,
            </td>
          </tr>
    </table>
    <table class="td">
      <th colspan="3" style="text-align: left;">Office Of AI & Services (OAIS)<br>Icludes Industrial Robotics, AI Services & Data Related Services</th>
      <tr>
        <td class="td3">
          <img src="img/salee.jpg" alt="hi"></br>
          Mrs. Salee</br>
          CEO,OAIS,</br>New Gen Software Pvt. Ltd.,
        </td>
        <td class="td3">
          <img src="img/Zendaya.jpg" alt="hi"></br>
          Mrs. Zendaya</br>
          Chief Manager,OAIS,</br>New Gen Software Pvt. Ltd.,
        </td>
        <td class="td3">
          <img src="img/z.jpg" alt="hi"></br>
          James Zyen</br>
          Cheif Project Manager,OAIS,</br> New Gen Software Pvt. Ltd.,
        </td>
      </tr>
</table>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 New Gen Software Pvt. Ltd., Developed by Vismaya Nair S.
      </div>
    </div>
  </body>
</html>
```
PRODUCT PAGE:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>New Gen Software Pvt. Ltd.,</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">New Gen Software Pvt. Ltd.,</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/head1.jpeg" alt="product image">
                  </div>
                  <div class="itemname">Gaming Headphones</div>
                  <div class="itemprice">Price: Rs.8,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/head2.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">ROG Gaming HeadPhone</div>
                  <div class="itemprice">Price: Rs.11,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/head3.jpeg" alt="product image">
                </div>
                <div class="itemname">ROG 2 headphones</div>
                <div class="itemprice">Price: Rs.9,000.00 </div>
              </div> 
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/head4.jpg"  alt="product image">
                </div>
                <div class="itemname">Gamers Headphone 2022</div>
                <div class="itemprice">Price: Rs.13,999.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/iphone_13.jpg" alt="product image">
                </div>
                <div class="itemname">Iphone 13</div>
                <div class="itemprice">Price: Rs.1,00,000.00 </div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/iphone_13_pro.jpg"  alt="product image">
                </div>
                <div class="itemname">Iphone 13 Pro</div>
                <div class="itemprice">Price: Rs.1,20,000.00 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/iphone_13_pro_max.png" alt="product image">
              </div>
              <div class="itemname">Iphone 13 ProMax</div>
              <div class="itemprice">Price: Rs.1,40,000.00 </div>
            </div> 
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/mac2.jpg"  alt="product image">
                </div>
                <div class="itemname">Apple MacBook Pro</div>
                <div class="itemprice">Price: Rs.2,39,999.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/mac3.jpg"  alt="product image">
                </div>
                <div class="itemname">Apple MacBook Air</div>
                <div class="itemprice">Price: Rs.84,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/mac4.jpg"  alt="product image">
                </div>
                <div class="itemname">Apple MacBook Air 2020</div>
                <div class="itemprice">Price: Rs.92,990.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/mac5.jpg"  alt="product image">
                </div>
                <div class="itemname">Apple MacBook Pro MVVK2LL</div>
                <div class="itemprice">Price: Rs.1,95,999.00 </div>
              </div>  
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 New Gen Software Pvt. Ltd., Developed by Vismaya Nair S.
      </div>
    </div>
  </body>
</html>
```
CONTACT US PAGE:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title class="companyname">New Gen Software Pvt. Ltd.,</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">New Gen Software Pvt. Ltd.,</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Contact Us</h1>
          <h2>New Gen Software Pvt. Ltd.,</h2>
          <table width="100%" border="0" cellspacing="0" cellpadding="0">
            <tr>
              <td width="33%" valign="top">
                    <p><i><strong>Corporate & Registered Office</strong></i></p>
                    <p>New Gen Software Pvt. Ltd.,<br />
                    #92, New Gen Towers<br />
                    1st & 2nd Floor, Genesis Main Road,  <br/>
                    New Gen Nagar</br>
                    Chennai - 600 024<br />
                    Tamilnadu, India.<br /><br />
                    Phone: +91-95486 54514<br />
                    Tel: 044-4257-4664<br />
                    e-mail:<a target='_blank' href='mailto:info@newgensoftwarepvtltd.com?Subject=Enquiry for New Gen Software Pvt. Ltd.,'> info@genesissoftpvtltd.com</a><br />
                    </p><br />
                </td>
              <td width="33%" valign="top">
               <p><strong>Training& Development Centre New Gen Ltd.</strong><br/> 
                    <p>New Gen Software Pvt. Ltd.,<br />
                     #92, New Gen Towers<br />
                     8th, 9th & 10th  Floor,new gen Main Road,  <br/>
                     Genesis Nagar</br>
                     Chennai - 600 024<br />
                     Tamilnadu, India.<br /><br />
                     Phone: +91-95486 54528<br />
                     Tel: 044-4257-4454<br />
                     e-mail:<a target='_blank' href='mailto:training@genesissoftpvtltd.com?Subject=Enquiry for Training & Development @ New Gen Software Pvt. Ltd.,'> tandd@genesissoftpvtltd.com</a><br />
                    </p><br />
                </td>
              <td width="33%" valign="top">
               <p><strong>Media  & Investor Relations</strong><br/> <p>                          
                      <p><strong>Satya Nadella</strong> <br/>Vice President<p> 
                      <p>New Gen Software Pvt. Ltd.,<br />
                      #92, Genesis Towers<br />
                      3rd Floor, Genesis Main Road,  <br/>
                      Genesis Nagar</br>
                      Chennai - 600 024<br />
                      Tamilnadu, India.<br /><br />
                      Phone: +91-95486 54249<br />
                      Tel: 044-4257-4578<br />
                      e-mail:<a target='_blank' href='mailto:media@genesissoftpvtltd.com?Subject=Enquiry for Media and Related @ New Gen Software Pvt. Ltd.,'> media@genesissoftpvtltd.com</a><br />
                      </p><br />
                </td>
            </tr>
          </table>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 New Gen Software Pvt. Ltd., Developed by Vismaya Nair S
      </div>
  </body>
</html>
```
CSS WORKSHEET:
```
@import url('https://fonts.googleapis.com/css2?family=Mea+Culpa&display=swap');
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: #17421d;
}

.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px gray;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/img/background.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #CAF0F8;
  font-family: 'Mea Culpa', cursive;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #03045E;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #00B4D8;
}

.menuitem a {
  text-decoration: none;
  color: #90E0EF;
}

.content {
  display: block;
  width: 100%;
  background-color: #cffffd;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
  text-align: center;
}

.scrollingwelcome{
  font-size: 40px;
  font-family: 'Times New Roman', Times, serif;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
  width: 1080px;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 380px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
  width: 98%;
}
.contentimg{
  display: inline-block;
  padding-right: 30px;
  text-align: left;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
  text-align: center;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
  text-align: center;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
  padding-right: 5px;
  padding-left: 5px;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #03045E;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #ADE8F4;
}
.td1{
  width: 100%;
  text-align: center;
  padding-left: 5px;
  padding-bottom: 50px;
}

.td{
  width: 98%; 
  border: 0px;
  text-align: center;
}
.td2{
  width: 50%;
text-align: center;
padding-left: 5px;
padding-bottom: 5px;
}
.td4{
  width: 20%;
text-align: center;
padding-left: 5px;
padding-bottom: 5px;
}
.td5{
  width: 98%; 
  border: 0px;
  text-align: center;
  background-color: darkblue;
  color: aliceblue;
  border-right: aliceblue;
}
.td1{
  width: 200%;
  text-align: center;
  padding-left: 5px;
  padding-bottom: 5px;
  width: 100%; 
      border: 0px;
  }
  ```

## OUTPUT:

### Home Page:

![output](./images/home.png)

### Product Page:

![output](./images/product.png)

### People Page:

![output](./images/people.png)

### Contact Us Page:

![output](./images/contactus.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
