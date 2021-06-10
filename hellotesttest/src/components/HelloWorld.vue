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
              <p><button class="btn btn-primary">เพิ่มไปยังตะกร้า</button></p></div>
      </div>

      <div class="col-3 imagecontainer">
          <div class="photo">
            <img src="https://keyrincare.com/wp-content/uploads/2020/07/51jNORv6nQL._SX340_BO1204203200_.jpg" class="img-thumbnail" style="margin-right: 20px; height: 352px;" />
          </div>
            <div class="pricetext"><p class="name">แฮร์รี่ พอตเตอร์กับห้องแห่งความลับ</p> <span class="bgprice">100 บาท</span> <p><button class="btn btn-primary">เพิ่มไปยังตะกร้า</button></p></div>
      </div>

      <div class="col-3 imagecontainer">
          <div class="photo">
            <img src="https://images-na.ssl-images-amazon.com/images/I/81lAPl9Fl0L.jpg" class="img-thumbnail" style="margin-right: 20px; height: 352px;" />
          </div>
            <div class="pricetext"><p class="name">แฮร์รี่ พอตเตอร์กับนักโทษแห่งอัซคาบัน</p> <span class="bgprice">100 บาท</span> <p><button class="btn btn-primary">เพิ่มไปยังตะกร้า</button></p></div>
      </div>

      <div class="col-3 imagecontainer">
          <div class="photo">
            <img src="https://prodimage.images-bn.com/pimages/9780439139601_p0_v1_s550x406.jpg" class="img-thumbnail" style="margin-right: 20px; height: 352px;" />
          </div>
            <div class="pricetext"><p class="name">แฮร์รี่ พอตเตอร์กับถ้วยอัคนี</p> <span class="bgprice">100 บาท</span> <p><button class="btn btn-primary">เพิ่มไปยังตะกร้า</button></p></div>
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
            <div class="pricetext"><p class="name">แฮร์รี่ พอตเตอร์กับภาคีนกฟีนิกซ์</p> <span class="bgprice">100 บาท</span> <p><button class="btn btn-primary">เพิ่มไปยังตะกร้า</button></p></div>
        </div>
      <div class="col-3 imagecontainer">
        <div class="photo">
          <img src="https://images-na.ssl-images-amazon.com/images/I/61sXBXmAWML.jpg" class="img-thumbnail" style="margin-right: 20px; height: 352px;" />
        </div>
         <div class="pricetext"><p class="name">แฮร์รี่ พอตเตอร์กับเจ้าชายเลือดผสม</p> <span class="bgprice">100 บาท</span> <p><button class="btn btn-primary">เพิ่มไปยังตะกร้า</button></p></div>
      </div>
      <div class="col-3 imagecontainer">
        <div class="photo">
          <img src="https://images-na.ssl-images-amazon.com/images/I/71sH3vxziLL.jpg" class="img-thumbnail" style="margin-right: 20px; height: 352px;" />
        </div>
         <div class="pricetext"><p class="name">แฮร์รี่ พอตเตอร์กับเครื่องรางยมทูต</p> <span class="bgprice">100 บาท</span> <p><button class="btn btn-primary">เพิ่มไปยังตะกร้า</button></p></div>

      </div>
      
    
    </div>
    

    

  </div>

    
</template>

<script lang="ts">
import { ref, defineComponent } from 'vue'
export default defineComponent({
  name: 'HelloWorld',
  props: {
    msg: {
      type: String,
      required: true
    }
  },
  setup: () => {
    const count = ref(0)
    return { count }
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
</style>
