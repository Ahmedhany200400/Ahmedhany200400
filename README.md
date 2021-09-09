- 👋 Hi, I’m @Ahmedhany200400
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Ahmedhany200400/Ahmedhany200400 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html dir="rtl" lang="en">
  <head>


    <script>       @import url("https://fonts.googleapis.com/css2?family=Kufam:wght@700&family=Tajawal:wght@400;700&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  font-size: 10px;
  scroll-behavior: smooth;
}
body {
  font-family: "Tajawal", sans-serif;
  background: #d9e2ec;
  overflow-x: hidden;
}

h1 {
  font-size: 5rem;
  margin-bottom: 1rem;
  color: #f0f4f8;
}

h1 span {
  color: #27ab83;
}

h2 {
  color: #243b53;
  font-size: 3.4rem;
  margin-bottom: 1rem;
}

h3 {
  color: #2b4561;
  font-size: 2.4rem;
  margin-bottom: 1rem;
}
h4 {
  font-size: 2rem;
  width: 40%;
  line-height: 1.8;
  margin-bottom: 2rem;
  color: #d5d5d5;
}

p {
  font-size: 1.6rem;
  color: #345375;
  line-height: 2;
}

/* Nav Section */
.nav-container {
  background: #334e68;
  color: #f0f4f8;
}

nav {
  width: 90%;
  max-width: 1366px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  min-height: 10vh;
  font-size: 1.6rem;
}

nav .logo {
  font-family: "Kufam", cursive;
  font-weight: bold;
  flex: 3;
  color: #f0f4f8;
}

nav ul {
  display: flex;
  list-style-type: none;
  justify-content: space-between;
  flex: 1;
}

nav ul li a {
  color: #f0f4f8;
  text-decoration: none;
}

/* Hero Section */

.hero {
  height: 90vh;
  position: relative;
}

.hero::after {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  z-index: -1;
  right: 0;
  background-image: linear-gradient(
      90deg,
      rgba(51, 78, 104, 0.2) 0%,
      rgba(20, 63, 92, 0.8) 20%
    ),
    url("./images/background.jpg");

  animation: herobg 3s ease-in;
  background-position: center;
}

.content {
  width: 90%;
  max-width: 1366px;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  height: 90vh;
}

.btn {
  font-family: inherit;
  font-size: 1.6rem;
  font-weight: bold;
  padding: 0.75rem 3rem;
  border-radius: 0.5rem;
  border: none;
  color: #243b53;
  background: #27ab83;
  text-decoration: none;
}

.btn:hover {
  background: #239673;
}

.btn:active {
  scale: 0.98;
}

/* Qualities Section */
#qualities {
  width: 90%;
  max-width: 1366px;
  margin: 4rem auto;
  height: 100%;
  min-height: 50vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  text-align: center;
}

.qualities-container {
  display: flex;
  justify-content: space-between;
  grid-gap: 2rem;
  padding-top: 5rem;
}

.quality {
  background: #bcccdc;
  padding: 4rem 0;
  width: 30%;
}

.quality p {
  text-align: center;
  width: 70%;
  margin: 1rem auto;
}

.header-container {
  display: flex;
  align-items: center;
  justify-content: center;
}

i {
  color: #27ab83;
  font-size: 2.4rem;
  margin-left: 1rem;
  opacity: 0.7;
}

/* About us */

.about-container {
  background: #334e68;
}
.about-us {
  width: 90%;
  max-width: 1366px;
  margin: 0 auto;
  height: 50vh;
  display: flex;
  justify-content: space-between;
}

.about-us img {
  width: 100%;
  height: 100%;
}

