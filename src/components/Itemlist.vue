<template>
    <div>
        Itemlist
        <div v-for="item in items" :key="item.name">
            <div class="item">
                <div class="name">名前:{{item.name}}</div>
                <div class="class">{{item.price}}円</div>
            </div>
        </div>
    </div>
</template>
<script>
export default{
    name:"Itemlist",
    data(){
        return{
            items:[
                {name:"りんご",price:100},
                {name:"たまご",price:160}
            ]
        }
    }
};
</script>

<style>
</style>