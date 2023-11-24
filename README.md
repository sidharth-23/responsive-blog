# responsive-blog

/*custom.scss*/
nav {
  display: flex;
  //   background-color: aqua;
  justify-content: space-between;
  height: 70px;

  .logoimg {
    display: flex;
    align-items: center;
    img {
      width: 260px;
      height: 47.31px;
      // top: 30px;
      // left: 30px;
    }
  }

  ul {
    display: flex;
    justify-content: space-between;
  }

  li {
    font-family: "Poppins";
    margin-left: 30px;

    a {
      color: black;
      font-size: 14px;
    }
  }
  .button {
    display: flex;
    align-items: center;

    button {
      width: 140px;
      height: 50px;
      border-radius: 40px;
      background-color: orange;
      color: white;
      border: none;
    }
  }
}

.frame1 {
  // margin: 0;

  // width: 1366 px;
  .banner {
    height: 600px;
    background-image: url(../images/Rectangle\ 23.png);
    background-size: cover;
    // position: relative;
  }

  .companyname h1 {
    text-align: center;
    font-family: Poppins;
    font-size: 60px;
    font-style: normal;
    font-weight: 300;
    line-height: normal;
    letter-spacing: 6px;
    text-transform: uppercase;
    background: linear-gradient(90deg, #7074e7 0.16%, #5dbce9 101.88%);
    background-clip: text;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    margin: 0;
  }

  .imgholder {
    display: flex;
    justify-content: center;
    align-items: center;
    .bannerimg {
      margin-top: 140px;
    }
  }
  .companymotto h2 {
    color: #fff;
    margin: 0;
    text-align: center;
    font-family: Poppins;
    font-size: 60px;
    font-style: normal;
    font-weight: 300;
    line-height: 70px; /* 116.667% */
    text-transform: capitalize;
  }
}
.desc {
  height: 347px;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: rgb(255, 251, 251);
  border-radius: 40px;
  position: absolute;
  bottom: -250px;
  padding: 50px;
  box-shadow: 0px 20px 40px 0px rgba(57, 61, 153, 0.06);

  // bottom: 90px;

  // margin: 40px;
}

.desc p {
  // background-color: #7074e7;
  // padding: 30px;
  color: #1e1e1e;

  text-align: center;
  font-family: Poppins;
  font-size: 20px;
  font-style: normal;
  font-weight: 300;
  line-height: 42px;
}

.frame2 {
  background-color: #f8fdff;
}
.clients {
  margin-top: 300px;
  text-align: center;
  h1 {
    color: #323338;
    text-align: center;
    font-family: Poppins;
    font-size: 45px;
    font-style: normal;
    font-weight: 300;
    line-height: normal;
    text-transform: uppercase;
  }
  .firstrow,
  .secondrow {
    display: flex;
    justify-content: space-between;
    padding: 30px;

    img {
      width: 80px;
    }
  }
}

.numbers {
  // margin: 30px 0;
  padding-bottom: 90px;
  .numbers-desc {
    display: flex;
    justify-content: space-between;
    background-color: rgb(255, 251, 251);
    padding: 30px;
    border-radius: 30px;
    box-shadow: 0px 15px 30px 0px rgba(0, 55, 100, 0.06);
    .matter {
      max-width: 300px;
    }
    .innermatter {
      display: flex;
      max-width: 200px;

      img {
        margin-left: 30px;
      }
    }
    .matterdesc {
      max-width: 100px;

      p {
        text-align: justify;
      }
    }
  }

  h1 {
    color: #323338;
    text-align: center;
    font-family: Poppins;
    font-size: 45px;
    font-style: normal;
    font-weight: 300;
    line-height: normal;
    text-transform: uppercase;
  }
}

.frame3 {
  // width: 1366 px;
  .services {
    height: 940px;
    background: linear-gradient(
        to bottom,
        rgba(10, 83, 143, 0.7),
        rgba(0, 44, 65, 0.7)
      ),
      url("../images/Rectangle\ 24.png");
    background-size: cover;

    h1 {
      color: #fff;
      padding-top: 70px;
      padding-bottom: 30px;
      text-align: center;
      font-family: "Poppins";
      font-size: 45px;
      font-style: normal;
      font-weight: 300;
      line-height: normal;
      text-transform: uppercase;
      margin: 0;
    }
    .rows {
      display: flex;
      align-items: center;
      justify-content: space-around;
      //   margin:30px;
      //   padding: 50px;
      //   height: 100px;
      .service-desc {
        position: relative;
        width: 300px;
        background-color: transparent;
        color: white;
        border-radius: 25px;
        font-size: 12px;
        opacity: 0.8;
        background: #010829;
        padding: 50px;
        box-shadow: 0px 2px 5px 0px rgba(0, 55, 100, 0.08);
        height: 300px;
      }
    }
    .rows1 {
      display: flex;
      align-items: center;
      justify-content: space-around;
      margin-top: 30px;
      .service-desc {
        width: 300px;
        background-color: transparent;
        font-size: 12px;
        background: #010829;
        color: white;
        border-radius: 25px;
        opacity: 0.8;
        padding: 50px;
        box-shadow: 0px 2px 5px 0px rgba(0, 55, 100, 0.08);
        height: 300px;
        .learnmore {
          display: flex;
          align-items: center;
          justify-content: center;
        }
      }
    }
  }
}
.mybutton {
  display: none;
  width: 140px;
  height: 50px;
  border-radius: 40px;
  background-color: orange;
  color: white;
  border: none;
  position: absolute;
  bottom: -22px;
}

.service-desc:hover .mybutton {
  display: block;
  cursor: pointer;
}
.learnmore {
  display: flex;
  align-items: center;
  justify-content: center;
}

.frame4 div {
  background-image: url(../images/pngwing\ 1.png);
  height: 350px;
  // width: 800px;
  //   background-size: cover;
  h1 {
    // margin-top: 50px;
    color: #2e3192;
    text-align: center;
    font-family: Poppins;
    font-size: 45px;
    font-style: normal;
    font-weight: 300;
    line-height: 55px;
  }
  p {
    color: #1e1e1e;
    text-align: center;
    font-family: Poppins;
    font-size: 17px;
    font-style: normal;
    font-weight: 300;
    line-height: 34px;
  }
}

.getintouch {
  height: 600px;
  // width: 1366px;
  display: flex;
  align-items: center;
  justify-content: space-around;
  background: linear-gradient(277deg, #0e131d -7.66%, #01123d 89.79%);
  .form {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .formbox {
    h1 {
      text-align: center;
      color: white;
    }
    .submitbtn {
      display: flex;
      justify-content: center;
      width: inherit;
      button {
        width: 300px;
        border-radius: 20px;
        height: 40px;
        border: none;
        background-color: orange;
        color: white;
      }
    }
  }

  .info,
  .form {
    height: 250px;
    width: 400px;
    input {
      margin: 10px;
      border: none;
      outline: none;
      width: 300px;
      border-radius: 20px;
      padding: 8px;
    }
    button {
      width: 70%;
      margin-left: 30;
    }
    h1 {
      color: #fff;
      text-align: center;
      font-family: Poppins;
      font-size: 35px;
      font-style: normal;
      font-weight: 300;
      line-height: 35px;
    }
    .mail {
      display: flex;
      align-items: center;
      justify-content: center;
      margin: 0 auto;
    }
    h2 {
      color: #fff;
      margin: 0;
      text-align: center;
      font-family: Poppins;
      font-size: 25px;
      font-style: normal;
      font-weight: 300;
      line-height: 35px;
    }
    h4 {
      color: #fff;
      margin: 0;
      text-align: center;
      font-family: Poppins;
      font-size: 25px;
      font-style: normal;
      font-weight: 300;
      line-height: 55px;
    }
    p {
      color: #fff;
      margin: 0;
      text-align: center;
      font-family: Poppins;
      font-size: 20px;
      font-style: normal;
      font-weight: 300;
      line-height: 35px;
    }
    h4,
    p,
    h2 {
      color: white;
    }
  }
}

.footer1 {
  height: 360px;
  display: flex;
  align-items: center;
  justify-content: space-around;
  .footercontents {
    li {
      color: #323338;

      font-family: Poppins;
      font-size: 16px;
      font-style: normal;
      font-weight: 300;
      line-height: 45px;
    }
    a {
      color: #323338;
    }
  }
  .onlytwo ul{
    align-items: start;
  }
}

.black{
  background-color: black;


.footer2{
  display: flex;
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: black;
  height: 80px;
  .innerFooterDiv{
    display: flex;
    align-items: center;
    color: white;
  }
  .credentials {
    span{
      color: white;
      .sitename{
        color: skyblue;
      }
    }
  }
}
}


/*html*/
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link
            href="https://fonts.googleapis.com/css2?family=Poppins&display=swap"
            rel="stylesheet">

        <link rel="stylesheet" href="./css/style.css">
    </head>
    <body>
        <header>
            <nav>
                <div class="logoimg">
                    <img src="./images/logo-01 1.png" alt="img">
                </div>

                <div class="linksinnav">
                    <ul>
                        <li id="one"><a href="about.html">About</a></li>
                        <li><a href="#">Services</a></li>
                        <li><a href="#">Market</a></li>
                        <li><a href="#">Clients</a></li>
                        <li><a href="#">Strategic Partners</a></li>
                        <li><a href="#">News</a></li>

                    </ul>
                </div>

                <div class="button">
                    <button>Contact Us</button>
                </div>
            </nav>
        </header>

        <!-- BANNER -->

        <section class="frame1">
            <div class="banner">
                <div class="imgholder">
                    <img class="bannerimg" src="./images/logo-01 2.png" alt>
                </div>
                <div class="companyname">
                    <h1>IBG GLOBAL</h1>
                </div>
                <div class="companymotto">
                    <h2>The world’s largest <br>
                        international trade consultancy</h2>
                </div>

            </div>

        </section>

        <!-- BANNER SECTION OVER -->
        <section class="frame2">

            <div class=" container">
                <div class="desc">
                    <p>IBG Global is a global network of 21 independently owned
                        international trade consultancies established in 2002 to
                        provide market entry services to exporters and
                        investment promotion marketing to economic development
                        agencies. Working for international trade and investment
                        agencies at the national and regional levels, and
                        directly with private sector companies, we increase our
                        customers’ export sales. IBG Global is the world’s most
                        experienced international trade network with the
                        greatest number of in-country offices.</p>
                </div>

            </div>

        </section>
        <div class="clients container">
            <h1>Clients that matter</h1>
            <div class="firstrow">
                <div><img src="./images/GMSP Partnership Logo 1.png" alt></div>
                <div><img src="./images/Ohio Development Services Agency 1.png"
                        alt></div>
                <div><img src="./images/Invest_Northern_Ireland_logo 1 (1).png"
                        alt></div>
                <div><img src="./images/VEDP_Logo 1 (1).png" alt></div>
                <div><img src="./images/company_logo 1.png" alt></div>

                <div><img src="./images/image 1.png" alt></div>

            </div>
            <hr>
            <div class="secondrow">
                <div><img
                        src="./images/switzerland-global-enterprise-s-ge-vector-logo 1.png"
                        alt></div>
                <div><img
                        src="./images/michigan-economic-development-corporation-medc-vector-logo 1.png"
                        alt></div>

                <div><img
                        src="./images/great-lakes-and-st-lawrence-governors-and-premiers-gsgp-logo-vector 1.png"
                        alt></div>

                <div><img src="./images/image 10.png" alt></div>

                <div><img src="./images/image 11.png" alt></div>
                <div><img src="./images/Business_Finland 1.png" alt></div>

            </div>
        </div>
        <div class="numbers container">
            <h1>Numbers that matter</h1>
            <div class="numbers-desc">
                <div class="matter">
                    <div class="innermatter">
                        <div><img src="./images/Group.svg" alt></div>
                        <div><img src="./images/2,880+.png" alt></div>
                    </div>
                    <div class="matter-desc"><p>Market entry reports and partner
                            searches in the past 3 years</p></div>
                </div>
                <div class="matter"><img src="./images/Line 2.png" alt></div>

                <div class="matter">
                    <div class="innermatter">
                        <div><img src="./images/Vector.svg" alt></div>
                        <div><img src="./images/150+.png" alt></div>
                    </div>
                    <div class="matter-desc"><p>Trade missions in the past 3
                            years</p></div></div>
                <div class="matter"><img src="./images/Line 2.png" alt></div>
                <div class="matter">
                    <div class="innermatter">
                        <div><img src="./images/Layer 2.svg" alt></div>
                        <div><img src="./images/53.png" alt></div>
                    </div>
                    <div class="matter-desc"><p>Countries with in-country staff</p></div>
                </div>
            </div>
        </div>
        <section class="frame3">
            <div class="services">
                <h1>Services that matter</h1>
                <div class="rows container">
                    <div class="service-desc">
                        <h3>Market Research & Intelligence</h3>
                        <p>IBG Global has delivered more than 2,800
                            international market entry reports and
                            partner searches in just the past three years, in
                            virtually all industries and in dozens of
                            countries.</p>
                            <div class="learnmore"><button class="mybutton">Learn more</button></div>
                    </div>
                    <div class="service-desc">
                        <h3>Trade Missions & Trade Shows</h3>
                        <p>IBG Global has completed more than 150 trade missions
                            in just the past three years, in
                            virtually all industries and in multiple country
                            markets.</p>
                            <div class="learnmore"><button class="mybutton">Learn more</button></div>
                    </div>
                    <div class="service-desc">
                        <h3>Foreign Direct Investment (FDI)AttractionMarket
                            Research & Intelligence</h3>
                        <p>IBG Global has been retained by a wide assortment of
                            national and state governments
                            to conduct comprehensive FDI recruitment and to
                            manage government investment
                            attraction...</p>
                            <div class="learnmore"><button class="mybutton">Learn more</button></div>
                    </div>
                </div>
                <div class="rows1    container">
                    <div class="service-desc">
                        <h3>Partner and Distributor Search</h3>
                        <p>IBG Global has delivered more than 2,800 partner
                            searches and market entry reports in
                            just the past three years.</p>
                            <div class="learnmore"><button class="mybutton">Learn more</button></div>
                    </div>
                    <div class="service-desc">
                        <h3>Trade Agency Representation</h3>
                        <p>IBG Global has more experience representing national
                            and state governments in
                            countries across the world than any other
                            international trade consultancy network.</p>
                            <div class="learnmore"><button class="mybutton">Learn more</button></div>
                    </div>
                    <div class="service-desc">
                        <h3>Corporate
                            Support</h3>
                        <p>IBG Global coordinates, or directly offers, corporate
                            support services through in-country
                            experts (legal, accounting, HR, etc.) which
                            includes:</p>
                            <div class="learnmore"><button class="mybutton">Learn more</button></div>
                    </div>
                </div>

            </div>

        </section>
        <section class="frame4">
            <div class="container">
                <h1>PROFESSIONALS THAT MATTER</h1>
                <p>IBG Global’s consultants provide our clients with highly skilled trade and investment knowledge, fluent English and local language skills, large public and private sector networks of contacts, and an in-country presence that will accelerate your market entry, better enabling you to capitalize on the very lucrative business of international trade.</p>
            </div>

        </section>

            <div class="getintouch">
                <div class="info">
                    <p>Have a project to discuss? Send us an email or fill out the form and we’ll get back to you quickly.</p>
                    <div class="mail"><img src="./images/msg.svg" alt=""><h4>info@ibgglobal.com</h4></div>
                    <h2>Paul H. Grossman</h2>
                    <h2> Executive Director</h2>
                </div>
                <div class="line">
                    <img src="./images/Line 8.png" alt="">
                </div>
            <div class="formbox">
                <h1>Get in touch</h1>
                <div class="form">
                        
                        <form action="">
                            <input type="text" placeholder="Name"><br>
                            <input type="text" placeholder="Company Name"><br> 
                            <input type="text" placeholder="E-mail"><br>
                            <input type="text" placeholder="How can we help?"><br>
                            
                        </form>
                       


                </div>
                <div class="submitbtn">
                    <button type="submit">Submit Now!</button>
                </div>
            </div>


            </div>
        
       <!-- footer1 -->
       <footer>
       <div class="footer1 container">
            <div class="footercontents">
                <img src="./images/logo 1.png" alt="">
            </div>
            <div class="footercontents">
                <ul>
                    <li ><a href="">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Services</a></li>
                   
                    <li><a href="#">Strategic Partners</a></li>
                   

                </ul>
            </div>
            <div class="footercontents">
                <ul>
                    <li ><a href="">Clients</a></li>
                    <li><a href="#">News</a></li>
                    <li><a href="#">Location</a></li>
                   
                    <li><a href="#">Contact</a></li>
                   

                </ul>
            </div>
            <div class="footercontents onlytwo">
                <ul>
                    <li ><a href="">Contact Information</a></li>
                    <li><a href="#">E-mail:info@ibgglobal.com</a></li>

                </ul>
                
                
            </div>
            <div class="footercontents onlytwo">
                <ul>
                    <li ><a href="">Follow us on</a></li>
                    <li><a href="#"><img src="./images/linkedin (2) 1.svg" alt=""></a></li>

                </ul>
            </div>
       </div>
       <div class="black">
       <div class="footer2 container">
        <div class="innerFooterDiv">
            <img src="./images/logo-01 2.png" alt="" width="30px" height="30px">
            <h6>© 2023 IBG Global, LLC, All rights reserved.</h6>
        </div>
        <div class="credentials">
            <span>Site by <span class="sitename">Acodez</span></span>
        </div>
       </div>
    </div>
    </footer>
       

    </body>
</html>

/*default*/
*{
    box-sizing: border-box;
    font-family: "Poppins";
    
    // background: #F8FDFF;
}

body{
    margin: 0;
}
    a{
    text-decoration: none;
}

li{
    list-style-type: none;
}

.container{
    max-width: 1080px;
    margin: 0 auto;
    padding: 0 16px;
    position: relative;
    // background-color: aqua;
}
