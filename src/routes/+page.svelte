<script>
import Bottom from "../components/+bottom.svelte";
import Right from "../components/+right.svelte";
</script>

<main>
    <div class="side-container">
        <div class="right-top">
            <div class="header">
                    <a href="/home">
                        <img src="images/logo.svg" alt="">
                    </a>
                    <div class="menu">
                        <ul>
                            <li>
                                <a href="/home">home</a>
                            </li>
                            <li>
                                <a href="/about">shop</a>
                            </li>
                            <li>
                                <a href="/services">about</a>
                            </li>
                            <li>
                                <a href="/portfolio">contact</a>
                            </li>
                        </ul>
                     </div>
            </div>
            <div class="main-image">
                <img src="/images/desktop-image-hero-1.jpg" alt="">
            </div>
        </div>
        <div class="left-top">
            <Right/>
        </div>
    </div>
    <Bottom/>
</main>

<style>
    @import url('https://fonts.googleapis.com/css2?family=League+Spartan:wght@400;700&display=swap');
main{
    font-family: 'League Spartan', sans-serif;
    margin: 0;
    padding: 0;
}
.right-top {
    position: relative;
}

.header {
    position: absolute;
    display: flex;
    align-items: center;
    top: 20px;
    left: 20px;
    z-index: 1;
    padding: 10px;
    margin: 30px;
}

.header img {
    height: auto;
    width: 70px;
}

.menu ul {
    list-style-type: none;
    margin-left: 60px;
    padding: 0;
    display: flex;
    font-size: 18px;
}

.menu li {
    margin-right: 40px; 
    color: hsl(0, 0%, 100%);
}

.menu li:last-child {
    margin-right: 0;
}

.menu a {
    text-decoration: none;
    color: hsl(0, 0%, 100%);
    font-weight: bold;
}

.menu a:hover {
    border-bottom: 2px solid  hsl(0, 0%, 100%);
    padding-bottom: 7px;
}


.main-image img {
    display: block;
    margin: 0;
}
.side-container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    margin: 0;
    padding: 0;
}
</style>
