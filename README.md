# Web Design using Bootstrap Framework

## AIM:
To design a website using bootstrap framework.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using bootstrap grid system.

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
## Home page:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap Website</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
<link href="./vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">
  <link href="./vendor/bootstrap-icons/bootstrap-icons.css" rel="stylesheet">
  <link href="./vendor/boxicons/css/boxicons.min.css" rel="stylesheet">
  <link href="./vendor/glightbox/css/glightbox.min.css" rel="stylesheet">
  <link href="./vendor/swiper/swiper-bundle.min.css" rel="stylesheet">
  <link href="./css/style.css" rel="stylesheet">
<style>
    .nav-tabs
 {
   border-color:rgb(140, 12, 199);
   width:40%;
 }

.nav-tabs > li a { 
    border: 1px solid #68034f;
    background-color:#d273e6; 
    color:#fff;
    }

.nav-tabs > li.active > a,
.nav-tabs > li.active > a:focus,
.nav-tabs > li.active > a:hover{
    background-color:#D6E6F3;
    color:#000;
    border: 1px solid #b05fe6;
    border-bottom-color: transparent;
    }

.nav-tabs > li > a:hover{
  background-color: #1ab8bb !important;
    border-radius: 5px;
    color:#000;

} 
.btn:hover {
  background-color: RoyalBlue;
}
</style>
</head>
<body>
    <div class="container">
        <div class="row">
            <img src="./police.png"   style="height:300px;"  alt="police">
            <nav class="navbar navbar-expand-sm bg-light navbar-light">
                <div class="container">

                    <button class="btn"><i class="fa fa-twitter" style="font-size:36px"></i></button>
                    <button class="btn"><i class="fa fa-youtube-play" style="font-size:36px"></i></button>
                    <button class="btn"><i class="fa fa-instagram" style="font-size:36px"></i></button>
                    <button class="btn"><i class="fa fa-envelope" style="font-size:36px"></i></button>
                    



                
                    <form class=" d-flex">
                        <input class="form-control me-2" type="text" placeholder="Search" style="width: 500px; height: 40px">
                        <button class="btn btn-primary " type="button" style="width: 200px; height: 40px">Search</button>
                      </form>
                </div>
              </nav>
            <div class="col-sm-2 h2  bg-warning "><a href="/static/pageone.html">HOME</a></div>
            <div class="col-sm-2 h2  bg-warning"><a href="/static/pagetwo.html">ABOUT US</a></div>
            <div class="col-sm-2 h2  bg-warning bg-gradient"><a href="/static/pagethree.html">GALLERY</a></div>
            <div class="col-sm-2 h2  bg-warning bg-gradient"><a href="/static/pagefour.html">TRAINING</a></div>
            <div class="col-sm-2 h2  bg-warning bg-gradient"><a href="/static/pagefive.html">ADMIN</a></div>
            <div class="col-sm-2 h2  bg-warning bg-gradient"><a href="/static/contactus.html">CONTACT US</a></div>
        <div class="container">
        <!-- ======= What's New ======= -->
    <section id="featured-services" class="featured-services section-bg">
        <div class="container" style="padding-top: 30px;">
          <h3 class="bi bi-laptop" style="text-align: center;">What's New</h3>
          <div class="row no-gutters" style="padding-top: 30px;">
            <div class="col-lg-4 col-md-6">
              <div class="icon-box">
                <h4 class="title"><a href="">Internship - 17/01 to 28/02 2022</a></h4>
                <p class="description">Invitation of application for the paid Internship Programme at BPR&D for the year 2022-23</p>
              </div>
            </div>
            <div class="col-lg-4 col-md-6">
              <div class="icon-box">
                <h4 class="title"><a href="">Bureau Darpan - 05/0/ to 31/03 2022</a></h4>
                <p class="description">	Directory of Prison Officials in India 2021</p>
              </div>
            </div>
            <div class="col-lg-4 col-md-6">
              <div class="icon-box">
                <h4 class="title"><a href="">Webinar - 04/01/2022 to 31/12/2024</a></h4>
                <p class="description">Proceedings of the Webinar on Woman Safety with Sensitivity</p>
              </div>
            </div>
            <p style="text-align: center;"><a href="">View Old Announcement Here</a></p>
          </div>
  
        </div>
      </section><!-- End What's New Section -->
      <!-- ======= News & Events Section ======= -->
    <section id="why-us" class="why-us">
        <div class="container">
  
          <div class="row no-gutters">
            <h2 class="bi bi-chevron-right" style="text-align: center; padding-top: 20px;">News & Events</h2>
            <div class="col-lg-4 col-md-6 content-item">
              <span>01</span>
              <h4>Internship</h4>
              <p>Invitation of application for the paid Internship Programme at BPR&D for the year 2022-23. Last date: 28/02/2022</p>
              <p><a href="https://bprd.nic.in/WriteReadData/News/Internship.pdf">Apply Here</a></p>
            </div>
  
            <div class="col-lg-4 col-md-6 content-item">
              <span>02</span>
              <h4>Bureau Darpan</h4>
              <p>From : 05/01/2022 To: 31/03/2022</p>
              <p><a href="https://bprd.nic.in/WriteReadData/News/BureauDarpan.pdf">View PDF here</a></p>
            </div>
  
            <div class="col-lg-4 col-md-6 content-item">
              <span>03</span>
              <h4>Adv of PGVPant 2021-22</h4>
              <p>	पंडित गोविंद वल्लभ पंत पुरस्कार योजना वर्ष 2021-22 का विज्ञापन।. From : 18/11/2021 To: 31/03/2022</p>
              <p><a href="https://bprd.nic.in/WriteReadData/News/Adv%20of%20PGVPant%202021-22.pdf">View PDF here</a></p>
            </div>
  
            <div class="col-lg-4 col-md-6 content-item">
              <span>04</span>
              <h4>Police Aur Seva</h4>
              <p>Do Visit our Ploice Aur Seva Channel on YouTube</p>
              <p><a href="https://www.youtube.com/channel/UCGhrg_cnnGuhwXfCU16kYow/videos">See the channel here</a></p>
            </div>
  
            <div class="col-lg-4 col-md-6 content-item">
              <span>05</span>
              <h4>Yoga at Workplace</h4>
              <p>Why is yoga good for you?Yoga improves strength, balance and flexibility.Slow movements and deep breathing increase blood flow and warm up muscles, while holding a pose can build strength.</p>
              <p><a href="https://bprd.nic.in/WhatsNews_Description.aspx?News_id=10308">Watch the video here</a></p>
            </div>
  
            <div class="col-lg-4 col-md-6 content-item">
              <span>06</span>
              <h4>Cyber Cases Manual</h4>
              <p>Investigative Workflow Manual on Cyber Harassment Cases</p>
              <p><a href="https://bprd.nic.in/WriteReadData/News/BPRD%20Cyber%20harassment%20cases%206-3-21.pdf">See the PDF here</a></p>
            </div>
  
          </div>
        </div>
  
        </div>
      </section><!-- End News & Events Section -->
    </div>
    <div class="copyright">
        &copy; Copyright <strong><span>BPRD</span></strong>. All Rights Reserved
      </div>
      <div class="credits">
        Designed by <a href="https://bootstrapmade.com/">Praneet</a>
      </div>
    </div>
  </footer><!-- End Footer -->
            </div>
        </body>
