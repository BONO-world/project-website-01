<template>
  <div class="section-container">
    <div class="section-body">
      <div class="section-header">
        <!-- Navbar -->
        <nav class="navbar navbar-dark bg-dark fixed-top">
          <div class="container-fluid">
            <div>
              <button
                class="navbar-toggler"
                type="button"
                data-bs-toggle="offcanvas"
                data-bs-target="#offcanvasDarkNavbar"
                aria-controls="offcanvasDarkNavbar"
              >
                <span class="navbar-toggler-icon"></span>
              </button>
              <a href="/">
                <img
                  src="https://image.makewebeasy.net/makeweb/0/m14BHwk4P/Home/clicknext_logo2x.png?v=202012190947"
                  alt="logo"
                  class="d-inline-block img-logo"
                />
              </a>
            </div>
            <div class="right">
              <div class="search">
                <a href="#">
                  <i class="fa-solid fa-magnifying-glass"></i>
                </a>
              </div>
              <li class="nav-item dropdown">
                <a
                  class="nav-link dropdown-toggle"
                  href="#"
                  role="button"
                  data-bs-toggle="dropdown"
                  aria-expanded="false"
                >
                  TH
                </a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">EN</a></li>
                </ul>
              </li>
            </div>
            <div
              class="offcanvas offcanvas-end text-bg-dark"
              tabindex="-1"
              id="offcanvasDarkNavbar"
              aria-labelledby="offcanvasDarkNavbarLabel"
            >
              <div class="offcanvas-header">
                <h5 class="offcanvas-title" id="offcanvasDarkNavbarLabel">
                  ClickNext Menu
                </h5>
                <button
                  type="button"
                  class="btn-close btn-close-white"
                  data-bs-dismiss="offcanvas"
                  aria-label="Close"
                ></button>
              </div>
              <div class="offcanvas-body">
                <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
                  <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#"
                      >Home</a
                    >
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Aboutus</a>
                    <a class="nav-link" href="#">Awards</a>
                    <a class="nav-link" href="#">Our Business</a>
                    <a class="nav-link" href="#">News & Activities</a>
                  </li>
                  <form class="d-flex" role="search">
                    <input
                      class="form-control me-2"
                      type="search"
                      placeholder="Search"
                      aria-label="Search"
                    />
                    <button class="btn btn-success" type="submit">
                      Search
                    </button>
                  </form>
                </ul>
              </div>
            </div>
          </div>
        </nav>
      </div>

      <div id="section-content">
        <!-- Header -->
        <div
          id="carouselExampleControls"
          class="carousel slide"
          data-bs-ride="carousel"
        >
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img
                src="../assets/clicknext-profile.png"
                class="d-block w-100 profile"
                alt="..."
              />
            </div>
            <div class="carousel-item">
              <img
                src="../assets/clicknext-profile.png"
                class="d-block w-100 profile"
                alt="..."
              />
            </div>
            <div class="carousel-item">
              <img
                src="../assets/clicknext-profile.png"
                class="d-block w-100 profile"
                alt="..."
              />
            </div>
          </div>
          <button
            class="carousel-control-prev"
            type="button"
            data-bs-target="#carouselExampleControls"
            data-bs-slide="prev"
          >
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button
            class="carousel-control-next"
            type="button"
            data-bs-target="#carouselExampleControls"
            data-bs-slide="next"
          >
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>
        <nav
          aria-label="Page navigation example"
          class="nav-bottom"
          id="main-nav-btn"
        >
          <ul class="pagination">
            <li class="page-item page-link-i">
              <a href="#" aria-label="Previous">
                <span aria-hidden="true"
                  ><i class="fa-solid fa-chevron-left"></i
                ></span>
              </a>
            </li>
            <li class="page-item .control .active-btn">
              <a class="page-link" href="#sectionTop">About us</a>
            </li>
            <li class="page-item .control">
              <a class="page-link" href="#">Awards</a>
            </li>
            <li class="page-item .control">
              <a class="page-link" href="#">Our Business</a>
            </li>
            <li class="page-item .control">
              <a class="page-link" href="#">News & Activies</a>
            </li>
            <li class="page-item page-link-i">
              <a href="#" aria-label="Next">
                <span aria-hidden="true"
                  ><i class="fa-solid fa-chevron-right"></i
                ></span>
              </a>
            </li>
          </ul>
        </nav>
        <div id="sectionTop" class="section sectionTop">
          <div class="sectiontop-left">
            <div class="heading-arcticle">
              <h2>Service</h2>
              <a
                href="https://www.clicknext.com/"
                class="seeAll"
                target="_blank"
              >
                <p class="small">ดูทั้งหมด</p>
                <div class="seeAll-buttom">
                  <i class="fa-solid fa-chevron-right"></i>
                </div>
              </a>
            </div>
            <div class="main-article">
              <a
                href="https://www.clicknext.com/softwaredevelopment"
                target="_blank"
                ><img
                  src="https://image.makewebeasy.net/makeweb/0/m14BHwk4P/Home/05__Service_03_edit_1.png?v=202012190947"
                  class="img-article-main"
                  alt=""
              /></a>
              <a
                href="https://www.clicknext.com/softwaredevelopment"
                target="_blank"
              >
                <h3>
                  บริการพัฒนาซอฟต์แวร์สำหรับองค์กรที่มุ่งเน้นให้ลูกค้าได้ชิ้นงานที่ใช้งานได้จริง
                </h3>
                <p class="small">
                  เราแตกต่าง และใส่ใจตั้งแต่ขั้นตอนการเก็บความต้องการ
                  จนถึงกระบวนการการทำงานที่ให้ลูกค้าได้เห็นพัฒนาการของชิ้นงานตั้งแต่ต้นจนจบโครงการ
                </p>
                <div class="article-tag">
                  <a href="ttps://www.clicknext.com" target="_blank"
                    ><p>Service</p></a
                  >
                </div>
              </a>
            </div>
            <div class="detail-article">
              <div class="detail-article-right">
                <a
                  href="https://www.clicknext.com/mobileappdevelopment"
                  target="_blank"
                  ><img
                    src="https://image.makewebeasy.net/makeweb/0/m14BHwk4P/Home/05__Service_04_edit_1.png?v=202012190947"
                    class="img-article-detail"
                    alt=""
                /></a>
                <a
                  href="https://www.clicknext.com/mobileappdevelopment"
                  target="_blank"
                >
                  <h3 class="second-content">
                    สร้างสรรค์นวัตกรรมผ่านสื่อแบบใหม่ที่เหนือกว่า
                    เพื่อขับเคลื่อนธุรกิจของคุณให้ก้าวไปสู่ยุคใหม่อย่างเต็มรูปแบบ
                  </h3>
                  <div class="article-tag">
                    <a href="ttps://www.clicknext.com" target="_blank"
                      ><p>Service</p></a
                    >
                  </div>
                </a>
              </div>
              <div class="detail-article-left">
                <a href="https://www.clicknext.com/interactivemedia"
                  ><img
                    src="https://image.makewebeasy.net/makeweb/0/m14BHwk4P/Home/05__Service_02_edit_1.png?v=202012190947"
                    class="img-article-detail"
                    alt=""
                    target="_blank"
                /></a>
                <a
                  href="https://www.clicknext.com/interactivemedia"
                  target="_blank"
                >
                  <h3 class="second-content">
                    สร้างโลกเสมือนด้วยภาพที่ถ่ายทำจากสถานที่จริงเสมือนอยู่สถานที่นั้นจริงๆ
                  </h3>
                  <div class="article-tag">
                    <a href="ttps://www.clicknext.com" target="_blank"
                      ><p>Service</p></a
                    >
                  </div>
                </a>
              </div>
            </div>
          </div>

          <div class="sectiontop-right">
            <div class="heading-arcticle">
              <h2>News</h2>
              <a
                href="https://blog.clicknext.com/category/all-category/clicknext-culture/"
                class="seeAll"
                target="_blank"
              >
                <p class="small">ดูทั้งหมด</p>
                <div class="seeAll-buttom">
                  <i class="fa-solid fa-chevron-right"></i>
                </div>
              </a>
            </div>
            <div class="news-col">
              <div
                id="carouselExampleCaptions"
                class="carousel slide"
                data-bs-ride="false"
              >
                <div class="carousel-indicators">
                  <button
                    type="button"
                    data-bs-target="#carouselExampleCaptions"
                    data-bs-slide-to="0"
                    class="active"
                    aria-current="true"
                    aria-label="Slide 1"
                  ></button>
                  <button
                    type="button"
                    data-bs-target="#carouselExampleCaptions"
                    data-bs-slide-to="1"
                    aria-label="Slide 2"
                  ></button>
                  <button
                    type="button"
                    data-bs-target="#carouselExampleCaptions"
                    data-bs-slide-to="2"
                    aria-label="Slide 3"
                  ></button>
                </div>
                <div class="carousel-inner">
                  <div class="carousel-item active">
                    <img
                      src="https://blog.clicknext.com/wp-content/uploads/2022/09/301311663_502861868508148_748688933476987067_n-1-400x225.jpg"
                      class="d-block w-100"
                      alt="..."
                    />
                    <div class="carousel-caption d-none d-md-block">
                      <!-- <h5>Clicknext ร่วมยินดีกับนายกสมาคมผู้ประกอบการพาณิชย์อิเล็กทรอนิกส์ไทย (THECA) คนใหม่</h5> -->
                      <p class="transparent">
                        Clicknext
                        ร่วมยินดีกับนายกสมาคมผู้ประกอบการพาณิชย์อิเล็กทรอนิกส์ไทย
                        (THECA) คนใหม่
                      </p>
                    </div>
                  </div>
                  <div class="carousel-item">
                    <img
                      src="https://blog.clicknext.com/wp-content/uploads/2022/03/S__7184468-400x225.jpg"
                      class="d-block w-100"
                      alt="..."
                    />
                    <div class="carousel-caption d-none d-md-block">
                      <p class="transparent">
                        Clicknext ยกระดับมาตรฐานความปลอดภัย ผ่าน ISO/IEC 27001
                        จาก BSI
                      </p>
                    </div>
                  </div>
                  <div class="carousel-item">
                    <img
                      src="https://blog.clicknext.com/wp-content/uploads/2022/09/IMG_5942-400x225.jpg"
                      class="d-block w-100"
                      alt="..."
                    />
                    <div class="carousel-caption d-none d-md-block">
                      <p class="transparent">
                        งานสัมมนา Clicknext RE-Connect Outing 2022
                      </p>
                    </div>
                  </div>
                </div>
                <button
                  class="carousel-control-prev"
                  type="button"
                  data-bs-target="#carouselExampleCaptions"
                  data-bs-slide="prev"
                >
                  <span
                    class="carousel-control-prev-icon"
                    aria-hidden="true"
                  ></span>
                  <span class="visually-hidden">Previous</span>
                </button>
                <button
                  class="carousel-control-next"
                  type="button"
                  data-bs-target="#carouselExampleCaptions"
                  data-bs-slide="next"
                >
                  <span
                    class="carousel-control-next-icon"
                    aria-hidden="true"
                  ></span>
                  <span class="visually-hidden">Next</span>
                </button>
              </div>
              <div class="news-img">
                <img
                  src="../assets/Chatcone-1600x400-สัมมนา-DEPA-x-Chatcone-1536x384-1.png"
                  alt=""
                />
              </div>
            </div>
          </div>
        </div>
        <div class="section sectionBottom">
          <div class="sectionBottom-headline">
            <div class="headline"><h2>Clicknext Culture</h2></div>
            <div class="hedline-detail">
              <p class="medium">
                ที่ Clicknext ทำงาน 1 ปีได้ความรู้เหมือนทำงานมา 10 ปี
              </p>
            </div>
          </div>
          <div class="sectionBottom-content">
            <div class="vdo-choice">
              <div class="choice choice-1">
                <a href=""><h3>Who We Are</h3></a>
              </div>
              <div class="choice">
                <a href=""><h3 class="vdohidden">Internship</h3></a>
              </div>
              <div class="choice">
                <a href=""><h3 class="vdohidden">Activity</h3></a>
              </div>
            </div>
            <div class="vdo-content">
              <div class="vdo">
                <div class="vdo-technology">
                  <iframe
                    class="vdo-xl"
                    width="560"
                    height="315"
                    src="https://www.youtube.com/embed/YF6J7pSCcXw"
                    title="YouTube video player"
                    frameborder="0"
                    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                    allowfullscreen
                  ></iframe>
                </div>

                <div class="detailvdo">
                  <h3 class="text-L">"Spirit of Craftmanship"</h3>
                  <p class="medium">
                    ที่ Clicknext เราคือแหล่งรวมตัวของคนที่กระหายในการสร้าง
                    พวกเรามีเป้าหมายเดียวกันคือ
                    การสร้างและพัฒนาซอฟต์แวร์,เทคโนโลยี AR/VR
                    ให้ตอบโจทย์ธุรกิจและทำให้สิ่งที่เราสร้างเป็นที่รู้จักทั่วโลก
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="sectionBottom-detail">
            <div class="hidden">
              <p class="hidden-text">.</p>
              <a
                href="https://blog.clicknext.com/category/all-category/technology/"
                class="seeAll"
              >
                <p class="small">ดูทั้งหมด</p>
                <div class="seeAll-buttom">
                  <i class="fa-solid fa-chevron-right"></i>
                </div>
              </a>
            </div>
            <div class="detail-content">
              <div>
                <a
                  href="https://blog.clicknext.com/improved-android-app-to-appgallery/"
                  target="_blank"
                >
                  <img
                    src="https://blog.clicknext.com/wp-content/uploads/2021/03/%E0%B8%A7%E0%B8%B4%E0%B8%98%E0%B8%B5%E0%B8%9B%E0%B8%A3%E0%B8%B1%E0%B8%9A%E0%B8%9B%E0%B8%A3%E0%B8%B8%E0%B8%87%E0%B9%83%E0%B8%AB%E0%B9%89-Android-Application-%E0%B9%80%E0%B8%9C%E0%B8%A2%E0%B9%81%E0%B8%9E%E0%B8%A3%E0%B9%88%E0%B8%9A%E0%B8%99-AppGallery_nam-768x432.png"
                    alt=""
                  />
                  <h3 class="second-content">
                    วิธีปรับปรุงให้ Android Application เผยแพร่บน AppGallery ได้
                  </h3>
                </a>
              </div>
              <div>
                <a
                  href="https://blog.clicknext.com/android-navigation-component/"
                  ><img
                    src="https://blog.clicknext.com/wp-content/uploads/2021/01/banner_ER-Diagram-768x432.png"
                    alt=""
                    target="_blank"
                  />
                  <h3 class="second-content">ER-Diagram คืออะไร?</h3></a
                >
              </div>
              <div>
                <a
                  href="https://blog.clicknext.com/what-is-er-diagram/"
                  target="_blank"
                  ><img
                    src="https://blog.clicknext.com/wp-content/uploads/2020/12/Android-Navigation-Component-768x432.png"
                    alt=""
                  />
                  <h3 class="second-content">
                    Android Navigation Component คือ อะไร?
                  </h3></a
                >
              </div>
            </div>
          </div>
        </div>
      </div>
      <div id="footer">
        <div class="footer-info">
          <div class="location">
            <h4 class="clicknext">CLICKNEXT COMPANY LIMITED</h4>
            <p>
              128/323-333 30th FL. Phayathai Plaza Bldg. Phayathai road, Thung
              Phayathai, Ratchathewi, Bangkok, 10400, Thailand.
            </p>
          </div>
          <div class="menu">
            <h4>Company</h4>
            <ul>
              <li><a href="" target="_blank">Team</a></li>
              <li><a href="" target="_blank">Carees</a></li>
              <li><a href="" target="_blank">Success Story</a></li>
              <li><a href="" target="_blank">Contact</a></li>
            </ul>
          </div>
          <div class="menu">
            <h4>Product</h4>
            <ul>
              <li><a href="">MakeWebEasy</a></li>
              <li><a href="">ChatCone</a></li>
              <li><a href="">SMS Marketing</a></li>
              <li><a href="">CMS</a></li>
            </ul>
          </div>
          <div class="contactInfo">
            <h4>Contact us</h4>
            <div>
              <div class="contactMe">
                <i class="fa-solid fa-square-phone"></i>
                <p>+66-2217-7900</p>
              </div>
              <div class="contactMe">
                <i class="fa-solid fa-envelope"></i>
                <p>info@clicknext.com</p>
              </div>
            </div>
            <div></div>
            <div class="social">
              <a href="https://www.facebook.com/clicknext/" target="_blank"
                ><i class="fa-brands fa-square-facebook"></i
              ></a>
              <a href=""
                ><i class="fa-brands fa-youtube" target="_blank"></i
              ></a>
            </div>
          </div>
        </div>
        <div class="coppy-right">
          <p class="coppy-right">
            Project for apply jop at Clicknext by Pattarapon Srimanta
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AboutComponent",
};
</script>

