<script>
    import Header from './Header.svelte';
    import Footer from './Footer.svelte';

</script>


<Header />
<main class="container">
    <h2>최고의 무대를 선사하겠습니다.</h2>
    <div class="contact">
        <figure class="map">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3165.9973181836704!2d126.7911681583078!3d37.484389657020394!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x357b62db2d99db03%3A0xca2ab305aecb5f8f!2z6rK96riw64-EIOu2gOyynOyLnCDshozsgqzrj5kgMjYtOA!5e0!3m2!1sko!2skr!4v1769085524246!5m2!1sko!2skr" width="100%" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        </figure>
        <address>
            <p>경기도 부천시 원미구 소사동 26-8, 3층</p>
            <p>(주)더큰세상</p>
            <p>Email: <a href="mailto:agri@gmail.com">agri@gmail.com</a></p>
            <p>Tel:
                <a href="tel:031-0000-0000">031-0000-0000</a>
                <a href="tel:010-0000-0000">010-0000-0000</a>
            </p>
            <p>Fax: 031-0000-0000</p>
        </address>
    </div>

</main>
<Footer />

<style lang="scss">
    .contact {
        display: flex;
        gap: 50px;
        figure, address { width: 50%; }
        address { font-style: normal;}
        a { color: inherit}
    }

    .container {
        background: #fff;
    }
</style>