<template>

    <header>
        <div id="logo-container">
            <div id="logo-square">
                <img class="brand-logo" src="../assets/YU-logo-17-white-cropped.png" alt="">
            </div>
        </div>
    </header>

</template>

<script>

export default {
    
}
</script>

<style>

/*******    STYLES RELATING TO THE BRAND LOGO                *******/

#logo-container {
    display: flex;
    justify-content: center;
    margin: 20px 0px 20px 0px;
}

#logo-square {
    height: 200px;
    width: 200px;
    border-radius: 25%;
    background: linear-gradient(to top right, #6FE3A9 0%, #4AD7BB 35%, #36C9C6  100%);
    
    display: flex;
    justify-content: center;
    align-items: center;
}

.brand-logo {
    width: 90%;
}

</style>