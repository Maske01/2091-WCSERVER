<template>
    <div class="blog">
        <h1>{{title}}</h1>
        <div class="bloginfo">
            <h1>Music</h1>
            <img id="pic" src="https://images.unsplash.com/photo-1605020420620-20c943cc4669?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8OXx8Z3VpdGFyfGVufDB8fDB8fA%3D%3D&w=1000&q=80" alt="Guitar"> <br>
            <p>Playing the guitar holds a special place in my heart, allowing myself to expres and connect with others <br> through music. I loves the guitar's sense of power, which gives me a sense of confidence and strength <br> that is unmatched by any other instrument. The guitar allows me to channel my emotions into the music, <br> and its technical intricacy challenges me to constantly improve my skills. Playing the guitar allows <br> me to connect with others, creating bonds that go beyond words.</p>
        </div>

        <div class="bloginfo">
            <h1>Basketball</h1>
            <img id="pic" src="https://d2560u4h06m0te.cloudfront.net/images/2022/1/1/121818_003_basket.JPG" alt="Basketball"> <br>
            <p>As a basketball enthusiast, I can confidently say that basketball is my favorite sport. The fast-paced and dynamic <br>nature of the game keeps me on the edge of my seat and makes it an exciting experience every time I watch or<br> play it. Also, as an IT student playing basketball can also serve as my stress reliever, which is particularly beneficial for <br> me who may be under high levels of stress due to academic demands or long hours in <br> front of a computer screen. Taking a break to play basketball and engage in physical activity helps me recharge <br>and refresh my minds, leading to increased productivity and better academic performance.</p>
        </div>

        <div class="bloginfo">
            <h1>Programming</h1>
            <img id="pic" src="https://f.hubspotusercontent10.net/hubfs/6448316/web-programming-languages.jpg" alt="Programming"> <br>
            <p>Programming is a field that has always fascinated me. From an early age, I was drawn to the<br> logical and creative aspects of coding, as well as the satisfaction that comes from seeing a project come to life <br>through code.Programming allows me to be creative and express myself in a unique way. <br>Coding is like writing poetry in a language that only computers can understand. With each line <br>of code, I am able to bring my ideas to life and create something that is uniquely my own.My very reason <br>for liking this field is because of my father, he's the reason why i'm taking this path.</p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'blog',
    data () {
        return{
            title: 'Blog'
        }
    }
}
</script>

<style scoped>

.bloginfo{
    margin: 50px 100px;
    background-color: #c9bfbf ;
}

#pic{
    width: 430px;
    margin-top: 10px;
}

p{
    margin-top: 30px;
}


</style>