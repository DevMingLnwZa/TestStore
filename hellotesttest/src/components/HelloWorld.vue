<template>
  <div class="img1" style="margin-top:;">
    <div><h1>น า ย ดิ น S t o r e</h1></div>
    
    <div class="row">

      <div class="col-3 imagecontainer">
          <div class="photo">
            <img src="https://images-se-ed.com/ws/Storage/Originals/978059/035/9780590353427L.gif?h=243734e918edacf628e9216a70b2b5fd" class="img-thumbnail" style="height: 352px;" />
          </div>
            <div class="pricetext">
              <p class="name">แฮร์รี่พอตเตอร์กับศิลาอาถรรพ์</p> 
              <span class="bgprice">100 บาท</span> 
              <p> 
                <!-- <input v-model="count[1]" type="text" class="form-control" aria-label="Amount (to the nearest dollar)" /> -->
              <button class="btn btn-primary ">เพิ่มไปยังตะกร้า</button>
              </p></div>
      </div>

      <div class="col-3 imagecontainer">
          <div class="photo">
            <img src="https://keyrincare.com/wp-content/uploads/2020/07/51jNORv6nQL._SX340_BO1204203200_.jpg" class="img-thumbnail" style="margin-right: 20px; height: 352px;" />
          </div>
            <div class="pricetext"><p class="name">แฮร์รี่พอตเตอร์กับห้องแห่งความลับ</p>
            <span class="bgprice">100 บาท</span> 
            <p>
              <!-- <input v-model="count[2]" type="text" class="form-control" aria-label="Amount (to the nearest dollar)" /> -->
            <button class="btn btn-primary ">เพิ่มไปยังตะกร้า</button>
            </p>
            </div>
      </div>

      <div class="col-3 imagecontainer">
          <div class="photo">
            <img src="https://images-na.ssl-images-amazon.com/images/I/81lAPl9Fl0L.jpg" class="img-thumbnail" style="margin-right: 20px; height: 352px;" />
          </div>
            <div class="pricetext"><p class="name">แฮร์รี่พอตเตอร์กับนักโทษแห่งอัซคาบัน</p> <span class="bgprice">100 บาท</span>
            <p >
              <!-- <input  v-model="count[3]" type="text" class="form-control" aria-label="Amount (to the nearest dollar)" /> -->
            <button class="btn btn-primary ">เพิ่มไปยังตะกร้า</button>
            </p>
            </div>
      </div>

      <div class="col-3 imagecontainer">
          <div class="photo">
            <img src="https://prodimage.images-bn.com/pimages/9780439139601_p0_v1_s550x406.jpg" class="img-thumbnail" style="margin-right: 20px; height: 352px;" />
          </div>
            <div class="pricetext"><p class="name">แฮร์รี่พอตเตอร์กับถ้วยอัคนี</p> <span class="bgprice">100 บาท</span>
            <p>
              <!-- <input  v-model="count[4]" type="text" class="form-control" aria-label="Amount (to the nearest dollar)" /> -->
            <button class="btn btn-primary ">เพิ่มไปยังตะกร้า</button>
            </p>
            </div>
      </div>
    </div>
    <div class="space">
      <p></p>
    </div>
      <div class="row" style="margin-top: 50px">

        <div class="col-3 imagecontainer">
          <div class="photo">
            <img src="https://images-na.ssl-images-amazon.com/images/I/91TpLHDnuFL.jpg" class="img-thumbnail" style="height: 352px;" />
          </div>
            <div class="pricetext"><p class="name">แฮร์รี่พอตเตอร์กับภาคีนกฟีนิกซ์</p> <span class="bgprice">100 บาท</span>
            <p>
              <!-- <input  v-model="count[5]" type="text" class="form-control" aria-label="Amount (to the nearest dollar)" /> -->
            <button class="btn btn-primary ">เพิ่มไปยังตะกร้า</button>
            </p>
            </div>
        </div>
      <div class="col-3 imagecontainer">
        <div class="photo">
          <img src="https://images-na.ssl-images-amazon.com/images/I/61sXBXmAWML.jpg" class="img-thumbnail" style="margin-right: 20px; height: 352px;" />
        </div>
         <div class="pricetext"><p class="name">แฮร์รี่พอตเตอร์กับเจ้าชายเลือดผสม</p>
          <span class="bgprice">100 บาท</span> 
          <p>
            <!-- <input  v-model="count[6]" type="text" class="form-control" aria-label="Amount (to the nearest dollar)" /> -->
          <button class="btn btn-primary">เพิ่มไปยังตะกร้า</button>
          </p>
          </div>
      </div>
      <div class="col-3 imagecontainer">
        <div class="photo">
          <img src="https://images-na.ssl-images-amazon.com/images/I/71sH3vxziLL.jpg" class="img-thumbnail" style="margin-right: 20px; height: 352px;" />
        </div>
         <div class="pricetext"><p class="name">แฮร์รี่พอตเตอร์กับเครื่องรางยมทูต</p> 
         <span class="bgprice">100 บาท</span> 
          <p>
            <!-- <input v-model="count[7]" type="text" class="form-control" aria-label="Amount (to the nearest dollar)" /> -->
          <button class="btn btn-primary">เพิ่มไปยังตะกร้า</button>
          </p>
           </div>
      </div>
      
    
    </div>
    <!-- #examplemodal คือการเรียกใช้ ID=examplemodal-->
    <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
  สินค้าในตะกร้า
