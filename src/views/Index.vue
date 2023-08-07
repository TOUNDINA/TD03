<template>
  <header>
    <div class="wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/product">Product</RouterLink>
        <button @click="$emit('checkout')">Go to checkout</button>
      </nav>
    </div>
    <nav>
   <input type="checkbox" id="check"> <label for="check" class="checkbtn">
     <i class="fa fa-bars"></i>
     </label> <label class="logo">Foodie</label>
        <ul>
          <li><RouterLink to="/">Home</RouterLink></li>
          <li><RouterLink to="/about">About</RouterLink></li>
          <li><RouterLink to="/product">Product</RouterLink></li>
          <li><a href="#">Contact Us</a></li>
          <i class="fa fa-search"></i>
          <button @click="$emit('checkout')">Go to checkout</button>
        </ul>
  </nav>
  </header>

  <!-- <footer>
        <div class="sub_footer">
            <div class="footer_box">
                <img src="../IMAG/footer-logo.png" alt=""><br>
                <span>​© រក្សា​សិទ្ធិ​គ្រប់​យ៉ាង​ដោយ​ Sabay ឆ្នាំ​២០១៦</span><br>
                <a href="">គោលការណ៍​ភាព​ឯកជន | Privacy Policy</a>
                <p>អាសយដ្ឋាន</p>
                <span>អគារ​លេខ ៣០៨ មហាវិថីព្រះមុន្នីវង្ស <br>សង្កាត់បឹងរាំង ខណ្ឌដូនពេញ</span>
            </div>
            <div class="footer_box">
                <h2>អំពីយើង</h2>
                <span>Sabay Digital Corporation ជា​ក្រុមហ៊ុន​ព័ត៌មាន​ឌីជីថល និង​កម្សាន្ត​ឈាន​មុខ​គេ​នៅ​កម្ពុជា។</span>
                <a href="">ព័ត៌មាន​បន្ថែម</a><br>
                <span>ផលិត​ផល​ និង​ សេវាកម្ម របស់ Sabay</span>
                <p>
                    <img src="/IMAG/logo (1).png" alt="">
                    <img src="/IMAG/logo (2).png" alt="">
                    <img src="/IMAG/logo (3).png" alt="">
                    <img src="/IMAG/logo (4).png" alt="">
                    <img src="/IMAG/logo (5).png" alt="">
                    <img src="/IMAG/61d5007946e0b_1641349200_small.png" alt="">
                    <img src="/IMAG/61d501f25761a_1641349560_small.png" alt="">
                    <img src="/IMAG/61d5007946e0b_1641349200_small (1).png" alt="">
                    <img src="/IMAG/61d4f62a95ade_1641346560_small.png" alt="">
                    <img src="/IMAG/logo (6).png" alt="">
                    <img src="/IMAG/logo (7).png" alt="">
                </p>
            </div>
            <div class="footer_box">
                <h2>ជួបគ្នានៅបណ្តាញសង្គម</h2>
                <span>
                    <i class="fab fa-facebook"></i>
                    <i class="fab fa-telegram"></i>
                    <i class="fab fa-youtube"></i>
                    <i class="fab fa-instagram"></i>
                </span>
                <p>ទំនាក់ទំនង</p>
                <a href="">info@sabay.com</a><br>
                <span>023 228 000</span>
            </div>
        </div>
    </footer> -->

  <RouterView />
</template>
