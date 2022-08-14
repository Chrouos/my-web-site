<template>

<!-- 選單 -->
<div class="out">
    <div class="navigation">
        <ul>
            <li>
                <a>
                    <span><i class="fa fa-address-book icon" aria-hidden="true"></i></span>
                    <span class="title">基本資料</span>
                </a>
            </li>     
            <li>
                <a>
                    <span><i class="fa fa-graduation-cap icon" aria-hidden="true"></i></span>
                    <span class="title">在校成績</span>
                </a>
            </li>     
        </ul>
    </div>
</div>

</template>

<style scoped>

.out{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.navigation{
    background: white;
    padding: 10px;
}

.navigation ul{
    padding: 0; 
} 

.navigation ul li{
    list-style: none;
    display: flex;
    justify-content: center;
}

.navigation ul li a{
    display: flex;

    width: 200px;
    flex-direction: row;
    justify-content: space-evenly;
}

.navigation ul li .icon {
    font-size: 2rem;
    left: -20%;

    margin: 10px 20px;
    align-self: center;
}

.navigation ul li .title {
    align-self: center;
    font-size: 1.5rem;
}
</style>
