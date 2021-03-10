<template>

    <header>
        <div id="logo-container">
            <div id="logo-square">
                <img class="brand-logo" src="../assets/YU-logo-17-white-cropped.png" alt="">
            </div>
        </div>

        <nav>
            <router-link to="/" class="nav-link">Home</router-link>
            <router-link to="/about-yu" class="nav-link">Who are YU?</router-link>
        </nav>
        <router-view/>
    </header>

</template>

<script>

export default {
    
}
</script>

<style>

/*********************************************
/ STYLES RELATING TO THE BRAND LOGO                
/********************************************/

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

/*********************************************
/ STYLES RELATING TO THE NAVIGATION BAR             
/********************************************/

nav {
    margin: 70px 0px 0px 0px;
    padding: 8px;
    background-color: #324B4A;
    text-align:center;
}

a {
    color: #E1E8ED;
    padding: 0px 16px;
}

/* Change the link color on hover */
a:hover {
    font-weight: 700;
}


</style>