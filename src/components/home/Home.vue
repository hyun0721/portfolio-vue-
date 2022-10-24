<template>
    <div class="home">
        <section id="home">
            <div class="home__container">
                <img src="../../images/profile.jpg" alt="" class="home_avatar">
                <h1 class="home__title">Hello,<br/> I'm Donghyun Kim</h1>
                <!-- <h2 class="home__description">Communicator, Steady Self-Development </h2> -->
                <button class="home__contact">Contact Me</button>
            </div>
        </section>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>

/* @import "../../assets/css/global.css"; */


#home {
    background: url("../../images/home-background.png") center/cover no-repeat;
    padding: 40px;
    padding-top: 120px;
    text-align: center;
}

.home_avatar {
  width: 250px;
  height: 250px;
  border-radius: 50%;
  border: 2px solid var(--color-white);
}

.home__title,
.home__description {
  color: var(--color-white);
}

.home__contact {
  color: var(--color-white);
  font-size: var(--font-regular);
  font-weight: var(--weight-bold);
  margin: 24px;
  padding: 8px, 12px;
  border: 2px solid var(--color-white);
  border-radius: var(--size-border-radius);
}

</style>