</html>
~~~
## About us:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap Website</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
<link href="./vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">
  <link href="./vendor/bootstrap-icons/bootstrap-icons.css" rel="stylesheet">
  <link href="./vendor/boxicons/css/boxicons.min.css" rel="stylesheet">
  <link href="./vendor/glightbox/css/glightbox.min.css" rel="stylesheet">
  <link href="./vendor/swiper/swiper-bundle.min.css" rel="stylesheet">
  <link href="./css/style.css" rel="stylesheet">
<style>
    .nav-tabs
 {
   border-color:rgb(140, 12, 199);
   width:40%;
 }

.nav-tabs > li a { 
    border: 1px solid #68034f;
    background-color:#d273e6; 
    color:#fff;
    }

.nav-tabs > li.active > a,
.nav-tabs > li.active > a:focus,
.nav-tabs > li.active > a:hover{
    background-color:#D6E6F3;
    color:#000;
    border: 1px solid #b05fe6;
    border-bottom-color: transparent;
    }

.nav-tabs > li > a:hover{
  background-color: #1ab8bb !important;
    border-radius: 5px;
    color:#000;

} 
.btn:hover {
  background-color: RoyalBlue;
}
</style>
</head>
<body>
    <div class="container">
        <div class="row">
            <img src="./police.png"   style="height:300px;"  alt="police">
            <nav class="navbar navbar-expand-sm bg-light navbar-light">
                <div class="container">

                    <button class="btn"><i class="fa fa-twitter" style="font-size:36px"></i></button>
                    <button class="btn"><i class="fa fa-youtube-play" style="font-size:36px"></i></button>
                    <button class="btn"><i class="fa fa-instagram" style="font-size:36px"></i></button>
                    <button class="btn"><i class="fa fa-envelope" style="font-size:36px"></i></button>
                    



                
                    <form class=" d-flex">
                        <input class="form-control me-2" type="text" placeholder="Search" style="width: 500px; height: 40px">
                        <button class="btn btn-primary " type="button" style="width: 200px; height: 40px">Search</button>
                      </form>
                </div>
              </nav>
            <div class="col-sm-2 h2  bg-warning "><a href="/static/pageone.html">HOME</a></div>
            <div class="col-sm-2 h2  bg-warning"><a href="/static/pagetwo.html">ABOUT US</a></div>
            <div class="col-sm-2 h2  bg-warning bg-gradient"><a href="/static/pagethree.html">GALLERY</a></div>
            <div class="col-sm-2 h2  bg-warning bg-gradient"><a href="/static/pagefour.html">TRAINING</a></div>
            <div class="col-sm-2 h2  bg-warning bg-gradient"><a href="/static/pagefive.html">ADMIN</a></div>
            <div class="col-sm-2 h2  bg-warning bg-gradient"><a href="/static/contactus.html">CONTACT US</a></div>
            <div class="bg-warning">
            <!-- ======= Top Bar ======= -->
  
        <div class="col-lg-9 pt-4 pt-lg-0 order-2 order-lg-1 content">
          <h3>Evolution of BPRD</h3>
          <p class="fst-italic">
              <dl>
                <dt>CREATION</dt>
                <br>1.The Government of India vied Resolution No.8/136/68-P.I (Pers.I) dated 28.08.1970 formally established the Bureau of Police Research and Development (BPR&D), under the Ministry of Home Affairs giving a new orientation to then existing Police Research and Advisory Council (1966) for the following reasons and with the primary objective of modernization of police force:
                <dd>1.1. To take direct and active interest in the issues</dd>
                <dd>1.2. To promote a speedy and systematic study of the police problems,</dd>
                <dd>1.3. To apply science and technology in the methods and techniques used by police.</dd>
                In addition and as a secondary, the Resolution mandated an advisory role also for the Bureau.<br>
                2. The Bureau was established with the following two divisions initially with a well laid out charter of duties
                <dd>2.1. Research, Statistics and Publication</dd>
                <dd>2.2. Development</dd>
                <dd>2.3. Training is a vital and growing requirement to improve the competency of police forces in the country. The Gore-Committee (1971) set up by the Government of India studied the training aspects of police and gave several recommendations. The government of India in accepting its recommendations created a Training Division (1973) in addition to the two divisions already existing to function under the Bureau.</dd>
                <dd>2.4. The forensic science services uncompromising & Geese under the Development Division grew over a period and a separate Directorate of Forensic Sciences under the BPR&D came into existence in 1983.</dd>
                <dd>2.5. Further in 1995 Government of India decided to entrust issues relating to Correctional Administration Work to the BPR&D so that problems relating to prisons and implementation of deemed prison reforms can be taken up by the Bureau in a cohesive manner. This set up is operating out of the existing manpower resources.</dd>
                <dd>2.6. During the year 2008, the Government of India further decided to create National Police Mission under the administrative control of BPR&D to transform the police forces in the country into effective instrument for maintenance of internal security and facing the challenges in future, by equipping them with the necessary material, intellectual and organizational resources.</dd>
                <dt>SEPARATION</dt>
                <br>1.Though the Institute of Criminology and Forensic Science (ICFS) was established under the overall supervision and guidance of BPR&D as part of the same exercise, it was allowed to function as a separate entity in 1976; since the ultimate objective of setting up the Institute was to develop a full-fledged academic institution for furthering studies in Criminology and forensic science. The same which has been re-christened in the year 1991 is now functioning as Lok Nayak Jai Prakash Narayan (LNJN), National Institute of Criminology and Forensic Science from 1982. The institute provides training courses for officers of the criminal justice system in the two subjects i.e. Criminology and Forensic Science and carries out research.
                <dd>2. Growth dynamics took over and the need to specialize in each area arose. The National Police Commission (1977) also recommended certain measures requiring implementation. Simultaneously, technological innovations particularly computers held promises of support to many areas of crime control and crime detection besides processing statistical data for the purpose of analysis. The Government of India, therefore, decided to establish a National Crime Records Bureau in 1986 build another Resolution and entrusted statistics and publications work of the Research Division to the newly constituted Bureau along with the plans for their computerization.</dd>
                <dd>3. In an identical move brought about by compulsions of growth, the Government of India decided to give an independent status to the Forensic Science Division by creating a Forensic Science Directorate having an autonomous status under the direct control of the Ministry of Home Affairs.</dd>
              </dl>
          </p>
        </div>
      </div>
    </div>
  </section><!-- End About Us Section -->

  <!-- ======= Footer ======= -->
  <footer id="footer">
      <div class="copyright">
        &copy; Copyright <strong><span>BPRD</span></strong>. All Rights Reserved
      </div>
      <div class="credits">
        Designed by <a href="https://bootstrapmade.com/">Praneet</a>
      </div>
    </div>
  </footer><!-- End Footer -->
            </div>
        </body>
