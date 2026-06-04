<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ALDO GITAR - Toko Online</title>

<link rel="stylesheet"
href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}

body{
    background:#f4f4f4;
}

/* HEADER */

header{
    background:linear-gradient(135deg,#0033cc,#00aaff);
    padding:15px 50px;
    position:sticky;
    top:0;
    z-index:999;
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    color:white;
    text-decoration:none;
    font-size:28px;
    font-weight:bold;
}

.nav-links{
    display:flex;
    list-style:none;
    gap:20px;
}

.nav-links a{
    color:white;
    text-decoration:none;
    font-weight:bold;
}

.cart-icon{
    position:relative;
    color:white;
    font-size:24px;
    cursor:pointer;
}

#cart-count{
    position:absolute;
    top:-10px;
    right:-12px;
    background:red;
    width:20px;
    height:20px;
    border-radius:50%;
    display:flex;
    align-items:center;
    justify-content:center;
    font-size:12px;
    color:white;
}

/* HERO */

.hero{
    height:500px;
    background:
    linear-gradient(rgba(0,0,0,.5),rgba(0,0,0,.5)),
    url('aldo galeri/banner.jpg');
    background-size:cover;
    background-position:center;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    color:white;
}

.hero h1{
    font-size:60px;
    margin-bottom:15px;
}

.btn-primary{
    display:inline-block;
    margin-top:20px;
    padding:12px 25px;
    background:#00aaff;
    color:white;
    text-decoration:none;
    border-radius:5px;
}

/* PRODUK */

.product-section{
    padding:50px;
}

.product-section h2{
    text-align:center;
    margin-bottom:30px;
    color:#0033cc;
}

