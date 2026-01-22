<script>
    import Header from './Header.svelte';
    import Footer from './Footer.svelte';
</script>

<Header />
<main class="container">
    <h2>비보이 브라더스 소개</h2>
    <div class="about">
        <figure class="image">
            <img src="/images/about.jpg" alt="about">
        </figure>
        <div class="content">
            <p>브레이크 댄스의 시초는 미국이지만, 현재는 전 세계 200여개 나라에 브레이크 댄스 씬이 존재합니다. 이 중에서도 한국은 매년 세계 대회에서 우수한 성격을 거두며 비오잉 강국으로 자리매김을 하고 있습니다. 때문인지 한국의 보지옹두출전하 영상에서는 한국 비보이들이 차원이 다르다는 댓시글이 많이 달기기도 하는데요. 한국의 비보이는 맘녕언ㅁ게 존하혐,, 이들은 함께 뭉쳐 쿠를 이루고 있습니다.</p>
            <p>크루의 구성원들은 해외의 대회에 직접 출전하는 건 물로,ㄴ 심사위윈을 ㅏㅇ록 ㅣㅇㅆ스빈다. 또한 이들을 국내에서 대도히를 주최하여 한국의 보비이 씬과 브레이키 ㅇ물화를 소게[이 ㅗ개학 ㅗ잇씁니다. 레르 불을 여러붇릉리 꼭 알아야 할 네팀의 쿠르를 소개하고 자합니다.]</p>
        </div>
    </div>

</main>
<Footer />

<style lang="scss">
    .about {
        display: flex;
        gap: 50px;
        figure, .content { width: 50%; }
        figure img { width: 100%; }
    }

    .container {
        background: #fff;
    }

</style>