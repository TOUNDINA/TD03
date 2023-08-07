<template>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="/Page3.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;500;600;700&display=swap" rel="stylesheet">
</head>
    <div class="con_check">
        <div class="left_con">
            <div class="header">
                <!-- <hr> -->
                <div class="sub_header">
                    <div class="header_item">Item</div>
                    <div class="header_price">Price</div>
                    <div class="header_quantity">Quantity</div>
                </div>
            </div>
            <div class="body_item">
                <div class="item">
                    <div class="image"><img src="../assets/images/download.jpg" alt=""></div>
                    <div class="text">
                        <div class="name"><p>Fried Chicken </p></div>
                        <div class="size"><p>Size: Small</p></div>
                    </div>
                </div>
                <div class="price"><h4>$20.20</h4></div>
                <div class="quantity">
                    <select name="dog-names" id="dog-names"> 
                        <option value="">1</option> 
                        <option value="">2</option> 
                        <option value="">3</option> 
                        <option value="">4</option> 
                        <option value="">5</option> 
                        <option value="">6</option> 
                        <option value="">7</option> 
                        <option value="">8</option> 
                        <option value="">9</option> 
                    </select>
                </div>
            </div>
            <div class="footer"></div>
        </div>
        <div class="right_con">
            <div class="sub_right">
                <h4>Suumary(1item)</h4>
                <div class="list">
                    <div class="left_text">
                        <p>Subtotal</p>
                        <p>Shipping</p>
                        <p>EsL Taxs</p>
                    </div>
                    <div class="right_num">
                        <h4>$20.20</h4>
                        <h4>-</h4>
                        <h4>-</h4>
                    </div>
                </div>
                <hr style="background-color: white; width:90%">
                <div class="total">
                    <div class="text"><h3>Total</h3></div>
                    <div class="num"><h4>$20.20</h4></div>
                </div>
                <div class="btn"><button>Checkout</button></div>
            </div>
        </div>
    </div>
    <button @click="$emit('cancel')">Cancel</button>
    <div class="con_info">
        <div class="left_con_info">
            <div class="cus_info">
                <div class="left_cus"><h3 style="color: #FFA500;">Customer Information</h3></div>
                <div class="right_cus"><p>Aready have an acount?</p><div class="login">Login</div></div>
            </div>
            <div class="form">
                <form action="">
                    <input type="email" name="" id="" placeholder="Email"><br>
                    <input type="checkbox" name="" id="">
                    <label for="" style="color: #A3A2A2;">Keep me up to date on news and exclusive offers</label>
                </form>
                <p>Shipping Address</p>
                <form action="">
                    <input type="text" name="Firstname" id="" placeholder="First name">
                    <input type="text" name="lastname" id="" placeholder="Last name">
                    <input type="text" name="company" id="company" placeholder="Company(optional)">
                    <input type="text" name="address" id="addr" placeholder="Address"> 
                    <input type="text" name="apt" id="apt" placeholder="apt(optional)">
                    <select id="country" name="country">
                        <option value="volvo">Cambodia</option>
                        <option value="saab">Korea</option>
                        <option value="fiat">China</option>
                        <option value="audi">English</option>
                        <option value="audi">Hong kong</option>
                        <option value="audi">American</option>
                        <option value="audi">Malaysia</option>
                        <option value="audi">Thailand</option>
                        <option value="audi">Indonesia</option>
                        <option value="audi">India</option>
                        <option value="audi">Japan</option>
                        <option value="audi">Turkey</option>
                      </select>
                      <select id="state" name="state">
                        <option value="volvo">Phnom Penh</option>
                        <option value="saab">Kandal</option>
                        <option value="fiat">Kompong Cham</option>
                        <option value="audi">Kompong chnang</option>
                        <option value="audi">sveyreang</option>
                        <option value="audi">siemreap</option>
                      </select>
                    <input type="text" name="zip" id="zip" placeholder="Zip">
                </form>
            </div>
        </div>
        <!-- <div class="right_con_info"></div> -->
        <div class="right_con">
            <div class="sub_right">
                <h4>Suumary(1item)</h4>
                <div class="list">
                    <div class="left_text">
                        <p>Subtotal</p>
                        <p>Shipping</p>
                        <p>EsL Taxs</p>
                    </div>
                    <div class="right_num">
                        <h4>$20.20</h4>
                        <h4>-</h4>
                        <h4>-</h4>
                    </div>
                </div>
                <hr style="background-color: white; width:90%">
                <div class="dis_code">
                    <p>Gift card or discound code</p>
                    <form action="">
                        <input type="text" name="discount code" id="code">
                        <button>Appy</button>
                    </form>
                </div>
                <hr style="background-color: white; width:90%">
                <div class="total">
                    <div class="text"><h3>Total</h3></div>
                    <div class="num"><h4>$20.20</h4></div>
                    
                </div>
            </div>
        </div>
    </div>
    <!-- //////// -->
    <div class="con_info">
        <div class="left_con_info">
            <div class="sub_info">
                <hr>
                <div class="text_info">
                    <p style="color: #ffa500;">Shipping Address<span> 12 Word Point Road, Rood, Mishauken, NY 1200</span></p>
                    <div class="edit">Edit</div>
                </div>
                <hr>
                <p style="margin-top: 50px;">Shipping Method</p>
               <div class="form">
                    <div class="sub_form">
                        <form action="">
                              <input type="radio" id="html" name="fav_language" value="HTML">
                              <label for="html">Fried Chicken Unlimited</label><br>
                              <input type="radio" id="css" name="fav_language" value="CSS">
                              <label for="css">Fried Chicken Unlimited</label><br>
                              <input type="radio" id="javascript" name="fav_language" value="JavaScript">
                              <label for="javascript">Fried Chicken Unlimited</label><br>
                              <input type="radio" id="foot" name="" value="foot">
                              <label for="foot">Fried Chicken Unlimited</label><br>
                          </form>
                    </div>
                    <div class="price">
                        <h4>$2.20</h4>
                        <h4>$5.50</h4>
                        <h4>$9.50</h4>
                        <h4>$12.50</h4>
                    </div>
               </div>
            </div>
        </div>
        <!-- <div class="right_con_info"></div> -->
        <div class="right_con">
            <div class="sub_right">
                <h4>Suumary(1item)</h4>
                <div class="list">
                    <div class="left_text">
                        <p>Subtotal</p>
                        <p>Shipping</p>
                        <p>EsL Taxs</p>
                    </div>
                    <div class="right_num">
                        <h4>$20.20</h4>
                        <h4>-</h4>
                        <h4>-</h4>
                    </div>
                </div>
                <hr style="background-color: white; width:90%">
                <div class="dis_code">
                    <p>Gift card or discound code</p>
                    <form action="">
                        <input type="text" name="discount code" id="code">
                        <button>Appy</button>
                    </form>
                </div>
                <hr style="background-color: white; width:90%">
                <div class="total">
                    <div class="text"><h3>Total</h3></div>
                    <div class="num"><h4>$20.20</h4></div>
                    
                </div>
            </div>
        </div>
    </div>