<style scoped>
/*Navbar*/
.section-body {
  width: 100%;
}

.navbar-toggler {
  border: 1px solid #fff !important;
  background-color: #fff !important;
}
.container-fluid {
  padding-left: calc(var(--bs-gutter-x) * 2) !important;
  padding-right: calc(var(--bs-gutter-x) * 2) !important;
}
.navbar-toggler {
  background-color: rgba(var(--bs-dark-rgb), var(--bs-bg-opacity)) !important;
}
.navbar-toggler {
  margin-top: 0;
  margin-bottom: 0;
  font-size: 12px;
  height: 40px;
}
.img-logo {
  height: 65px;
  width: auto;
  display: inline-block !important;
  vertical-align: middle;
  margin-left: 20px;
}
.search {
  width: 2rem;
  height: 2rem;
}
.search i {
  color: var(--color-gray-1);
  font-size: 0.8rem;
  text-align: center;
  align-items: center !important;
  padding-top: 0.4rem;
}
.right {
  display: flex;
  margin-right: 0;
  font-size: 1rem;
  color: var(--color-gray-1);
  align-items: center !important;
  float: right !important;
  padding-top: 1.2rem;
}
.offcanvas.offcanvas-end {
  left: 0 !important;
  right: unset !important;
}

/*Header*/
#carouselExampleControls {
  padding-top: 4rem;
}
.carousel-item img {
  width: 100%;
  height: auto;
  padding: 0;
}
.pagination li {
  padding-right: 2rem;
  justify-content: center;
  justify-items: center;
}
.nav-bottom {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-top: -1rem;
  /* position: absolute;  */
  justify-content: center;
  position: absolute;
  width: 100% !important;
}
.pagination ul {
  margin-left: 2rem !important;
  margin-right: 2rem !important;
}
.page-link {
  background: #fff;
  color: #2a2e35;
  padding: 1rem;
  width: 10rem;
  text-align: center;
  border-bottom: 5px solid var(--color-secondary);
  font-weight: 700;
  box-shadow: 1px 4px 15px rgba(0, 0, 0, 0.32);
  z-index: 900;
}
.page-link:hover {
  background: var(--color-secondary);
  color: #fff;
  border-bottom: 5px solid var(--color-secondary);
  transition: var(--transition);
}
.active-btn {
  background: var(--color-secondary);
  color: #fff;
  border-bottom: 5px solid var(--color-secondary);
  transition: var(--transition);
}
.page-link-i {
  z-index: 1000;
}
a span {
  color: var(--color-secondary);
  margin-top: 2rem;
  font-size: 1.5rem;
}
#carouselExampleControls {
  background: var(--color-primarty);
  padding-bottom: 3rem;
}
.page-item i {
  padding-top: 1.5rem;
  text-shadow: 1px 4px 15px rgba(0, 0, 0, 0.32);
}
.page-item i:hover {
  color: black;
  transition: var(--transition);
}

