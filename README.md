<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Lalu Khairan - Frontend Web Developer </title>
    <link rel="icon" type="image/x-icon" a href="WhatsApp Image 2023-08-04 at 14.35.08.jpeg">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" media="screen and (max-width: 821px)" href="responsive.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css">
</head>
<body>

    <!-- Navbar Section -->
    <nav id="navbar" class="flex s-around bg-color">
        <div class="left-nav">
            <h2 class="t-white">Lalu Khairan</h2>
        </div>
        <div class="right-nav">
            <ul class="flex">
                <li><a href="#home" class="t-white roboto">Home</a></li>
                <li><a href="#about" class="t-white roboto">About Me</a></li>
                <li><a href="#skills" class="t-white roboto">Skills</a></li>
                <li><a href="#services" class="t-white roboto">services</a></li>
                <li><a href="#projects" class="t-white roboto">Projects</a></li>
            </ul>
        </div>
    </nav>

    <!-- Bottom Navigator -->
    <section id="bottom">
        <div class="bottom-nav flex s-center items-center">
            <ul class="flex s-around items-center">
                <a href="#home">
                    <li class="bottomo-hover flex s-center items-center"><i class="fa-solid fa-house"></i></li>
                </a>
                <a href="#about">
                    <li class="bottomo-hover flex s-center items-center"><i class="fa-solid fa-user"></i></li>
                </a>
                <a href="#skills">
                    <li class="bottomo-hover flex s-center items-center"><i class="fa-solid fa-code"></i></li>
                </a>
                <a href="#services">
                    <li class="bottomo-hover flex s-center items-center">
                        <i class="fa-solid fa-rocket"></i>
                    </li>
                </a>
            </ul>
        </div>
    </section>

    <!-- Home Section -->
    <section id="home" class="flex s-around sw-80 m-auto">
        <div class="home-left flex items-center">
            <div class="home-content">
                <h6 class="poppinss">Hi, I'm</h6>
                <h1 class="t-white">Lalu Khairan</h1>
                <h4 class="poppinss">Frontend Web Developer</h4>
                <a href="#" target="_blank"><button
                        class="btn poppins">Resume</button></a>
                <a class="btn live poppins" id="hireme" href="https://www.instagram.com/iyanvfd_/#"
                    target="_blank">Let's Talk</a>
            </div>
        </div>
        <div class="home-right flex s-center items-center">
            <div class="circle flex s-center items-center" id="mainImage">
                <!-- Here in src replace the given link with your image link -->
                <img src="WhatsApp Image 2023-08-04 at 14.35.08.jpeg" alt="">
            </div>

        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <h1 class="t-center my-2 t-white f-2">About Me</h1>
        <div class="about-container flex s-around ">
            <div class=" about-left flex s-center items-center">
                <!-- Here in src replade the given link with your secondary image link -->
                <img src="https://instagram.fdps5-1.fna.fbcdn.net/v/t51.2885-19/359069561_588581776766689_5467215249730610349_n.jpg?stp=dst-jpg_s150x150&_nc_ht=instagram.fdps5-1.fna.fbcdn.net&_nc_cat=101&_nc_ohc=hPma8c4OV90AX9u1Bp5&edm=AOQ1c0wBAAAA&ccb=7-5&oh=00_AfC39IVM0y2nU6ooKgC2yYsuv8NCiEGpdJzyj-jqJe2PkA&oe=64D1CC43&_nc_sid=8b3546" alt="" style="width: 50%;">
            </div>

            <div class="about-right flex">
                <div class="about-content">
                    <h1 class="t-white m-b-1 poppins">Lalu Khairan</h1>
                    <p class="t-white poppins">A self-tought Frontend Web Developer BCA student looking for
                        an opportunity in Web Development. <br>
                        Who is committed to study web development. Mindset to fullfill the life with
                        wonderful memories and knowledge.</p>
                    <a class="btn live poppins" id="hireme"
                        href="https://www.instagram.com/iyanvfd_">Hire Me</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h1 class="t-center my-2 t-white f-2">Skills</h1>
        <div class="services-container flex s-around h-50"">
        <div class=" skills-left flex s-center items-center">
            <img src="" alt="">
        </div>

        <div class="skills-right flex items-center">
            <div class="skillss-container">
                <div class="html bar p-relative"><span class="bar-content left t-white">HTML</span><span
                        class="bar-content right-skills t-white">90%</span></div>
                <div class="css bar p-relative"><span class="bar-content left t-white">CSS</span><span
                        class="bar-content right-skills t-white">80%</span></div>
                <div class="js bar p-relative"><span class="bar-content left t-white">JavaScript</span><span
                        class="bar-content right-skills t-white">75%</span></div>
                <div class="bootstrap bar p-relative"><span class="bar-content left t-white">Bootstrap</span><span
                        class="bar-content right-skills t-white">50%</span></div>
                <div class="reactjs bar p-relative"><span class="bar-content left t-white">ReactJs</span><span
                        class="bar-content right-skills t-white">30%</span></div>
            </div>
        </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services">
        <h1 class=" t-center my-2 t-white f-2">Services</h1>
        <div class="services-container flex s-center">
            <div class="test-item flex f-col items-center">
                <img src="https://www.niagahoster.co.id/blog/wp-content/uploads/2020/09/Coding-HTML-Dasar-untuk-Blogger.jpg" alt="">
                <h1 class="t-white poppins">Web Development</h1>
                <p class="t-white poppins">Web Development is envolving everywhere. Every startup and every bussines
                    have their own websites. As my passion I will help you to build your clean and fast website for your
                    startup or your bussines.</p>
            </div>
            <div class="test-item flex f-col items-center">
                <img src="https://play-lh.googleusercontent.com/VRMWkE5p3CkWhJs6nv-9ZsLAs1QOg5ob1_3qg-rckwYW7yp1fMrYZqnEFpk0IoVP4LM" alt="">
                <h1 class="t-white poppins">Social Media Management</h1>
                <p class="t-white poppins">Social Media is the power of future. So I'll help in developing brand
                    awareness thow managing your social media handles and will to increase customer loyalty.</p>
            </div>
            <div class="test-item flex f-col items-center">
                <img src="https://vocasia.id/blog/wp-content/uploads/2021/09/cara-membangun-brand-sendiri.jpg" alt="">
                <h1 class="t-white poppins">Growth Strategies</h1>
                <p class="t-white poppins">As a web developer also I will help your brand to grow up . I will provide
                    the growth strategies for your brand. And also help in searching techniques for your brand.</p>
            </div>

        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h1 class=" t-center my-2 t-white f-2">Projects</h1>
        <div class="projects-container flex s-center">
            <div class="projects-item flex f-col s-center items-center">
                <div class="image-container p-one">
                    <img src="https://static.wikia.nocookie.net/ipod/images/d/d6/Weather_iOS_15.png/revision/latest?cb=20220611140027" alt="">
                </div>
                <h1 class="t-white poppins">Weather App</h1>
                <p class="t-white poppins"> A weather app using HTML, CSS and JavaScript. Fetch the weather from the
                    openweather app using fetch api.</p>
                <div class="buttons flex s-around">
                    <a href="#"
                        target="_blanks" class="btn mx-1 m-top">GitHub</a>
                    <a href="#" target="_blanks" class="btn m-top live">Live
                        Link</a>
                </div>
            </div>
            <div class="projects-item flex f-col s-center items-center">
                <div class="image-container p-one">
                    <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAANcAAADrCAMAAADNG/NRAAAAw1BMVEX/hzL169zWIwD////UAAD38+T17uD/giT/gB/5xKH32MH39OX27uH16tvVGwDVFQDig3Lux7ffcGLdXEnruavhemrdZFLaRzLpqZr/hSz049Pwz7/x1sbaSjftvq724s3kkoL79/HqsaH8+PPnoZHZQCvy3MzcV0T/iznx1MT5yKb9nmDmmIjealn6uI37sYHkjX3XLxXYNyD+lE38pGv6vpf7tov33cb41Lj+kkn8qnT9mln5x6X8pGr+k0z40LLXLRHr20a8AAAXHUlEQVR4nO2dC1viutPAKTYBLW1BxZWCqICIF7zg4nXPX7//p3pz6WWSTEqp1+6+8zznPCtt0/wyyWQymUBt4xNlPD7m0oqFMhH/4B+Ox+PPfHXtE8occxTHT8XRBVzikONPqMOHco1THgPFLuJ+hjf+yJp8GBdDctYEMvGY7j6oOh/CJZFKExlw4w+o03u5xh/GBOFa79bbu7iOWx/NlLE5rfH3cB07n8SUor1HbSW5PhsqZSuLVoaLd78vgErRxl/CdfyFUAnZ+kpbk2u8hqqocJyksMpFh0J8/icRH7LrxdE+k4uNqkI8HMg/fDxf3j//d3E36zVV6dVm/3v5/Xy/PH8UmEX41u2Oa3AVoOJaiLbOr55fZqz+jUajx6SGCP+cXWY3ze6er863IqHUFWjrkBXmWjWseMUezq8vZo0mx8FgcOGAzcbsv/vXQ8JU90FkBbnyqXi3e72/YNVbB0jDY3S9i6tHP1dxhckKceX2wBaNXq+fWK8rjQThms2761eftt5LVoCL2UC7osjD8oVZgg9gAmyNl+WDXW2FbONqLisVg9q6nn2InhC22fUWsZD5/ur5bBWXdWC16NZ1rdn4eCaAdv9gUdpqla3gsiiLWfPlU/MTFKVKo3m36eNoq1SWy3WMU7Xo4+9P6X6mMCv5jPdH3xmX5cKVRenmF6gKoDXv/qD2MVdlOVyocaf+VeNrVAXJaksH0VneKLNyjXGq+8bnmYocafRQMntftHFhffDbqARZbYn0RmtftHAhWC2y7H0blST7Y1oQW1/EuZChRV5n30rFpTl7JAXBUC6kCx5efKUNtEmv+Tsyh1lBLtNiULL8CVRceo1NU2WFuBCsw6fmd/Nk0nw51FXmj1dzmVg/R1lSek1DZSaYzmVgUf/iBylLSvPCpyvAdC4D67H2o5QlpVd71MHyuZA++N0MuDSXel/M49Kx6PMPxWJgz7r1sHMZXsbLt0/Fdmm8aD2R2ri05RaNnn7g0Mqk96RaD8XzAFxjHesnWgwovZnqfEAnGHBpWIc/HYubRXWK9jGuVuWwTDDH5NIGlz+rABYHi/CemHJpvfBnm4xMek+qOsYal9YLL36wgVel94L2xBrWC8n9j52OTWk8Q88j6Ykxl6qt1wphMc9jE2rMh1yqug4rhcXAHgBYPDvXTKNBqmIzEuk9mQqrGeqiV5WxGYk0rg2F1Qx1PVSsF3JpbkGwhEtV10vFeiGX3hOwiUJhNc0Y0vMKqovbRDgBSy7Fj6ez765iOelBy3EsuCAp3aykupjpuAIjrCW4oLpIRdXFwACGz7lgN6yYpwGlscz6HeuINSWoQapoDKUok3OLcUFrWDUPCooyhzEuoK7WsnKuRiY94HT4GzVleF1UthtyAVzjmuJsVBqr+QAMB+SiWxUeXswignVYqwZmZbpZ4eHFBtizjeu+2lwvNq7nSo+v2gw49QpXtc1hrfG3clEL19/aD6u6SJEC7aHCxf6qsMJ6YF7WuOjhHU/mr6Q0Z48tGxdbqDycb1ZS/myp+bI1PfcNHJaplqgYBtdfIv/PVS35d7hyBmNyGXnAWkTOuyklQrC78qxCkeJ1LkIHw91Yhp2B72k1Jp39ySiCO4RkMJqMzrLMW+pFHVCCYzllQonTH9105/Pt9uXulKh3EZLVQkjfSV9J6FlWw35E8PJVLkovb10o4ekEQpDOCfvMdbsZRbQnPtmZxh95wwOlhGBPKSGF73Tr7MEwDNh/rru4GWQtaNSCF3ND4/e168qFk3bfQ8hULv/EDeqKBK57lLYI7cSX3dPko+gtFJ+Eocx98dpICW09KdfbPXFD5abQnU+JtRbpK+kgCNXP2ZO/hl4+F9kJjfJYiSdpterJ+9xLWQkyT54Id3jhdN9FSgjdEXwzjXaQiofuflzmHlaLuntDYA0gmjvX8yxVf76DVYo9dytjO0qlRUF0mn3inrGPKFoAr1QGRvp1tOJxY9E+Xgv+SjrBr4ULvUdALnKDv68e7nmqclgd+lQjDSfU2jLs/knSy9LOjNzEC7XWwh1Qcmp5NFjkce1YXzjkj3m/suvuiH9CjrI6hG3i0JGNS6qTYw2st9TDLuHd0FILt0Ppm/1RrwRXIBSmcO0bXKxS+PCSRZzGCru1vYTd8+blcTGTa382abdVXIFShOuv5mrncsUvJl1LL5P35HAFJ6xh7FxC16u53NPTOqgj6wMluJRahEfsxfTMDs6rnsMlxoJySb0vKKIvt+MRDwwWMZzW5HJvFyH4M9hhXJ5Radgv3CPb+GKzlDA8sEPVF3VogaQlW8Ul+l1Wa27s1uRydz2PQM43YhiNwA0XiyCZooM6f6vCxT0S7pTctgeim2WXgh3P86YHoEa7Rbh4uiKYScpw8SI8YLRdotzPP9nr+J7n9G/cMGCM9QHVuMJ9P+Lie7HPAy6Jbh2B9+0X5spm3RL9UG8azuWdwD7GvBA5u5Po6KT+60g6DZDL1Q8falyOl01ooumLce1mXP2SXMAhqRPlL9ZxMgsm1ivxP1UudTGic5HttAJyRl05vlhxBPRe0TgluIbpB2wCAw2VzaT6Qkrph0fTAZMpTVrA0NcCmLoCXOHNdLp7kLXFZRkuVlsPFNkm5BIMLz7Nsi7oD0dMhmfpOk2xG6FcjLzdOOb48ljxoKFcJXvNNn/xAtO/grq4vh5X2J4OOsA1Z/YKTsoB9/9ptJ0usOYdz+RKHz7R9RUs+oPBBJR3WmheViSUKl5z/lKahr1YazjWBeg0BM+7O5FuDwFYW7PzfF0H13CqOSzEJZp2fS6tYmw8eNp0AwdwXaw2rFz10NO4dHGcdbnq4Zy8lyu41QsYUmOlFZ7a/ShhhuxcqjUsvE4p4s/ncsmJ4kDlMlY1QokWLj+Py9WWKQW55LLwHVxhR8w2aj80uQKmMJxLuMRWLs2Zz+EK1VFZD6P3cMVTsDI1TSiyuma9zWI3xMrWwhUcGIEb2/zVHgz6cLbh5qs8l5xElcVXuM3cxRO9nmxyVbmk3+smMR1bh9Kx8v0NMK6DX+/hqodidFDYUmy9xAyHVlE+yUGut+42k24agrQtpScF+6G0Pt4cgPjrcgVwcmqLKNwQXOYqoIMDdZJjZk3xD6eejHQnVVRVCXq1fjI0lwv6PcygQS7pPcPYkcG1cODCVEztEVRnwKZhSga7o1PFmqh+ryawCfbpbfby7WL2EOHqUGimpdeqfKJxMdvmg7/eHO1+1rX5woR1dxAbYK2ncPna/oKyPva60Esjxbk8GPDQRjQrlniK23SjcxFoF0QMUo1rBvUR72ReG1RPtYfBfCSlTw274faV1bg7LeJHiYaC3rKISrah5Xfn7QNlOcVmfJ0LPiDWBJFqV1xWSHsBnNeFNn8F6f7CjW7nmWphVCFYFNEXs/NnnRtYidDRo55BqFgnBq5zKXZCBNqMMFsAR7/oyzZ/44AaXGQBn1VcjqLzcrBntrZawQVxdC7VfonZM68I6W1Z42w3xOBSQt5KQKqgHxUHOOah/YZLanKp6hEKs+wcxI/kxXsDqnOp0UjFmSrIFbyJbYacqGbIS9C5VI9dzHkeuheVVjUvjj2gGpej7EMEt56Fy66OODjnta3+ulgnwBEoeq4HXxyKHSx/YWs9uXYEoRjtsrrvIMbzrtJuFi7FzdHeGD9CDvBb4hugfgSFojA5l9NogZcR7oh+ZNvj4pYc6ke4GOrK1MY1tZU4T56g/gF2j5t0bbCvJz0MqOF4YFP/FC1jJx72FtPCDRO9zMJbe2ITEJh67kmjXMzdw3dRj7KGYJOYsS0HtlkzsxAeEE3D8e4gh710dZUF7lFSK3KJgomhEGUhMtlIJOv57sCaf0hERBm+jtn7+UBxUbz+DryJzZxdsOFP9uR7wno6/8facU8y35RE7RCgsbfsgZew5g3NtpObtEPZqkGywc1bMv5E8aT0PL2z7glMcziZT6Z6ggQl08vT5I76fF9NY2AuPv98nm34svbn0oZxW0r80XaYFHJwNFBeotWCu/zb/Vj9/V/870UGQfri3oO+Nc4mX6gJnnND6KAzHKJpIYR2docR/Jg4nd2Oo6+Q2JsGHR4S7ftGIUYtsjuoNx12lGag3mB3ONWSOErnR+Wk8ZifW+5cnWpke2rVJ/9Q3hfrBJ6f7TihV9GkJHaFRhFBH4yv2b6Rl10m4tEVteWZYuzO6ZTd6+FjJBaDi9LRHh/Q9e0hkndEyWiPrx1OL/WkJ+p12guRsHRzZgwlr98V104nRmIMFzK9+SXtB5JKBd5N+5PuTpweFd7utfcH1pbSubxhsmkbur8G+lvIWZy6xCzzkVIkzw0Kk0vbau3BNTccGSExh95kj15awNi6cjRnc0M2AQR8Dnrrdij6hMblwTkxcIfqM2wSBAvoA5C7Q/shDMq9wcWrmqsFM4ri69CFcffQapKpMuHBee12gn2jqjYva3EyZQp3iOJl1sOTrGpT1QmRO+Cx+FoqyKUKpi1+UlcUvjjqolBx6wf75ohRuXTXLPgFXmK4j1kQyAhwZj6TuWhTNxZVl7yuLQ9lCRM7lXzkYJpr59UAhngCJA9ouzqgCkg4NK08kp4WKCfc9SZJdqVScH8vd40tngn1xlD1ZayMgqzd9T5azzxoz4hH14N54r8ZbSWiGGmtTWxX+UooOr3NV1YMFtn9DSzLLgukYsuHUK6YsBS1JKRJkGUkGLbImk/ZyqJnhguMCuj4JtfEbJm0t6OxDRm0Q6PySUdEm2Oe9QKzWLmsjqs0sCYr6u/LyWczu0w6wIzhDQrDnkv2e/Hsz8w2mIMWrg9phOW9ohJe2rmQHLqkU/hoYbJDoRGJeGsIzyDNbINncgU7KVdekEd/37Z1nYJyyWb38GBKKNesKFc7hwt07zyu3KCc/lROnoOVSw3cZmVJ56AEV6qwPC5rvCWnLmtx0cgShRqV1VdqVvK48sKw5vuO1ueydfM4RbMMlwjt5nPZE84x0dyUIlweHiBKdz/LcCUKy+Gyq4uf/bA7bkW5CGri40Ti0lzxHr6dyza6mJ972u1uHyj+fa6/gXGFR56tO6SaL8WV5OTbudDoc+DuDSnfdPaczjwlC3P9QzQHPLBErsEefDkumWli54K72Vmpt510TUK9aVccSXLdbePb9ldy2SZ86AuV4pKujJUL7YbhjrKGpCSadLfb+0j0YDWXBesAxGfLcYmdQDsXciREm3slGh7iKMkVnoAQRkkuMf1ZudDBjvy4g0XKcQW3MDJTlosrzMqFrOmSZCLHAUcsP5IreFMariwXn0Ts/RB5LlmCE3K2O+GyP+pYgpJluPRTZKW5WE2xpTbnQtaqyTKbTLsiB1ZYQte97Q4RshJc4S8tuFmeK9xBlm6SC8nhkx4KmRhHMxcjg2x9ruBEj9e9Q1/6KdCMyzSHcW7TDWIn3dPcc4iFuOIMx4/hwkRyGbEFMS3YyguD6Xp+FMI1+hIuI9YiHUrrqbc3NVOvTD80ovZfwyUnZVtxmkNfwm7AbfSv7IecKyczRh0fZey8PsK+iIv3wzy3TEleLjcvf9j8hZZusYeLfH2pGYjluNQhtjaXsdpVSxdcZqRIngzI4dp/L5eWTrsuV3jp5WTOxVymYsS8bM2eystnK+7PK4nd63K5Q5IXQZP+oRn/licq7U8qq5iy6y+4lbk+F7XEWWX9pD9vfi4n5l1bxN6ep4dy2cIAWZy/BFdeyDNef5kTsLTDpLOwka3FZVFikBnFElx5fSNep5hhG6kwnpOwwx36d3GFE88WZlskbn0ZrrxxsmNzBJO9Z5ENMjKeO1mDi8cPLQme6b55GS58cwlwOQTbfAJ77t6RdoMSoS/AZT9Mc1ou3ivHiTUzO+HCeqrbTdM1PP063N4tFMemtq/MiPtFOS7r96IkcVHUUwnrk0icxfGM1l5rXhZc1m9BkUvYclyObyk1ic+bp8Nkwe7J/OayfWLO29b8edt+iuUN8lRYaS6iDxCNy9qcQWjuO3Cx5Yva97/yg+wluRw/n8uh1ox0TJThVXC/0sO/0in2ycpyWRKUMy7LDINLzveK2PdhbcZLdMSyXJZjhdn+srU5safK7C/n7GCXH1+2UkE+QFS8I6pZV6vzN+IoDZJnIatvaY8knyJfX+jXg4H5tfiqFGzvGFzYTlpSB4vfI09HIXk6SYNgC9zMZUYVBg1A4UyHQDs4qnAh4zRdXONvEN8cgLZqmgOFlAkOCCBf4OXCL3Sx7W3rz6i9UMtnM61D7EKLN6AJUvIYERKCXSQndYyvVIMBFmyOUjOdvCIac0d67E/NPzTqAHOwHHM6kcfCsIHpJulK5vEgF2YymeNWj0+S4crULxNL+x5pI1gCcwGRJKxkECHTQFp3Y/ZVvrDF3Dcx4sk0Qs8wpRIGnfx9WHPCUM+n04HmvaTfDmEMPhBiNHKG1TPvROuJ4amR30u9/cC+WnP3sNx1Pc9cOXPmztWGoNM3y2Wvq7zYhUk93rabU6ZmGcI6ttdK/MsA7Y3MCUa+hNPk4mfOkucDt63rlzrbWc6EC8cePNIVuvvKu8CRscA1vinDYSuOML18YNlCJs7+gasenxJnuLA9PYSLvWX0K06K2OsjLeH15/Fl7VgYmXZDfsV1g7aed+B1duKHTjtImWS67cpHT0bYd7tKoV402V7Isw7i/4vuru1LdNHvJfYGo8ujyW6Ev4IVvzs5OtqNzLNNznBydLmPHUCg3pSVeTnSTzOlj/rDfXb5zE4V3+dFZ7uj0WR/NDyznqCxcInN9rwjLeL0C14/aj8LI8q0F7rislK5Iqer/qFzUn+F/Dtceb818HNlBRd1HraqKTl5lcyX+92srLzAXyvWuJ4q/ENZveahhetv/R0f+rvCP+NT+/d+/6tVcX3VbFzV+wVwKL2LbHypv6/3WGm7AX/5tqXGNyr7K8VcoJ1vKb83WsGfos8EdkP/WPl9WMevsOGAv+frj5Xf83XosrIjrAFnZZ//rjTgcshdZTUG9dPSfgfccaKKcjUfobr474ArP5hdVVvfXCrLFPF79MovMDut8wqCNa9hDIypi3OpCquiV69iMashuVSFOaRqGmveq1jHMdeGFuNoPTYqZD16zU01ENvaSLg2tE1MGt1VxvFozB5UtfgbGdex/rW+9KpZCZX1ms/aaRnRCxOujZYB9vBSgVHWmD1qmwF+awNy6UOMhxHPaz+8MzaaV1Svd4yVcm3oXJxsWfvBBqTRvEY2Kjd0LgTMadHNp585znrN3hW2A7hhcmFgTGePF82fprReo/lyjn0ZVoYFuTYc3XhIsmh594PQGNTs6gHb/kpMhsFlWsW4O5LDzYtGs/f9bAzq6X4L31RUsFQucx7LtOa/Xj81v1FvPa6o5z+HyN6JxDresHOxxZiNjO8fRa9XF71m46vhOFLz7poxtWy7r74z3sjjsvbFlI0evt5fzJqc7tPxGBAj6r1c/3nA9rgAVkvHMLg2jlHzocIR5+F1+fwy63E+BvihhD2Ow3gatbvnq/OtaOWGuqEslIuPshVkgq7F8PzDrdfl/fPL/zihYBSUQgpDCBGP8jJ6s7uL5/vl+eMD/52t1uocAV8bWXYu3hkLkCXKk/ugfvTw+Lq5vLq/fv7938XL3dOs1lixE8fG6ezp6eXi4vfz9f3VcvP18eHQlyUW4EmojC6Yw7UOmcLYaslKgY1fPzrMJPKlONyZ4UKS+8ST677RRmXnKjDOvl18B+uBq7gYWRmlfZUwVdmp8rmk0n4imp+nqiJcPxGNQ41X1Xo1F0dr/RQ2f0X3W48rZftOOP721mpFrcvFZSzhvppOzAzFkdbnSuAk3efjybe01kQqyZXipXwfi5gWyXiOx+sTvZMLAnLEjDGTwgyAhdOUx/lALlXGTI6ltDgtFOkuQZE38mfGH1yP/wP6DJm2c+xlGgAAAABJRU5ErkJggg==" alt="">
                </div>
                <h1 class="t-white poppins">Burger King</h1>
                <p class="t-white poppins">A simple landing page using HTML and CSS. This webiste is for burger shop who
                    provides all the information of thir services at this landing page.</p>
                <div class="buttons flex s-around">
                    <a href="#" target="_blanks"
                        class="btn mx-1 m-top">GitHub</a>
                    <a href="#" target="_blanks" class="btn m-top live">Live
                        Link</a>
                </div>
            </div>
            <div class="projects-item flex f-col s-center items-center">
                <div class="image-container p-two">
                    <img src="./Images/MBA.png" alt="">
                </div>

                <h1 class="t-white poppins">MBA Chai Wala</h1>
                <p class="t-white poppins">Lorem ipsum dolor sit amet consectetur adipisicing elit. Hic obcaecati cum
                    nemo
                    recusandae voluptas ipsum.s</sp>
                <div class="buttons flex s-around">
                    <a href="#" target="_blank"
                        class="btn mx-1 m-top">GitHub</a>
                    <a href="#" target="_blank"
                        class="btn m-top live">Live Link</a>
                </div>
            </div>
            <div class="projects-item flex f-col s-center items-center">
                <div class="image-container p-three">
                    <img src="./Images/magicNotes.png" alt="">
                </div>

                <h1 class="t-white poppins">Magic Notes App</h1>
                <p class="t-white poppins">Lorem ipsum dolor sit amet consectetur adipisicing elit. Hic obcaecati cum
                    nemo
                    recusandae voluptas ipsum.s</p>
                <div class="buttons flex s-around">
                    <a href="#" target="_blank"
                        class="btn mx-1 m-top">GitHub</a>
                    <a href="#" target="_blank" class="btn m-top live">Live
                        Link</a>
                </div>
            </div>
            <div class="projects-item flex f-col s-center items-center">
                <div class="image-container p-three">
                    <img src="./Images/login.png" alt="">
                </div>

                <h1 class="t-white poppins">Login Form</h1>
                <p class="t-white poppins">Lorem ipsum dolor sit amet consectetur adipisicing elit. Hic obcaecati cum
                    nemo
                    recusandae voluptas ipsum.s</p>
                <div class="buttons flex s-around">
                    <a href="#" target="_blank"
                        class="btn mx-1 m-top">GitHub</a>
                    <a href="#" target="_blank" class="btn m-top live">Live
                        Link</a>
                </div>
            </div>

        </div>
    </section>

    <!-- Contact Me Section -->
    <section id="contact" class="m-b-1">
        <h1 class=" t-center my-2 t-white f-2">Contact Me</h1>
        <div class="contact-container flex s-around items-centers">
            <div class="form" id="contactForm">
                <form action="" id="contactFrom">
                    <div class="name form-div">
                        <input type="text" name="name" id="name" class="poppins" placeholder="Enter Your Name">
                    </div>
                    <div class="email form-div">
                        <input type="email" name="email" id="email" class="poppins" placeholder="Enter Your Email"
                            required>
                    </div>
                    <div class="phone form-div">
                        <input type="phone" name="phone" id="phone" class="poppins" placeholder="Enter Your Phone"
                            required>
                    </div>
                    <div class="textarea form-div">
                        <textarea name="text" id="textarea" cols="30" rows="10" class="poppins"
                            placeholder="Enter Messages"></textarea>
                    </div>
                    <button type="submit" class="btn poppins" id="submit">Send</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer id="footer">
        <ul class="flex s-center w-80 m-auto my-2 res">
            <li><a href="#home" class="poppinss">Home</a></li>
            <li><a href="#about" class="poppinss">About</a></li>
            <li><a href="#skills" class="poppinss">Skills</a></li>
            <li><a href="#projects" class="poppinss">Projects</a></li>
            <li><a href="#portfolio" class="poppinss">Portfolio</a></li>
        </ul>
        <ul class="flex s-center w-80 font-awesome ">
            <a href="https://in.linkedin.com/in/raju-sheoran-b220781b8" target="_blank">
                <li><i class="fa-brands fa-linkedin-in"></i></li>
            </a>
            <a href="https://github.com/rajusheoran4" target="_blank">
                <li><i class="fa-brands fa-github"></i></li>
            </a>
            <a href="https://www.instagram.com/raju_webdev" target="_blank">
                <li><i class="fa-brands fa-instagram"></i></li>
            </a>
            <a href="https://www.youtube.com/channel/UC6ScgVJbFPpHAnRdrOSJMlg" target="_blank">
                <li><i class="fa-brands fa-youtube"></i></li>
            </a>
        </ul>
        <p class="t-center my-2 poppins">&copy; All Rights Reserved - <span class="cpy-white poppins">Raju
                Sheoran</span></p>

    </footer>

    <div id="scroll-top" onclick="scrolltop()">
        <span><i class="fa-solid fa-arrow-up"></i></span>
    </div>

</body>
<script src="/script.js"></script>

</html>