</button>

<!-- Modal-Cart -->
<div class="modal fade" id="exampleModal" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Cart</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
       <table class="table">
        <thead>
            <tr>
              <!-- scope คือแอตทริบิวต์กำหนดวิธีการที่จะเชื่อมโยงเซลล์ส่วนหัวและเซลล์ข้อมูลในตาราง -->
              <!-- scope=”col” นั้นใส่เพื่อบอกว่า คอลัมภ์ด้านล่างคือ ข้อมูล ของ head นี้ -->
            <th scope="col">id</th>
            <th scope="col">name</th>
            <th scope="col">price</th>
            <th scope="col">count</th>
            </tr>
        </thead>
            
        <tbody>
      <tr>

      </tr>
    </tbody>
          
         
      </table>
      <!-- class=row คือการสร้างแถว -->
      <div class="row">รวม 0 เล่ม</div>
    <div class="row">ราคารวม 0 บาท</div>
    <div class="row">ส่วนลด 0 บาท</div>
    <div class="row">รวมสุทธิ 0 บาท</div>
      </div>
      <div class="modal-footer">
        <!-- กำหนด class="btn btn-รูปแบบ" -->
        <!-- data-bs-dismiss="modal"คือการปิดหน้าต่าง modal -->
        <button type="button" class="btn btn-danger" data-bs-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
</div>
  </div>

    
</template>

// <script>
// import { ref, defineComponent,reactive } from 'vue'
// export default defineComponent({
//   name: 'HelloWorld',
//   props: {
//     msg: {
//       type: String,
//       required: true
//     }
//   },
//   setup: () => {
    
//     const count = reactive([])
//     const data = reactive([])
//     const totalPrice = ref(0);
//     const countBooks = ref(0);
//     const discount = ref(0);

    
//     function addToBasket(id , pricname , e,count ) {
//       const d = {
//         id,
//         name,
//         price,
//         count
//       };
//       data.push(d);
//       let p=0
//       data.forEach((e) => {
//       p += e.price * e.count;
//     });
//       totalPrice.value = p
//       let book=0
//       data.forEach((e) => ( book += Number.parseInt(e.count)));
//       countBooks.value = book

//     let min = 99999;
//     data.forEach((e) => {
//       if (e.count < min) min = e.count;
//     });
  
//     const booksNotSame = data.length;
//     const discountPercent = 10 * (booksNotSame - 1);
//     discount.value = discountPercent * booksNotSame * min;
//       console.log(data);
//     }
    
//     return { count,data,addToBasket,totalPrice, countBooks, discount }
//   }
// })
// </script>

<style>
a {
  color: #42b983;
}

label {
  margin: 0 0.5em;
  font-weight: bold;
}

code {
  background-color: #eee;
  padding: 2px 4px;
  border-radius: 4px;
  color: #304455;
}
.image1{
  display: block;
}
.imagecontainer{
  text-align: center;
}
.pricetext{
  color: black;
}
.bgprice{
  background-color: white;
  padding-left: 10px;
  padding-right: 10px;
  padding-top: 5px;
  padding-bottom: 5px;
  border-radius: 20px;
  margin-bottom: 5px;
}
.photo{
  margin-bottom: 10px
}
.name{
  color: white;
}
.row{
  color: black;
}
.modal-title{
  color:black;
}
</style>
