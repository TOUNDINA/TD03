<template>
  <header>
    <!-- <div class="wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/product">Product</RouterLink>
        <button @click="$emit('checkout')">Go to checkout</button>
      </nav>
    </div> -->
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

  <RouterView />
</template>
