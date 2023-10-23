<template>
    <header>
        <nav>
            <RouterLink to="/about">關於我們</RouterLink>
            <RouterLink to="/news">最新消息</RouterLink>
            <RouterLink to="/product">產品介紹</RouterLink>
            <RouterLink to="/"><img src="/public/image/share/logo.svg" alt="logo" class="logo"> </RouterLink>
            <RouterLink to="/course">花藝教室</RouterLink>
            <RouterLink to="/space">空間佈置</RouterLink>
            <RouterLink to="/contact">聯絡我們</RouterLink>
        </nav>
        <nav>
            <RouterLink to="/login"><i class="fa-solid fa-cart-shopping" style="color: #9f9f9f;"></i></RouterLink>
            <RouterLink to="/buy"><i class="fa-solid fa-user" style="color: #9f9f9f;"></i></RouterLink>
        </nav>

        <div class="mobile">
            <nav>
                <RouterLink to="/about">關於我們</RouterLink>
                <RouterLink to="/news">最新消息</RouterLink>
                <RouterLink to="/product">產品介紹</RouterLink>
                <RouterLink to="/course">花藝教室</RouterLink>
                <RouterLink to="/space">空間佈置</RouterLink>
                <RouterLink to="/contact">聯絡我們</RouterLink>
            </nav>
            <div class="hb">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>
    </header>
</template>

<style scoped lang="scss">
header {
    .mobile {
        display: none;
    }

    max-width: 1920px;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    border: 1px solid red;

    a {
        padding: 10px 20px;
        margin: 30px 0;
    }
}
</style>