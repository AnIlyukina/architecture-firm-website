<template>
  <section class="about-firm">
    <div class="about-firm__profile">
        <div class="about-firm__about">
            <span class="about-firm__name">Wishbone+Partners</span>
            <h1 class="about-firm__title">The home of beautiful architecture.</h1>
            <p class="about-firm__text">
                We are an architecture firm with a focus on beautiful but functional design. 
                At its heart, we believe design is about usability and accessibility — these are the guiding principles for our work. 
                Read more about our previous projects, our process and our team below.
            </p>
            <a class="about-firm__link">Read more</a>
        </div>
        <img src="../assets/images/architecture.jpg" class="about-firm__image" alt="Архитектура"/>
    </div>
    <div class="about-firm__description">
        <h2 class="about-firm__subtitle">Our Team</h2>
        <div class="about-firm__partner">
          <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. 
              Duis cursus, mi quis viverra ornare, eros dolor interdum nulla, ut commodo diam libero vitae erat. 
              Aenean faucibus nibh et justo cursus id rutrum lorem imperdiet. Nunc ut sem vitae risus tristique posuere.
         </p>
          <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. 
              Duis cursus, mi quis viverra ornare, eros dolor interdum nulla, ut commodo diam libero vitae erat. 
              Aenean faucibus nibh et justo cursus id rutrum lorem imperdiet. Nunc ut sem vitae risus tristique posuere.
          </p>
           <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. 
              Duis cursus, mi quis viverra ornare, eros dolor interdum nulla, ut commodo diam libero vitae erat. 
              Aenean faucibus nibh et justo cursus id rutrum lorem imperdiet. Nunc ut sem vitae risus tristique posuere.
          </p>
        </div>
    </div>
  </section>
</template>

<script>
export default {
    name: 'AboutFirm'
}
</script>

<style lang="scss">

.about-firm{
    display: flex;
    flex-direction: column;
    &__profile{
        display: flex;
        background-color: #ECE7E4;
    }
    &__about{
        padding: 137px 50px 0 100px;
    }

    &__description{
        width: 100%;
        max-width: 760px;
        display: flex;
        justify-content: space-between;
        margin: 0 auto;
        padding: 100px 50px 128px;
    }

    &__image{
        max-width: 720px;
    }
    &__name{
        font-weight: 400;
        font-size: 14px;
        line-height: 20px;
        letter-spacing: 2px;
        text-transform: uppercase;
        color: #645C55;
    }
    &__title{
        font-weight: 400;
        font-size: 64px;
        line-height: 70px;
        color: #1B1A1A;
        margin: 20px 0 0 0;
    }

    &__subtitle{
        font-weight: 400;
        font-size: 32px;
        line-height: 38px;
        color: #403E3B;
    }
    &__text{
        max-width: 509px;
        font-weight: 400;
        font-size: 16px;
        line-height: 24px;
        color: #403E3B;
        margin: 18px 0 0 0;
    }
    &__link{
        display: block;
        margin-top: 41px;
        margin-left: 15px;
        font-weight: 400;
        font-size: 16px;
        line-height: 24px;
        letter-spacing: 0.4px;
        color: #1B1A1A;
    }
    &__partner{
        max-width: 493px;
        font-weight: 400;
        font-size: 16px;
        line-height: 24px;
        color: #403E3B;
    }
}

</style>