/* content section */
.section-content {
  min-height: 100vh;
  width: 100%;
  padding: 5rem 5rem;
}
.sectionTop {
  background: rgb(213, 213, 213);
  background: linear-gradient(
    360deg,
    rgba(213, 213, 213, 1) 0%,
    rgba(237, 237, 237, 1) 8%,
    rgba(255, 255, 255, 1) 44%,
    rgba(255, 255, 255, 1) 100%
  );
  clip-path: polygon(0 0, 100% 0, 100% 85%, 0% 100%);
  display: flex;
  padding: 5rem 5rem 5rem 5rem;
}
h2 {
  font-size: 2.5rem;
  color: var(--color-secondary) !important;
  font-weight: 600;
}
.heading-arcticle {
  justify-content: space-between;
}
.seeAll {
  display: flex;
  margin-left: 20px;
  font-size: 0.8rem;
  color: var(--color-third);
  padding-top: 0.8rem;
}
.seeAll i {
  font-size: 0.8rem;
  align-items: center;
  padding-bottom: 2.2rem;
  color: var(--color-gray-3);
}
.seeAll-buttom {
  border: var(--color-gray-3) 1px solid;
  border-radius: 50%;
  width: 18px;
  height: 18px;
  text-align: center;
  margin-left: 0.2rem;
}
h3 {
  font-size: 18px;
  color: var(--color-gray-4) !important;
  font-weight: 600;
}
.second-content {
  font-size: 16px;
  padding-top: 1rem;
  color: var(--color-gray-3);
}
p {
  font-size: 14px;
  color: var(--color-gray-3);
}
.small {
  font-size: 14px;
  color: var(--color-gray-3);
}
.article-tag {
  border-left: 3px solid var(--color-secondary);
  padding-left: 0.5rem;
  font-size: 14px;
  color: var(--color-gray-4) !important;
}
.article-tag p {
  color: var(--color-secondary);
  font-size: 14px;
}
.img-article-detail {
  width: 100%;
  height: 13rem;
  margin: 0 -10px;
}
.img-article-main {
  width: 25rem;
  height: 14rem;
  padding-right: 1rem;
  margin: -5px 0 0 -10px;
}
.main-article {
  display: flex;
  padding: 0.5rem 0 0.5rem 0;
}
.detail-article {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-gap: 2rem;
}
.news-img img {
  padding: 3rem 0rem 0 0rem;
  max-width: 100%;
  max-height: 100%;
  object-fit: contain;
}
.new-img {
  background: #fff;
  width: 100%;
}
.sectiontop-left img:hover {
  transform: scale(1.1);
  transition: var(--transition);
}
h3:hover {
  color: var(--color-secondary);
}
.news-col {
  padding-top: 0.8rem;
}
.transparent {
  background: rgba(0, 0, 0, 0.6);
  color: #fff;
}
.carousel-indicators {
  margin-bottom: -2rem !important;
}
.carousel-indicators button {
  background-color: var(--color-secondary);
}
.carousel-caption {
  bottom: 0;
  right: 0;
  left: 0;
  margin-bottom: -2.2rem;
}
.sectiontop-left {
  flex: 3;
  /* border:solid 1px black; */
  padding-right: 1rem;
}
.sectiontop-right {
  flex: 1.5;
  width: 20rem;
  /* border:solid 1px blue; */
  margin-left: 3rem;
}
.heading-arcticle {
  display: flex;
}
.sectionBottom {
  min-height: 100vh;
  padding: 1rem 5rem;
  width: 100%;
}
.sectionBottom-headline {
  display: flex;
}
.choice {
  padding: 0 2rem;
  border-right: solid 2px var(--color-fourth);
}
.vdohidden {
  color: gray !important;
}
.vdo-choice {
  display: flex;
}
.vdo {
  display: flex;
  margin-bottom: 2rem;
}

