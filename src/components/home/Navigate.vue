<template>
    <div class="nav">
        <nav id="navbar">
            <div class="navbar__logo">
                <img width="100px" height="100px" src="../../images/logo/favicon.png" alt=""/>
            </div>
            <div>
                <ul class="navbar__menu">
                    <li class="navbar__menu__item active" data-link="#home">Home</li>
                    <li class="navbar__menu__item" data-link="#about">About</li>
                    <li class="navbar__menu__item" data-link="#skills">Skills</li>
                    <li class="navbar__menu__item" data-link="#work">My work</li>
                    <li class="navbar__menu__item" data-link="#contact">Contact</li>
                </ul>
            </div>
        </nav>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>

/* @import "../../assets/css/global.css"; */

/* Navbar */
#navbar {
    position: fixed;
    width: 100%;
    height: 70px;
    display: flex;
    justify-content: space-between;
    /* background-color: var(--color-favorit-puple); */
    background-color: transparent;
    align-items: center;
    color: var(--color-white);
    transition: all var(--animation-duration) ease-in-out;
    z-index: 1;
}

#navbar.navbar--dark {
    background-color: var(--color-favorit-puple);
    padding: 8px;
}

.navbar__menu {
    display: flex;
}

.navbar__menu__item {
    padding: 8px 12px;
    margin: 0 4px;
}

.navbar__menu__item:hover {
    background-color: #71279c;
    /* background-color: var(--color-dark-puple); */
    border-radius: var(--size-border-radius);
    cursor: pointer;
}

.navbar__menu__item.active {
    border: 1px solid var(--color-white);
    border-radius: var(--size-border-radius);
}

</style>