<template>
    <footer class="footer bg-dark text-white p-3">
        <div class="container">
            <div class="row pt-5">
                <div class="col-md-2 text-center">
                    <img src="../../public/img/icons/favicon-32x32.png" class="justify-content-center logo" alt="">
                </div>
                <div class="col-md-6">
                    <h5>Al-Qur'an Online</h5>
                    <p class="text-muted">
                        Baca Al-Qur'an secara Online dimana dan kapanpun saja dengan mudah, Al-Qur'an ini yang bersumber
                        dari
                        <a href="#" class="text-decoration-none text-warning">Kementerian Agama Republik Indonesia
                        </a> dengan murottal
                        <strong>Misyari Rasyid Al-'Afasi</strong>.
                    </p>
                </div>
            </div>
            <hr>
            <div class="row">
                <div class="col-md-12 justify-content-center text-center">
                    <span class="">
                        &copy; Copyright 2024 <a href="https://www.adamdev.my.id" target="_blank"
                            class="text-decoration-none text-warning">ADAM DEV.</a> | All Right Reserved
                    </span>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'FooterVue',
    components: {},
}
</script>

<style scoped>
.mt-9 {
    margin-top: 9rem;
}

img.logo {
    width: 75%;
}

@media only screen and (max-width: 768px) {
    img.logo {
        width: 50%;
    }

    .footer {
        text-align: center;
    }
}
</style>