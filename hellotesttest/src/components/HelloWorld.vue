<template>
  <div class="img1" style="margin-top:;">
    <div><h1>น า ย ดิ น S t o r e</h1></div>
    
    <div class="row">

      <div class="col-3 imagecontainer">
          <div class="photo">
            <img src="https://images-se-ed.com/ws/Storage/Originals/978059/035/9780590353427L.gif?h=243734e918edacf628e9216a70b2b5fd" class="img-thumbnail" style="height: 352px;" />
          </div>
            <div class="pricetext">
              <p class="name">แฮร์รี่ พอตเตอร์กับศิลาอาถรรพ์</p> 
              <span class="bgprice">100 บาท</span> 
              <p ><input v-model="count[1]" type="text" class="form-control" aria-label="Amount (to the nearest dollar)" />
              <button class="btn btn-primary " @click="addToBasket (1,'แฮรี่พอตเตอร์กับศิลาอาถรรพ์',100,count[1])">เพิ่มไปยังตะกร้า</button>
              </p></div>
      </div>

      <div class="col-3 imagecontainer">
          <div class="photo">
            <img src="https://keyrincare.com/wp-content/uploads/2020/07/51jNORv6nQL._SX340_BO1204203200_.jpg" class="img-thumbnail" style="margin-right: 20px; height: 352px;" />
          </div>
            <div class="pricetext"><p class="name">แฮร์รี่ พอตเตอร์กับห้องแห่งความลับ</p> <span class="bgprice">100 บาท</span> <p>
              <input v-model="count[2]" type="text" class="form-control" aria-label="Amount (to the nearest dollar)" />
              <button class="btn btn-primary " @click="addToBasket (2,'แฮร์รี่ พอตเตอร์กับห้องแห่งความลับ',100,count[2])">เพิ่มไปยังตะกร้า</button>
              </p>
              </div>
      </div>

      <div class="col-3 imagecontainer">
          <div class="photo">
            <img src="https://images-na.ssl-images-amazon.com/images/I/81lAPl9Fl0L.jpg" class="img-thumbnail" style="margin-right: 20px; height: 352px;" />
          </div>
            <div class="pricetext"><p class="name">แฮร์รี่ พอตเตอร์กับนักโทษแห่งอัซคาบัน</p> <span class="bgprice">100 บาท</span> <p >
              <input  v-model="count[3]" type="text" class="form-control" aria-label="Amount (to the nearest dollar)" />
              <button class="btn btn-primary " @click="addToBasket (3,'แฮร์รี่ พอตเตอร์กับนักโทษแห่งอัซคาบัน',100,count[3])">เพิ่มไปยังตะกร้า</button>
              </p>
              </div>
      </div>

      <div class="col-3 imagecontainer">
          <div class="photo">
            <img src="https://prodimage.images-bn.com/pimages/9780439139601_p0_v1_s550x406.jpg" class="img-thumbnail" style="margin-right: 20px; height: 352px;" />
          </div>
            <div class="pricetext"><p class="name">แฮร์รี่ พอตเตอร์กับถ้วยอัคนี</p> <span class="bgprice">100 บาท</span> <p>
              <input  v-model="count[4]" type="text" class="form-control" aria-label="Amount (to the nearest dollar)" />
              <button class="btn btn-primary " @click="addToBasket (4,'แฮร์รี่ พอตเตอร์กับถ้วยอัคนี',100,count[4])">เพิ่มไปยังตะกร้า</button>
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
            <div class="pricetext"><p class="name">แฮร์รี่ พอตเตอร์กับภาคีนกฟีนิกซ์</p> <span class="bgprice">100 บาท</span> <p>
              <input  v-model="count[5]" type="text" class="form-control" aria-label="Amount (to the nearest dollar)" />
              <button class="btn btn-primary " @click="addToBasket (5,'แฮร์รี่ พอตเตอร์กับภาคีนกฟีนิกซ์',100,count[5])">เพิ่มไปยังตะกร้า</button>
              </p>
              </div>
        </div>
      <div class="col-3 imagecontainer">
        <div class="photo">
          <img src="https://images-na.ssl-images-amazon.com/images/I/61sXBXmAWML.jpg" class="img-thumbnail" style="margin-right: 20px; height: 352px;" />
        </div>
         <div class="pricetext"><p class="name">แฮร์รี่ พอตเตอร์กับเจ้าชายเลือดผสม</p> <span class="bgprice">100 บาท</span> <p>
           <input  v-model="count[6]" type="text" class="form-control" aria-label="Amount (to the nearest dollar)" />
           <button class="btn btn-primary " @click="addToBasket (6,'แฮร์รี่ พอตเตอร์กับเจ้าชายเลือดผสม',100,count[6])">เพิ่มไปยังตะกร้า</button>
           </p>
           </div>
      </div>
      <div class="col-3 imagecontainer">
        <div class="photo">
          <img src="https://images-na.ssl-images-amazon.com/images/I/71sH3vxziLL.jpg" class="img-thumbnail" style="margin-right: 20px; height: 352px;" />
        </div>
         <div class="pricetext"><p class="name">แฮร์รี่ พอตเตอร์กับเครื่องรางยมทูต</p> <span class="bgprice">100 บาท</span> <p>
           <input v-model="count[7]" type="text" class="form-control" aria-label="Amount (to the nearest dollar)" />
           <button class="btn btn-primary " @click="addToBasket (7,'แฮร์รี่ พอตเตอร์กับเครื่องรางยมทูต',100,count[7])">เพิ่มไปยังตะกร้า</button>
           </p>
           </div>

      </div>
      
    
    </div>
    <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
  สินค้าในตะกร้า
</button>

<!-- Modal -->
<div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
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
            <th scope="col">id</th>
            <th scope="col">name</th>
            <th scope="col">price</th>
            <th scope="col">count</th>
            </tr>
        </thead>
            
        <tbody>
      <tr v-for="(item, i) in data" :key="i">
        <td>{{item.id}}</td>
        <td>{{item.name}}</td>
        <td>{{item.price}}</td>
        <td>{{item.count}}</td>
      </tr>
    </tbody>
          
         
      </table>
      <div class="row">รวม {{countBooks}} เล่ม</div>
    <div class="row">ราคารวม {{totalPrice}}บาท</div>
    <div class="row">ส่วนลด {{discount}} บาท</div>
    <div class="row">รวมสุทธิ {{totalPrice-discount}} บาท</div>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
</div>
    

    

  </div>

    
</template>

<script>
import { ref, defineComponent,reactive } from 'vue'
export default defineComponent({
  name: 'HelloWorld',
  props: {
    msg: {
      type: String,
      required: true
    }
  },
  setup: () => {
    
    const count = reactive([])
    const data = reactive([])
    const totalPrice = ref(0);
    const countBooks = ref(0);
    const discount = ref(0);

    
    function addToBasket(id , name , price,count ) {
      const d = {
        id,
        name,
        price,
        count
      };
      data.push(d);
      let p=0
      data.forEach((e) => {
      p += e.price * e.count;
    });
      totalPrice.value = p
      let book=0
      data.forEach((e) => ( book += Number.parseInt(e.count)));
      countBooks.value = book

    let min = 99999;
    data.forEach((e) => {
      if (e.count < min) min = e.count;
    });
  
    const booksNotSame = data.length;
    const discountPercent = 10 * (booksNotSame - 1);
    discount.value = discountPercent * booksNotSame * min;
      console.log(data);
    }
    
    return { count,data,addToBasket,totalPrice, countBooks, discount }
  }
})
</script>

<style scoped>
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