.product-grid{
    display:grid;
    grid-template-columns:
    repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.product-card{
    background:white;
    border-radius:10px;
    overflow:hidden;
    box-shadow:0 3px 10px rgba(0,0,0,.15);
    transition:.3s;
}

.product-card:hover{
    transform:translateY(-5px);
}

.product-image img{
    width:100%;
    height:250px;
    object-fit:cover;
}

.product-info{
    padding:15px;
}

.product-title{
    margin-bottom:10px;
}

.product-price{
    color:#0033cc;
    font-weight:bold;
    margin-bottom:10px;
}

.cart-btn{
    width:100%;
    border:none;
    padding:10px;
    background:#0033cc;
    color:white;
    border-radius:5px;
    cursor:pointer;
    font-weight:bold;
}

.cart-btn:hover{
    background:#002299;
}

/* SIDEBAR KERANJANG */

.cart-sidebar{
    position:fixed;
    right:-400px;
    top:0;
    width:400px;
    height:100%;
    background:white;
    box-shadow:-2px 0 10px rgba(0,0,0,.2);
    transition:.3s;
    z-index:1000;
    padding:20px;
    overflow-y:auto;
}

.cart-sidebar.active{
    right:0;
}

.cart-header{
    display:flex;
    justify-content:space-between;
    align-items:center;
    margin-bottom:20px;
}

.close-cart{
    cursor:pointer;
    font-size:22px;
}

.cart-item{
    border-bottom:1px solid #ddd;
    padding:10px 0;
}

.cart-item button{
    background:red;
    color:white;
    border:none;
    padding:5px 10px;
    cursor:pointer;
    border-radius:5px;
    margin-top:5px;
}

.total{
    margin-top:20px;
    font-size:20px;
    font-weight:bold;
    color:#0033cc;
}

/* WHATSAPP */

.whatsapp{
    position:fixed;
    bottom:20px;
    right:20px;
    width:60px;
    height:60px;
    background:#25D366;
    color:white;
    border-radius:50%;
    display:flex;
    justify-content:center;
    align-items:center;
    text-decoration:none;
    font-size:32px;
    z-index:999;
}

/* FOOTER */

footer{
    background:#0033cc;
    color:white;
    text-align:center;
    padding:20px;
    margin-top:50px;
}

.socials{
    list-style:none;
    display:flex;
    justify-content:center;
    gap:15px;
    margin-top:15px;
}

.socials a{
    color:white;
    font-size:20px;
}
.rating{
    color:#f5b301;
    font-weight:bold;
    margin-top:5px;
}

.sold{
    color:#555;
    font-size:14px;
    margin-top:3px;
}

.review{
    background:#f8f8f8;
    padding:8px;
    border-radius:5px;
    margin-top:8px;
    font-size:13px;
    color:#666;
}

</style>
</head>
<body>
<!-- HEADER -->

<header>
    <nav>
        <a href="#" class="logo">🎸 ALDO GITAR</a>

        <ul class="nav-links">
            <li><a href="#produk">Produk</a></li>
            <li><a href="#">Diskon</a></li>
            <li><a href="#">Tentang Kami</a></li>
        </ul>

        <div class="cart-icon" onclick="toggleCart()">
            <i class="fas fa-shopping-cart"></i>
            <span id="cart-count">0</span>
        </div>
    </nav>
</header>

<!-- HERO -->

<section class="hero">
    <div>
        <h1>ALDO GITAR</h1>
        <p>Dapatkan gitar terbaik dengan kualitas premium.</p>
        <a href="#produk" class="btn-primary">
            Belanja Sekarang
        </a>
    </div>
</section>

<!-- PRODUK -->

<section id="produk" class="product-section">

    <h2>Produk Gitar Terbaik</h2>

    <div class="product-grid">

        <!-- Produk 1 -->

        <div class="product-card">
            <div class="product-image">
                <img src="yamahaapxt2.jpg"
                alt="Yamaha APXT2">
            </div>

            <div class="product-info">
                <h3 class="product-title">
                    Yamaha APXT2
                </h3>

               <p class="product-price">
    Rp 2.500.000
</p>

<p>
    ⭐ 4.9/5
</p>

<p>
    🛒 Terjual 328+
</p>

<p style="font-size:14px;color:gray;">
    "Suara jernih dan nyaman dimainkan."
</p>

                <button class="cart-btn"
                onclick="tambahKeranjang('Yamaha APXT2',2500000)">
                    <i class="fas fa-cart-plus"></i>
                    Tambah ke Keranjang
                </button>
            </div>
			
        </div>

        <!-- Produk 2 -->

        <div class="product-card">
            <div class="product-image">
                <img src="subjero.jpg"
                alt="Subzero">
            </div>

            <div class="product-info">
                <h3 class="product-title">
                    Subzero
                </h3>

               <p class="product-price">
    Rp 4.000.000
</p>

<div class="rating">⭐⭐⭐⭐⭐ 4.8</div>
<div class="sold">🛒 Terjual 214+</div>
<div class="review">
"Body kokoh dan suara mantap."
</div>

                <button class="cart-btn"
                onclick="tambahKeranjang('Subzero',4000000)">
                    <i class="fas fa-cart-plus"></i>
                    Tambah ke Keranjang
                </button>
            </div>
			
        </div>

        <!-- Produk 3 -->

        <div class="product-card">
            <div class="product-image">
                <img src="apx600.jpg"
                alt="Yamaha APX 600">
            </div>

            <div class="product-info">
                <h3 class="product-title">
                    Yamaha APX 600
                </h3>

               <p class="product-price">
    Rp 3.500.000
</p>

<div class="rating">⭐⭐⭐⭐⭐ 4.9</div>
<div class="sold">🛒 Terjual 502+</div>
<div class="review">
"Favorit musisi akustik elektrik."
</div>

                <button class="cart-btn"
                onclick="tambahKeranjang('Yamaha APX 600',3500000)">
                    <i class="fas fa-cart-plus"></i>
                    Tambah ke Keranjang
                </button>
            </div>
			
        </div>

        <!-- Produk 4 -->

        <div class="product-card">
            <div class="product-image">
                <img src="tylor.jpg"
                alt="Taylor">
            </div>

            <div class="product-info">
                <h3 class="product-title">
                    Taylor
                </h3>

               <p class="product-price">
    Rp 41.600.000
</p>

<p>
    ⭐ 4.9/5
</p>

<div class="rating">⭐⭐⭐⭐⭐ 5.0</div>
<div class="sold">🛒 Terjual 96+</div>
<div class="review">
"Premium, suara sangat detail dan mewah."
</div>

                <button class="cart-btn"
                onclick="tambahKeranjang('Taylor',41600000)">
                    <i class="fas fa-cart-plus"></i>
                    Tambah ke Keranjang
                </button>
            </div>
        </div>

    </div>

</section>

<!-- SIDEBAR KERANJANG -->

<div class="cart-sidebar" id="cartSidebar">

    <div class="cart-header">
        <h2>Keranjang Belanja</h2>

        <span class="close-cart"
        onclick="toggleCart()">
            ✖
        </span>
    </div>

    <div id="cart-items">
        <p>Belum ada produk.</p>
    </div>

    <div class="total">
    Total:
    <span id="cart-total">
        Rp 0
    </span>
</div>

<br>

<button
onclick="checkoutWA()"
style="
width:100%;
padding:12px;
background:#25D366;
color:white;
border:none;
border-radius:5px;
font-weight:bold;
cursor:pointer;
">

<i class="fab fa-whatsapp"></i>
Checkout via WhatsApp

</button>

</div>

<!-- WHATSAPP -->

<a href="https://wa.me/6281572967104"
class="whatsapp"
target="_blank">

    <i class="fab fa-whatsapp"></i>

</a>

<!-- FOOTER -->

<footer>

    <h3>ALDO GITAR</h3>

    <p>
        Solusi Kebutuhan Gitar Anda
    </p>

    <br>

    <p>
        <i class="fas fa-phone"></i>
        0815-7296-7104
    </p>

    <p>
        <i class="fab fa-whatsapp"></i>
        0815-7296-7104
    </p>

    <ul class="socials">

        <li>
            <a href="#">
                <i class="fab fa-instagram"></i>
            </a>
        </li>

        <li>
            <a href="#">
                <i class="fab fa-facebook-f"></i>
            </a>
        </li>

        <li>
            <a href="#">
                <i class="fab fa-tiktok"></i>
            </a>
        </li>

    </ul>

    <p style="margin-top:15px;">
        &copy; 2026 ALDO GITAR.
        All Rights Reserved.
    </p>

</footer>
<script>

let keranjang = [];
let totalHarga = 0;

function toggleCart(){
    document
    .getElementById("cartSidebar")
    .classList.toggle("active");
}

function tambahKeranjang(nama,harga){

    keranjang.push({
        nama:nama,
        harga:harga
    });

    totalHarga += harga;

    updateKeranjang();
}

function hapusItem(index){

    totalHarga -= keranjang[index].harga;

    keranjang.splice(index,1);

    updateKeranjang();
}

function updateKeranjang(){

    let cartItems =
    document.getElementById("cart-items");

    let cartCount =
    document.getElementById("cart-count");

    let cartTotal =
    document.getElementById("cart-total");

    cartItems.innerHTML = "";

    if(keranjang.length === 0){

        cartItems.innerHTML =
        "<p>Belum ada produk.</p>";

    }else{

        keranjang.forEach((item,index)=>{

            cartItems.innerHTML += `
                <div class="cart-item">

                    <h4>${item.nama}</h4>

                    <p>
                        Rp ${item.harga.toLocaleString('id-ID')}
                    </p>

                    <button onclick="hapusItem(${index})">
                        Hapus
                    </button>

                </div>
            `;

        });

    }

    cartCount.innerText = keranjang.length;

    cartTotal.innerText =
    "Rp " +
    totalHarga.toLocaleString('id-ID');
}

/* CHECKOUT WHATSAPP */

function checkoutWA(){

    if(keranjang.length === 0){

        alert("Keranjang masih kosong!");

        return;
    }

    let pesan =
    "Halo ALDO GITAR,%0A%0ASaya ingin memesan:%0A";

    keranjang.forEach((item)=>{

        pesan +=
        "- " +
        item.nama +
        " (Rp " +
        item.harga.toLocaleString('id-ID') +
        ")%0A";

    });

    pesan +=
    "%0A*Total : Rp " +
    totalHarga.toLocaleString('id-ID') +
    "*";

    window.open(
    "https://wa.me/6281572967104?text=" + pesan,
    "_blank");

}

</script>
