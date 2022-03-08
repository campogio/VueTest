<template>
  <div id="app">

    <MyHeader/>
    <MyMain/> 
    <MyFooter/>   
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue';
import MyMain from './components/MyMain.vue';
import MyFooter from './components/MyFooter.vue';


export default {
  name: 'App',
  components: {
    MyHeader,
    MyMain,
    MyFooter
    
  },data(){
    return{
      listItem: [
            'home',
            'about',
            'service',
            'work',
            'articles'
        ],
        counter:0,
        position:0,
        interval:'',
        testimonial: [
            {
                name:'HARRY SMITH • NEW HOME OWNER',
                text: '“No man but feels more of a man in the world if he have but a bit of ground that he can call his own. However small it is on the surface, it is four thousand miles deep; and that is a very handsome property.”',
                photo: 'img/home-testimonial-113165296.jpg'
            },
            {
                name:'JOHN DOE • PROPERTY INVESTOR',
                text: '“Many novice real estate investors soon quit the profession and invest. When you invest in real estate, you often see a side of humanity that stocks, bonds, mutual funds, and saving money shelter you from.”',
                photo: 'img/home-testimonial-84268399.jpg'
            }
        ]
    }
     
  },
    created(){
        this.interval = setInterval(this.next, 6000);
    },
    methods:{
        statusActive(i){
            this.counter= i;
        },

        next(){
            (this.position == this.testimonial.length - 1) ? this.position = 0 : this.position++
        },
        circle(index){
            this.position = index;
        }
    }
}

</script>

<style lang="scss">
/* REGOLE GENERALI */
ul{
    list-style: none;
}
a{
    text-decoration: none;
    text-transform: uppercase;
    color: #666665;
}
h1{
    color: #fff;
    text-transform: uppercase;
    font-size: 3em;
}
.btn{
    background-color: #f9d03f;
    font-size: 0.7em;
    letter-spacing: 1.1px;
}
</style>