.about-us .about-content {
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.about-content h2 {
  color: #d9d9d9;
}
.about-content p {
  margin-top: 1rem;
  width: 80%;
  color: #d5d5d5;
}

/* Contact us */

.contact-us {
  width: 90%;
  max-width: 1366px;
  margin: 5rem auto 0 auto;
  height: 100%;
  padding: 2rem 0;
  text-align: center;
}

form {
  display: flex;
  flex-direction: column;
  padding: 5rem 0;
  width: 100%;
  align-items: center;
}

form .btn {
  width: 100px;
  text-align: center;
}

label,
input,
textarea,
.btn {
  font-family: inherit;
  font-size: 1.6rem;
}

label,
input,
textarea {
  margin-bottom: 1.5rem;
}

input,
textarea {
  width: 80%;
  border-radius: 1rem;
  border: none;
  outline: none;
  padding: 0.75rem 2rem;
}
.contact-us {
  text-align: center;
}

textarea {
  resize: vertical;
}

/* Footer */
footer {
  background: #243b53;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 10vh;
}

footer p {
  color: #d9d9d9;
}

@keyframes herobg {
  from {
    scale: 1.2;
  }
  to {
    scale: 1;
  }
}

/* Responsive Design */

@media (max-width: 1400px) {
  .hero .content {
    align-items: center;
    text-align: center;
  }
  .hero h4 {
    width: 100%;
  }

  .hero::after {
    animation: none;
  }
}
@media (max-width: 1042px) {
  html {
    font-size: 10px;
  }

  nav ul {
    flex-direction: column;
  }
  nav ul li {
    margin: 0.5rem 0;
  }

  .qualities-container {
    flex-wrap: wrap;
  }
  .quality {
    width: 100%;
  }
}

@media (max-width: 752px) {
  html {
    font-size: 8px;
  }

  .about-us img {
    display: none;
  }
  .about-content {
    justify-content: center;
    align-items: center;
    text-align: center;
  }
}

@media (min-width: 1400px) {
  input,
  textarea {
    width: 40%;
  }
}
</script>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta property="og:title" content="طلبك" />
    <meta property="og:description" content="بنوصل طلبك لباب بيت عملاءك." />
    <meta property="og:image" content="https://i.ibb.co/tMDGsYd/og.jpg"/>

    <link rel="stylesheet" href="style.css" />
    
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css" integrity="sha512-+4zCK9k+qNFUR5X+cKL9EIR+ZOhtIloNl9GIKS57V1MyNsYpYcUrUeQc9vNfzsWfV28IaLL3i96P9sdNyeRssA==" crossorigin="anonymous" />
    <title>طلبك</title>
  </head>
  <body>
    <div class="container">
      <div class="nav-container">
        <nav>
          <h3 class="logo">طلبك</h3>
          <ul>
            <li><a href="./index.html">الصفحة الرئيسية</a></li>
            <li><a href="#aboutus">من نحن</a></li>
            <li><a href="#contactus">تواصل معنا</a></li>
          </ul>
        </nav>
      </div>
      <div class="hero">
        <div class="content">
          <h1>بدك <span> طلبك</span> يوصل بسرعة؟</h1>
          <h4>
            طلبك شركة بتقدملك أفضل وأسرع الحلول لتوصيل منتجاتك في كافة أنحاء
            المملكة
          </h4>
          <a href="#qualities" class="btn">إعرف أكثر عنا</a>
        </div>
      </div>
      
      <section id="qualities">
        <h2>ماذا نقدم لكم؟</h2>
        <div class="qualities-container">

        <div class="quality">
          <div class="header-container">
            <i class="fas fa-tachometer-alt"></i>
            <h3>سرعة كبيرة</h3>
          </div>
          <p>
            طلبك رح يوصل بمدة لا تتجاوز ثلاثة أيام عمل لكافة أنحاء المملكة لكثرة
            سيارات التوصيل المتوزعة في كافة المناطق
          </p>
        </div>
        <div class="quality">
          <div class="header-container">
            <i class="fas fa-star"></i>
            <h3>جودة عالية</h3>
          </div>
          <p>
            فريق مختص بخبرة كبيرة في التغليف والتوصيل لضمان وصول طلبك بدون أي
            أضرار وبشكل كامل وبكفاءة عالية
          </p>
        </div>
        <div class="quality">
          <div class="header-container">
            <i class="fas fa-money-bill-wave-alt"></i>
            <h3>أسعار رمزية</h3>
          </div>
          <p>
            نقدم لكم أفضل الأسعار المنافسة لكافة الشركات في كافة انحاء المملكة،
            بالإضافة إلى خصومات على التوصيل للكميات الكبيرة
          </p>
        </div>
      </section>
      <div id='aboutus' class="about-container">
        <section class="about-us">
            <div class="about-content">
              <h2>من نحن؟</h2>
              <p>
                شركة طلبك هي شركة توصيل تأسست في عام 2020 بهدف توفير السبل لكافة
                القطاعات لتوصيل منتجاتها لجميع الأرجاء. لدينا فروع منتشرة في كافة
                أنحاء المملكة. طاقمنا يتكون من مجموعة متنوعة من ذوي الخبرة في
                التوصيل والتعامل مع العملاء
              </p>
            </div>
            <img src="./images/who-are-we.jpg" alt="" />
        </div>
          </section>
      </div>
      <section id="contactus" class="contact-us">
        <h2>تواصل معنا</h2>
        <form>
          <label for="name">اسمك</label>
          <input type="text" id="name" name="name" />
          <label for="email">بريدك الالكتروني</label>
          <input type="email" id="email" name="email"/>
          <label for="msg">رسالتك لنا</label>
          <textarea name="message" id="msg" cols="30" rows="5"></textarea>
        <button class="btn" type='submit'>إرسال</button>
        </form>
      </section>
      <footer>
          <p>المعلومات أعلاه خياليه ولا تمثل أي شركة حقيقية. 2020 </p>
      </footer>
    </div>
  </body>
</html>


























































