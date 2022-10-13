<template>
    <section class="main-title">
        <div class="container">
            <h2>Latest episodes</h2>
            <button class="btn">View all episodes</button>
        </div>
    </section>
</template>

<script>
import "../assets/media.css"
export default {

}
</script>

<style lang="scss">
    .main-title{
        margin-bottom: 66px;
        .container{
            display: flex;
            justify-content: space-between;
            align-items: center;
            h2{
                color: white;
                font-weight: 400;
                font-size: 64px;
                line-height: 79.2px;
                letter-spacing: 2.88px;
            }
            .btn{
                padding: 12px;
                font-weight: 400;
                font-size: 17px;
                line-height: 27px;
                color: white;
                border: none;
                background: #118DA8;
                border-radius: 6px;
            }
        }
    }
</style>