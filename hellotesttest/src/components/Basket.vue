<template>
  <div>
      <h>Basket</h>
      <div class="container">
        <table class="table">
        <thead>
            <tr>
            <th scope="col">id</th>
            <th scope="col">name</th>
            <th scope="col">price</th>
            <th scope="col">count</th>
            </tr>
        </thead>
            
        <tbody></tbody>
          
         
      </table>
    <div class="row">รวม {{countBooks}} เล่ม</div>
    <div class="row">ราคารวม {{totalPrice}}บาท</div>
    <div class="row">ส่วนลด {{discount}} บาท</div>
    <div class="row">รวมสุทธิ {{totalPrice-discount}} บาท</div>
      </div>
     

  </div>
 
</template>

<script>
import{ defineComponent,ref} from "@vue/runtime-core";
export default defineComponent ({
    setup(){
        const data = [
            {
                id: '1',
                price: 100,
                name: 'Harrypotter 1',
                count: 2
            },
            {
                id: '2',
                price: 100,
                name: 'Harrypotter 1',
                count: 3
            },
            {
                id: '3',
                price: 100,
                name: 'Harrypotter 1',
                count: 1
            }, 
        ];
    const totalPrice = ref(0);
    data.forEach((e) => {
      totalPrice.value += e.price * e.count;
    });

    const countBooks = ref(0);
    data.forEach((e) => (countBooks.value += e.count));

    let min = 99999;
    data.forEach((e) => {
      if (e.count < min) min = e.count;
    });

    const discount = ref(0);
    const booksNotSame = data.length;
    const discountPercent = 10 * (booksNotSame - 1);
    discount.value = discountPercent * booksNotSame * min;

    return { totalPrice, countBooks, discount };
    },
})
</script>

<style scoped>
.table{
    color:white;
}

</style>