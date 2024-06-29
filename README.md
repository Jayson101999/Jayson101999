</head>
 <body>
<div class="container">
<div class="row">
<div class="col-12 text-center">
<h2>IPHONE STORE</h2>
<hr class="hr" />
</div>
</div>
<div class="row">
<div class="col-4 text-center">
<label id="product1"> iPhone 13 512GB Blue - Apple (PH) </label>
<img src="image.png" style="width: 400px;height:500px;" class="img-thumbnail"/><br>
<label for="product1" id="price1">2000.00</label>
<input type="number" class="form-control" id="qty1" placeholder="Enter quantity"/><br>
</div>
<div class="col-4 text-center">
<label id="product2"> Samsung S22</label>
<img src="images/s22.png" style="width: 400px;height:500px;" class="img-thumbnail"/><br>
<label for="product2" id="price2">37000.00</label>
<input type="number" class="form-control" id="qty2" placeholder="Enter quantity"/><br>
</div>
<div class="col-4">
<label for="carts"> Orders </label<br>
<textarea class="form-control" rows="29" id="carts" cols="200" readonly style="width:350px;height: 400;font-size: 12px;"> </textarea>
<input type="text" class="form-control border-0" id="total" readonly placeholder="Total"/> <input type="number" class="form-control" id="cash" placeholder="Cash Tendered"/>
<input type="text" class="form-control border-0" id="change" readonly placeholder="Change"/>
</div>
</div>
</div>
<script src="app.js"></script>
</body>
