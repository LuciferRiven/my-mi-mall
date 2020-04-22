<template>
    <div class="footer">
        <div class="footer-logo">
            <img src="/imgs/logo-footer.png" alt="">
            <p>小米商城</p>
        </div>
        <div class="footer-link">
            <a href="">顾长安主页<span>|</span></a>
            <a href="">顾长安博客<span>|</span></a>
            <a href="">关于小米<span>|</span></a>
            <a href="">与我有关<span>|</span></a>
            <a href="">线下门店<span>|</span></a>
        </div>
        <div class="copright"> Select Location © mi.com 京ICP证110507号 京ICP备10046444号 京公网安备11010802020134号 京网文[2020]0276-042号</div>
    </div>
</template>

<script>
    export default{
        name:'nav-footer',
    }
</script>

<style lang="scss">
    .footer{
        height:234px;
        border-top:4px solid #FF6600;
        background-color:#333333;
        color:#999999;
        font-size:16px;
        text-align:center;
        .footer-logo{
            margin-top:46px;
            margin-bottom:31px;
            img{
                 width:53px;
                 height:36px;
                 margin-bottom:13px;
            }
             
        }
        .footer-link{
            a{
                color:#999999; 
                display:inline-block;
                span{
                    margin-left:4px;
                    margin-right:4px;
                }
            }
            margin-bottom:13px; 
        }
        
    }
</style>