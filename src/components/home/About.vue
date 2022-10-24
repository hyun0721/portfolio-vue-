<template>
    <div class="about">
        <section id="about" class="section">
            <div class="section__container">
                <h1>About Me</h1>
                <p>
                    <!-- 주로 Front End(C#, JavaScript)에서 작업하였으며, Data 분석 및 Service, Engine 유지보수를 진행하였다. -->
                </p>        
                <div class="about__majors">
                    <div class="major">
                        <div class="major__icon">
                            <i class="fab fa-html5"></i>
                            <!-- <i class="fa-brands fa-html5"></i> -->
                        </div>
                        <h2 class="major__title">HTML</h2>
                        <div class="major__description">Description</div>
                    </div>
                    <div class="major">
                        <div class="major__icon">
                            <i class="fa-brands fa-square-js"></i>
                        </div>
                        <h2 class="major__title">JavaScript</h2>
                        <div class="major__description">Description</div>
                    </div>
                    <div class="major">
                        <div class="major__icon">
                            <i class="fa-brands fa-vuejs"></i>
                        </div>
                        <h2 class="major__title">Vue.js</h2>
                        <div class="major__description">Description</div>
                    </div>
                    <div class="major">
                        <div class="major__icon">
                            <i class="fas fa-mobile"></i>
                        </div>
                        <h2 class="major__title">Web View</h2>
                        <div class="major__description">Description</div>
                    </div>
                </div>
        
                <!-- 근무 이력, 학습 내용(?) 등 -->
                <div class="about__jobs">
                    <div class="job">
                        <img src="../../images/logo/logisall_logo.png" alt="logisAll" class="job__logo">
                        <div class="job__description">
                            <p class="job__name">Currently working at LogisAll</p>
                            <p class="job__period"></p>
                        </div>
                    </div>
                    <div class="job">
                        <img src="../../images/logo/thira_logo.png" alt="thira-utech" class="job__logo">
                        <div class="job__description">
                            <p class="job__name">Currently working at Thirautech</p>
                            <p class="job__period"></p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>

.about__majors {
    display: flex;
    justify-content: space-between;
    margin: 80px 0;
}

.major__icon {
    width: 170px;
    height: 170px;
    font-size: 70px;
    line-height: 170px;
    margin: auto;
    border: 1px solid var(--color-blue);
    color: var(--color-blue);
    border-radius: 50%;
    margin-bottom: 16px;
}

.major__title,
.major__description {
    color: var(--color-dark-grey);
}

.major__icon i {
    /* 250 ~ 300 이 가장 이상적인 속도 */
    transition: all var(--animation-duration) ease;
}

.major__icon:hover i {
    color: var(--color-pink);
    transform: rotate(-30deg) scale(1);
}

.job {
    display: flex;
    align-items: center;
}

.job__logo {
    width: 200px;
    height: 50px;
}

.job__description {
    margin: 0 16px;
    text-align: left;
}

.job__name,
.job_period {
    color: var(--color-light-grey);
}

.job__name {
    font-size: var(--font-small);
}

.job__period {
    font-size: var(--font-micro);
}

</style>