</html>
~~~
## Contact us:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap Website</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
<link href="./vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">
  <link href="./vendor/bootstrap-icons/bootstrap-icons.css" rel="stylesheet">
  <link href="./vendor/boxicons/css/boxicons.min.css" rel="stylesheet">
  <link href="./vendor/glightbox/css/glightbox.min.css" rel="stylesheet">
  <link href="./vendor/swiper/swiper-bundle.min.css" rel="stylesheet">
  <link href="./css/style.css" rel="stylesheet">
<style>
    .nav-tabs
 {
   border-color:rgb(140, 12, 199);
   width:40%;
 }

.nav-tabs > li a { 
    border: 1px solid #68034f;
    background-color:#d273e6; 
    color:#fff;
    }

.nav-tabs > li.active > a,
.nav-tabs > li.active > a:focus,
.nav-tabs > li.active > a:hover{
    background-color:#D6E6F3;
    color:#000;
    border: 1px solid #b05fe6;
    border-bottom-color: transparent;
    }

.nav-tabs > li > a:hover{
  background-color: #1ab8bb !important;
    border-radius: 5px;
    color:#000;

} 
.btn:hover {
  background-color: RoyalBlue;
}
</style>
</head>
<body>
    <div class="container">
        <div class="row">
            <img src="./police.png"   style="height:300px;"  alt="police">
            <nav class="navbar navbar-expand-sm bg-light navbar-light">
                <div class="container">

                    <button class="btn"><i class="fa fa-twitter" style="font-size:36px"></i></button>
                    <button class="btn"><i class="fa fa-youtube-play" style="font-size:36px"></i></button>
                    <button class="btn"><i class="fa fa-instagram" style="font-size:36px"></i></button>
                    <button class="btn"><i class="fa fa-envelope" style="font-size:36px"></i></button>
                    



                
                    <form class=" d-flex">
                        <input class="form-control me-2" type="text" placeholder="Search" style="width: 500px; height: 40px">
                        <button class="btn btn-primary " type="button" style="width: 200px; height: 40px">Search</button>
                      </form>
                </div>
              </nav>
            <div class="col-sm-2 h2  bg-warning "><a href="/static/pageone.html">HOME</a></div>
            <div class="col-sm-2 h2  bg-warning"><a href="/static/pagetwo.html">ABOUT US</a></div>
            <div class="col-sm-2 h2  bg-warning bg-gradient"><a href="/static/pagethree.html">GALLERY</a></div>
            <div class="col-sm-2 h2  bg-warning bg-gradient"><a href="/static/pagefour.html">TRAINING</a></div>
            <div class="col-sm-2 h2  bg-warning bg-gradient"><a href="/static/pagefive.html">ADMIN</a></div>
            <div class="col-sm-2 h2  bg-warning bg-gradient"><a href="/static/contactus.html">CONTACT US</a></div>
            <h2 class="text-center bg-danger" >Contact Us </h2>
            <div class="h2 bg-info" style="height:1000px;">
                Address:</br>
             
                Bureau of Police Research and Development</br>
                Ministry of Home Affairs,</br>
                NH-8, Mahipalpur</br>
                New Delhi (India)</br>
                <br>
                <br>
                <br>
                <br>
                <br>
                Telefax:</br>
                DG Office: +91-11-26781312,</br>
                Email id: dg@bprd.nic.in</br>
                ADG Office: +91-11-26781341,</br> 
                Email id: adg@bprd.nic.in</br>
                Administration Directorate: +91-11-26781326,</br>
                Email id: igadm@bprd.nic.in</br>
                Training Directorate: +91-11-26782027,</br>
                Email id: dirtrg@bprd.nic.in</br>
                Research & CA Directorate: +91-11-26781314,</br> 
                Email id: dirrd@bprd.nic.in</br>
                Phone:</br>
                Administration Directorate: +919987233434</br>
                Training Directorate: +8756347690</br>
                
            
            
            </div>
            <div class="copyright">
                &copy; Copyright <strong><span>BPRD</span></strong>. All Rights Reserved
              </div>
              <div class="credits">
                Designed by <a href="https://bootstrapmade.com/">Praneet</a>
              </div>
            </div>
          </footer><!-- End Footer -->
                    </div>
                </body>
        </html>
~~~


## OUTPUT:

### Home Page:
![output](./1.png)
### About us Page:
![output](./2.png)
### Contact us Page: 
![output](./3.png)

## Result:
Thus the website is created using bootstrap