<!-- ////////////////////////// -->
<div class="con_in">
        <div class="left_con_info">
            <div class="sub_info">
                <hr>
                <div class="text_info">
                    <p style="color: #ffa500;">Shipping Address<span> 12 Word Point Road, Rood, Mishauken, NY 1200</span></p>
                    <div class="edit">Edit</div>
                </div>
                <hr>
                <div class="text_info">
                    <p style="color: #ffa500;">Shipping Method<span> 12 Word Point Road, Rood, Mishauken, NY 1200</span></p>
                        <div class="edit">Edit</div>
                </div>
                <hr>
                <p style="padding-top: 40px;">Payment Method</p>
                <form action="">
                    <input type="text" name="" id="card_num" placeholder="Card number">
                    <input type="text" name="" id="name_card" placeholder="Name on card">
                    <input type="date" name="" id="date">
                    <input type="text" name="" id="cvv">
                </form>
                <div class="b_addr">
                    <p>Billing Address</p>
                    <form action="">
                        <button>
                            <input type="radio" id="html" name="fav_language" value="HTML">
                            <label for="html">Same as shipping address</label>
                        </button>
                        <button>
                            <input type="radio" id="html" name="fav_language" value="HTML">
                            <label for="html">Use a different billing address</label>
                        </button>
                    </form>
                </div>
                <div class="rem_me">
                    <p>Remember Me</p>
                    <form action="">
                        <button>
                            <input type="checkbox" id="html" name="fav_language" value="HTML">
                            <label for="html">Save my information for a faster checkout</label>
                        </button>
                    </form>
                </div>
            </div>
        </div>
        <!-- <div class="right_con_info"></div> -->
        <div class="righ_con">
            <div class="sub_right">
                <h4>Suumary(1item)</h4>
                <div class="list">
                    <div class="left_text">
                        <p>Subtotal</p>
                        <p>Shipping</p>
                        <p>EsL Taxs</p>
                    </div>
                    <div class="right_num">
                        <h4>$20.20</h4>
                        <h4>-</h4>
                        <h4>-</h4>
                    </div>
                </div>
                <hr style="background-color: white; width:90%">
                <div class="dis_code">
                    <p>Gift card or discound code</p>
                    <form action="">
                        <input type="text" name="discount code" id="code">
                        <button>Appy</button>
                    </form>
                </div>
                <hr style="background-color: white; width:90%">
                <div class="total">
                    <div class="text"><h3>Total</h3></div>
                    <div class="num"><h4>$20.20</h4></div>
                </div>
            </div>
        </div>
    </div>
     <!-- ////////////////////// -->
     <div class="left_con">
        <div class="left_con_info">
            <div class="sub_info">
                <hr>
                <div class="text_info">
                    <p>Your order is comfirmed.</p>
                    <p>We’ve accepted your order and we’re getting it ready.</p>
                </div>
                <hr>
                <p style="margin-top: 40px; font-weight: bold;">Customer Information</p>
                <div class="cu_info">
                    <div class="leaft_cu_info">
                        <p style="font-weight: bold;">Shipping Address</p>
                        <p style="color: #A3A2A2; font-size:15px;">Kenny Bostick</p>
                        <a href="http://"><p>12 Waldo Piont Road <br>Mishauken, NY 12000 <br>United States</p></a>
                        <p style="font-weight: bold; margin-top:40px;">Shipping Method</p>
                        <p style="color: #A3A2A2; font-size:15px; margin-top:10px;">UPS Ground (Fstimated ship <br> time of 3-6 days)</p>
                    </div>
                    <div class="right_cu_info">
                        <p style="font-weight: bold;">Builling Address</p>
                        <p style="color: #A3A2A2; font-size:15px;">Kenny Bostick</p>
                        <a href="http://"><p>12 Waldo Piont Road <br>Mishauken, NY 12000 <br>United States</p></a>
                        <p style="font-weight: bold; margin-top:40px;">Payment Method</p>
                        <p style="color: #A3A2A2; font-size:15px; margin-top:10px;">Ending in 312 -  $23.60</p>
                    </div>
                </div>
            </div>
        </div>
        <!-- <div class="right_con_info"></div> -->
        <div class="right_con">
            <div class="sub_right">
                <h4>Suumary(1item)</h4>
                <div class="list">
                    <div class="left_text">
                        <p>Subtotal</p>
                        <p>Shipping</p>
                        <p>EsL Taxs</p>
                    </div>
                    <div class="right_num">
                        <h4>$20.20</h4>
                        <h4>-</h4>
                        <h4>-</h4>
                    </div>
                </div>
                <hr style="background-color: white; width:90%">
                <div class="dis_code">
                    <p>Gift card or discound code</p>
                    <form action="">
                        <input type="text" name="discount code" id="code">
                        <button>Appy</button>
                    </form>
                </div>
                <hr style="background-color: white; width:90%">
                <div class="total">
                    <div class="text"><h3>Total</h3></div>
                    <div class="num"><h4>$20.20</h4></div>
                </div>
            </div>
        </div>
    </div>
</template>

<style>
@media (min-width: 1024px) {
  .checkout {
    min-height: 100vh;
  }
}
</style>
