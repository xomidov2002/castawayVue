<template>
	<div class="form">
        <div class="subscribe">
            <a href="#">Email Newsletter</a>
            <h2 class="title">Subscribe for updates</h2>
        </div>
        <form>
            <input type="text" placeholder="Name">
            <input type="email" placeholder="Email">
            <button class="btn">Submit</button>
        </form>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
    .form{
        border-radius: 32px;
        margin-top: 200px;
        padding: 60px;
        background: #000;
        display: flex;
        justify-content: space-between;
        align-items: center;
        .subscribe{
            background: #000;
            a{
                background: #000;
                color: #118DA8;
                font-weight: 400;
                font-size: 18px;
                line-height: 27px;
            }
            .title{
                background: #000;
                color: #fff;
                font-weight: 400;
                font-size: 72px;
                line-height: 79.2px;
                letter-spacing: 2.88px;
                max-width: 431px;
            }
        }
        form{
            background: #000;
            display: flex;
            flex-direction: column;
            gap: 20px;
            align-items: flex-start;
            input{
                padding: 26px 19px;
                width: 100%;
                max-width: 533px;
                border: none;
                outline: none;
                color: rgb(255, 255, 255, 0.7);
                border-radius: 6px;
                font-weight: 400;
                font-size: 24px;
                line-height: 28.8px;
            }
            .btn{
                padding: 10px 19px;
                background: #118DA8;
                border-radius: 6px;
                border: none;
                color: #fff;
                font-weight: 700;
                font-size: 15px;
                line-height: 28.8px;
            }
        }
    }
</style>