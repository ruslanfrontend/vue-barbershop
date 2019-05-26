<template>
    <header class="page-header">
        <div class="container header-inner">
            <ul class="header-menu">
                <li class="header-menu">
                    <a href="" class="header-menu">ИНФОРМАЦИЯ</a>
                </li>
                <li class="header-menu">
                    <a href="" class="header-menu">НОВОСТИ</a>
                </li>
                <li class="header-menu">
                    <a href="" class="header-menu">ПРАЙС-ЛИСТ</a>
                </li>
                <li class="header-menu">
                    <a href="" class="header-menu">МАГАЗИН</a>
                </li>
                <li class="header-menu">
                    <a href="" class="header-menu">КОНТАКТЫ</a>
                </li>
            </ul>

            <button class="login">ВХОД</button>
        </div>
    </header>
</template>

<script>
    export default {
        name: "PageHeader"
    }
</script>

<style scoped>
    @import url('https://fonts.googleapis.com/css?family=PT+Sans+Narrow:400,700&display=swap');

    .page-header {
        background-color: #000;
        height: 72px;
        color: #ffffff;
    }

    .header-inner {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding-left: 17px;
        padding-right: 17px;
        height: 100%;
    }

    .header-menu {
        display: flex;
        color: #ffffff;
        text-decoration: none;
        padding: 0;
        justify-content: space-between;
        font-family: 'PT Sans Narrow', sans-serif;
    }

    .header-inner ul {
        width: 500px;
    }

    .header-menu a {
        font-size: 16px;
    }

    .login {
        background-color: #000000;
        border: none;
        color: #ffffff;
        font-family: 'PT Sans Narrow', sans-serif;
        font-size: 16px;
        position: relative;
    }

    .login::before {
        content:"";
        background-image: url("../assets/login.png");
        position: absolute;
        left: -30px;
        top: 50%;
        opacity: 0.3;
        transform: translateY(-50%);
        height: 14px;
        width: 14px;
    }

</style>