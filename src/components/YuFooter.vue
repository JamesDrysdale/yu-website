<template>

    <footer>
        <span class="wave">👋</span> <a href="mailto:hello&#64;you-understood.com">Contact Us</a>
        
        <section class="social-icons">
            <a href="https://www.facebook.com/YuUnderstood" target="_blank"><img src="../assets/social/facebook.png" alt="Visit us on Facebook"></a>
            <a href="https://www.instagram.com/yuunderstood/" target="_blank"><img src="../assets/social/instagram.png" alt="Visit us on Instagram"></a>
            <a href="https://www.linkedin.com/company/youunderstood/" target="_blank"><img src="../assets/social/linkedin.png" alt="Visit us on LinkedIn"></a>
            <a href="https://twitter.com/Yu_Understood" target="_blank"><img src="../assets/social/twitter.png" alt="Visit us on Twitter"></a>
        </section>

        <router-link to="/privacy-policy-gdpr">Privacy Policy & GDPR</router-link>

    </footer>

</template>

<script>
export default {
    name: 'YU-Footer'
}
</script>

<style>

footer {
    margin: 0px 0px 0px 0px;
    padding: 20px 20px;
    
    background-color: #324B4A;
    color: #E1E8ED;
}

.social-icons img {
    padding: 24px 25px;
    width: 25px;
}

footer a {
    color: #E1E8ED;
    
}

footer a:hover {
    color: #36C9C6;
}

/*********************************************
/ STYLES TO ANIMATE HAND EMOJI               
/********************************************/

.wave {
    animation-name: wave-animation;  /* Refers to the name of your @keyframes element below */
    animation-duration: 2.5s;        /* Change to speed up or slow down */
    animation-iteration-count: infinite;  /* Never stop waving :) */
    transform-origin: 70% 70%;       /* Pivot around the bottom-left palm */
    display: inline-block;
  }
  
  @keyframes wave-animation {
      0% { transform: rotate( 0.0deg) }
     10% { transform: rotate(14.0deg) }  /* The following five values can be played with to make the waving more or less extreme */
     20% { transform: rotate(-8.0deg) }
     30% { transform: rotate(14.0deg) }
     40% { transform: rotate(-4.0deg) }
     50% { transform: rotate(10.0deg) }
     60% { transform: rotate( 0.0deg) }  /* Reset for the last half to pause */
    100% { transform: rotate( 0.0deg) }
  }


</style>