.detail-content {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 2rem;
}
.detail-content img {
  width: 100%;
  height: auto;
  -o-object-fit: cover;
  object-fit: cover;
}
.detail-content img:hover {
  transform: translateY(-5px);
  transition: var(--transition);
}
.medium {
  font-size: 16px;
  color: var(--color-gray-3);
}
.hedline-detail {
  margin-top: 1.6rem;
  padding-left: 2rem;
}
#footer {
  min-height: 35vh;
}
.vdo-choice {
  margin: 1rem 0 1rem 1rem;
}
.vdo-technology {
  width: 55rem;
  height: 22rem;
  margin-left: 3rem;
}
iframe {
  box-shadow: 10px 10px 33px -11px rgba(0, 0, 0, 0.75);
  -webkit-box-shadow: 10px 10px 33px -11px rgba(0, 0, 0, 0.75);
  -moz-box-shadow: 10px 10px 33px -11px rgba(0, 0, 0, 0.75);
}
.detailvdo {
  margin: 3rem;
  align-items: center;
  justify-items: center;
  padding: 2rem 0 1rem 1rem;
  border-top: solid 4px var(--color-fourth);
  border-bottom: solid 4px var(--color-fourth);
}
.text-L {
  font-size: 24px;
  color: var(--color-secondary) !important;
  font-weight: 600;
  padding-bottom: 1.2rem;
}
.hidden-text {
  color: var(--color-white);
  padding: 0;
  margin: 0;
}
.hidden {
  justify-content: space-between;
  padding: 0 2rem 0 0;
  margin: 0;
  width: 100%;
  display: flex;
}
.footer-info {
  display: flex;
  background: var(--color-third);
  padding: 3rem 5rem;
  color: var(--color-gray-0);
  line-height: 1.5rem;
}
.footer-info h2,
p,
a,
h3 {
  color: var(--color-gray-0);
}
.footer-info h4 {
  margin-bottom: 1rem;
}
.footer-info li,
a {
  text-decoration: none;
  margin-bottom: 0.4rem;
}

