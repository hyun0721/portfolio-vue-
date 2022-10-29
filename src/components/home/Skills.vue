<template>
    <div class="skills">
        <section id="skills" class="section">
            <div class="section__container">
                <h1>Skills</h1>
                <h2>Skills & Attribute</h2>
                <p>
                    <!-- 기술 관련 내용  : 뭘 공부하고있고, 현재 공부하는 법, 스트레스 관리 등 학습에 대한 부분 -->
                </p>
        
<!--

[Star]
<i class="fa-solid fa-star"></i>

[Half Star]
<i class="fa-solid fa-star-half-stroke"></i>

[Empty Star]
<i class="fa-regular fa-star"></i>

-->
                <div class="skillset">
                    <div class="skillset__left">
                        <h3 class="skillset__title">Skills</h3>
                        <div class="skill">
                            <table style="width:100%">
                                <colgroup>
                                    <col width="10%">
                                    <col width="50%">
                                </colgroup>
                                <tr>
                                    <th>
                                        <div class="skill_desc">
                                            <span>JavaScript</span>
                                        </div>
                                    </th>
                                    <td>
                                        <div class="skill__level">
                                            <i class="fa-solid fa-star"></i>
                                            <i class="fa-solid fa-star"></i>
                                            <i class="fa-solid fa-star"></i>
                                            <i class="fa-solid fa-star"></i>
                                            <i class="fa-solid fa-star-half-stroke"></i>
                                        </div>
                                    </td>
                                </tr>
                                <tr>
                                    <th>
                                        <div class="skill_desc">
                                            <span>HTML</span>
                                        </div>
                                    </th>
                                    <td>
                                        <div class="skill__level">
                                            <i class="fa-solid fa-star"></i>
                                            <i class="fa-solid fa-star"></i>
                                            <i class="fa-solid fa-star"></i>
                                        </div>
                                    </td>
                                </tr>
                                <tr>
                                    <th>
                                        <div class="skill_desc">
                                            <span>CSS</span>
                                        </div>
                                    </th>
                                    <td>
                                        <div class="skill__level">
                                            <i class="fa-solid fa-star"></i>
                                            <i class="fa-solid fa-star"></i>
                                            <i class="fa-solid fa-star-half-stroke"></i>
                                        </div>
                                    </td>
                                </tr>
                            </table>
                        </div>
                    </div>
                    <div class="skillset__right">
                        <div class="tools">
                            <h3 class="skillset__title">Tools</h3>
                            <ul class="tools__list">
                                <li><span>Visual Studio</span></li>
                                <li><span>Visual Studio Code</span></li>
                                <li><span>Eclipse</span></li>
                                <li><span>SQL Developer</span></li>
                                <li><span>PyCharm</span></li>
                            </ul>
                        </div>
                        <div class="etc">
                            <h3 class="skillset__title">Etc</h3>
                            <ul class="etc__list">
                                <li><span>TFS</span></li>
                                <li><span>Git</span></li>
                                <li><span></span></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
export default {

    /** 퍼센트 보다 상,중,하 로 나누는것이? */

}
</script>

<style>
#skills {
    background-color: var(--color-yellow);
}

.skillset {
    display: flex;
    background-color: var(--color-light-grey);
    color: var(--color-light-white);
    margin: 20px 0;
}

.skillset__title {
    color: var(--color-white);
}

.skillset__left {
    flex-basis: 60%;
    background-color: var(--color-dark-grey);
}

.skillset__right {
    flex-basis: 40%;
}

.skill {
    margin: 32px;
    display: inline-flex;
    flex-direction: row;
    justify-content: flex-start;
    width: 100%;
}

.tools {
    background-color: var(--color-grey);
}

.tools,
.etc {
    padding: 20px;
}

.skill_desc {
    display: flex;
    justify-content: space-between;
    margin-right: 10px;
}

.skill__level {
    color: orange;
    display: inline-flex;
    justify-content: flex-start;
    width: 100%;
    /* display: inline-flex;
    flex-direction: row;
    justify-content: flex-start; */
}

.skill__bar {
    width: 100%;
    height: 3px;
    background-color: var(--color-light-grey);
}

.skill__value {
    height: 3px;
    background-color: var(--color-orange);
}
</style>