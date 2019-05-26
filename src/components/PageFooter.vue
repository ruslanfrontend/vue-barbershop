<template>
    <footer class="page-footer">
        <div class="container footer-inner">
            <div class="footer-contacts">
                <p>БАРБЕРШОП «БОРОДИНСКИЙ»</p>
                <p>АДРЕС: Г. САНКТ-ПЕТЕРБУРГ, УЛ. Б. КОНЮШЕННАЯ, Д. 19/8</p>
                <p><a href="#">КАК НАС НАЙТИ?</a></p>
                <p>ТЕЛЕФОН: +7 (495) 666-02-66</p>
            </div>

            <div class="footer-social">
                <h3>ДАВАЙТЕ ДРУЖИТЬ!</h3>
            </div>

            <div class="footer-dev">
                <h3>РАЗРАБОТАНО:</h3>
                <a href="#">HTML ACADEMY</a>
            </div>
        </div>
    </footer>
</template>

<script>
    export default {
        name: "PageFooter"
    }
</script>

<style lang="scss" scoped>
    @import url('https://fonts.googleapis.com/css?family=PT+Sans+Narrow:400,700&display=swap');

    .page-footer {
        background-color: #222222;
        color: #ffffff;
    }

    .footer-inner {
        display: flex;
        padding-top: 64px;
        padding-bottom: 45px;
        h3 {
            font-family: 'PT Sans Narrow', sans-serif;
            font-size: 14px;
        }
    }

    .footer-contacts {
        p {
            font-family: 'PT Sans Narrow', sans-serif;
            font-size: 14px;
            font-weight: Bold;

            a {
                color: #ffffff;
                &:hover {
                    text-decoration: none;
                }
            }
        }
    }

    .footer-social {
        margin-left: 92px;
    }

    .footer-dev {
        margin-left: auto;
        width: 140px;
        text-align: center;
        h3 {
            font-family: 'PT Sans Narrow', sans-serif;
            font-size: 14px;
            font-weight: bold;
        }

        a {
            text-decoration: none;
            color: #ffffff;
            font-family: 'PT Sans Narrow', sans-serif;
            font-size: 14px;
            font-weight: bold;
            background-color: #000000;
            display: block;
            padding-top: 11px;
            padding-bottom: 11px;


            &:hover {
                text-decoration: underline;
            }
        }
    }
</style>