.coppy-right {
  background: var(--color-secondary);
  color: var(--color-gray-4);
  text-align: center;
  padding: 0.4rem 0 0.1rem 0;

  justify-content: center;
}
.location {
  flex: 3;
  margin-right: 4rem;
}

.menu {
  flex: 1;
  padding-right: 4rem;
}
.menu li {
  font-size: 14px;
  margin-left: -2rem;
}
.contactInfo {
  flex: 2;
}
.contactMe {
  display: flex;
}
.contactMe p {
  margin-left: 1rem;
}
.clicknext {
  color: var(--color-secondary);
  font-weight: bold;
}
.social i {
  margin: 0.5rem;
  text-align: center;
}
.social {
  margin-right: 3rem;
}

/*Responsive*/
@media screen and (max-width: 1070px) {
  .img-article-main {
    width: 20rem;
    height: 12rem;
  }
  .sectiontop-left {
    padding-right: 0;
  }
  .samll .article-tag {
    font-size: 12px !important;
  }
  h3 {
    font-size: 16px !important;
  }
  .second-content {
    font-size: 14px !important;
  }
  .img-article-detail {
    height: 10rem;
  }
  .vdo-technology {
    width: 40rem !important;
    height: 18rem;
  }
  .detailvdo {
    margin: 0 0 0 10px;
  }
  .medium {
    font-size: 14px;
  }
}
@media screen and (max-width: 700px) {
  #main-nav-btn {
    visibility: hidden;
  }
  .img-logo {
    height: 50px;
  }
  .navbar {
    margin: 0;
  }
  .sectionTop {
    padding: 2rem 3rem 5rem 3rem;
    clip-path: polygon(0 0, 100% 0, 100% 95%, 0% 100%);
    flex-direction: column;
  }
  .main-article {
    flex-direction: column;
  }
  .img-article-main {
    width: 100%;
    height: auto;
    -o-object-fit: cover;
    object-fit: cover;
  }
  .img-article-detail {
    width: 100%;
    height: 6.5rem;
  }
  .second-content {
    font-size: 12px !important;
    color: var(--color-gray-2);
  }
  .article-tag {
    font-size: 12px !important;
  }
  .sectiontop-right {
    margin: 2rem 0;
    width: 100%;
    height: auto;
    -o-object-fit: cover;
    object-fit: cover;
  }
  .d-none {
    display: block;
  }
  .sectionBottom {
    padding: 2rem 3rem 5rem 3rem;
    width: 100%;
    height: auto;
    -o-object-fit: cover;
    object-fit: cover;
  }
  .sectionBottom-headline {
    flex-direction: column;
  }
  .hedline-detail {
    margin-top: 0rem;
    padding-left: 0rem;
  }
  .vdo-choice {
    margin-left: 0 !important;
  }
  .choice-1 {
    padding-left: 0;
  }
  .choice {
    padding: 1rem;
  }
  .vdo {
    flex-direction: column;
  }
  .vdo-technology {
    margin-left: 0;
  }
  .vdo-content {
    width: 100%;
    height: auto;
    -o-object-fit: cover;
    object-fit: cover;
  }

  .detailvdo {
    margin: 30px 0 0 0;
    border-top: none;
  }
  .detail-content {
    grid-template-columns: 1fr;
  }
  .footer-info {
    flex-direction: column;
    padding: 3rem;
    line-height: 1.2rem;
  }
  .location {
    margin-right: 1rem;
  }
}
@media screen and (max-width: 970px) {
  #main-nav-btn {
    visibility: hidden;
  }
  .main-article {
    flex-direction: column;
  }
  .img-article-main {
    width: 100%;
    height: auto;
    -o-object-fit: cover;
    object-fit: cover;
  }
  .sectionTop {
    padding: 2rem 3rem 5rem 3rem;
    clip-path: polygon(0 0, 100% 0, 100% 95%, 0% 100%);
  }
  .sectionBottom {
    padding: 1rem 3rem 5rem 3rem;
    width: 100%;
    height: auto;
    -o-object-fit: cover;
    object-fit: cover;
  }
  .vdo-choice {
    margin-left: 0 !important;
  }
  .choice-1 {
    padding-left: 0;
  }
  .vdo-technology {
    margin-left: 0;
  }
}
</style>
