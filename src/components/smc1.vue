<template>
    <ul>
        <li v-for="(item,index) in items" :key="index">
            {{index}}-{{item.message}}
        </li>
    </ul>
</template>
<script>
export default {
    name:'smc11',
    data:function(){
        return {
            d1:'smc1',
            d2:'cjj',
            items:[
                {message:'Foo'},
                {message:'Foo1'},
                {message:'Foo2'},
                {message:'Foo3'},
            ]
        };
    }
}
</script>
