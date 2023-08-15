<template>
    <div class="nav-bottom-tools">
        <div class="tools">
            <div class="tools-list">
                <div class="tools-item">
                    <img src="@/assets/images/svgs/homenavicon.svg" alt="" />
                    <span class="label">
                        Home
                    </span>
                </div>
                <div class="tools-item">
                    <img src="@/assets/images/svgs/discovernavicon.svg" alt="" />
                    <span class="label">
                        Discover
                    </span>
                </div>
                <div class="tools-item">
                    <img src="@/assets/images/svgs/addnavicon.svg" alt="" />
                </div>
                <div class="tools-item">
                    <img src="@/assets/images/svgs/inboxnavicon.svg" alt="" />
                    <span class="label">
                        Inbox
                    </span>
                </div>
                <div class="tools-item">
                    <img src="@/assets/images/svgs/accountnavicon.svg" alt="" />
                    <span class="label">
                        Me
                    </span>
                </div>
            </div>
        </div>
    </div>
</template>
  
<script>
export default {
    name: 'NavigationComponent',
    props: {
        data: String
    },
    setup() {

    }
}
</script>
  
<style scoped>
.nav-bottom-tools {
    width: 100%;
    min-height: 82.67px;
    background-color: black;
}

.nav-bottom-container>.tools {
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    position: fixed;
    box-sizing: border-box;
}

.nav-bottom-tools>.tools>div {
    min-height: 60px;
    width: 100%;
    display: flex;
    justify-content: space-around;
    align-items: center;
    border-bottom-left-radius: 20px;
    border-bottom-right-radius: 20px;
}

.tools-item{
    display: flex;
    width: 43px;
    align-items: center;
    justify-content: center;
}


.label{
    color: #FFF;
    text-align: center;
    font-family: Poppins;
    font-size: 10px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    letter-spacing: 0.15px;
}

.tools-item {
    display: flex;
    flex-direction: column;
    align-items: center;
}
</style>