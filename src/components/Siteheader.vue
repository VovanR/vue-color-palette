<template>
    <div class="navbar navbar-default">
        <div class="container">
            <div class="navbar-header">
                <span class="brand navbar-brand">
                    <span class="brand__text">Color Palette</span>
                    <span class="brand__label label label-default">Vue.js</span>
                </span>
            </div>

            <div class="navbar-collapse collapse">
                <p class="navbar-text">Just for fun</p>

                <div class="navbar-text navbar-right">
                    <div class="repo-link">
                        <span class="repo-link__icon">
                            <icon name="ei-sc-github" size="s"></icon>
                        </span>
                        <span class="repo-link__text">VovanR/vue-color-palette</span>
                        <a class="repo-link__link" href="https://github.com/VovanR/vue-color-palette"></a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
</script>

<style>
.brand {
}

.brand__label {
    vertical-align: super;
    font-size: 50%;
}

.brand__text {
}

.repo-link {
    position: relative;
    display: block;
    text-decoration: none;
}

.repo-link__icon {
    display: inline-block;
    margin: -3px 0 -4px;
    vertical-align: middle;
    height: 25px;
}

.repo-link__link {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}

.repo-link__text {
    font-size: 12px;
}

.repo-link:hover .repo-link__text {
    text-decoration: underline;
}
</style>
