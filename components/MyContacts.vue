<template>
    <v-row>
        <v-col>
            <div class="contacts">
                <div class="contacts-body">
                    <img class="contacts-body-img" width="25px" height="25px" src="../static/free-icon-chat-4542105.png" alt="telephone">
                    <p class="contacts-body-text" style="margin-top:4px;">+79046155339</p>
                </div>
                <div class="contacts-body">
                    <img class="contacts-body-img" width="25px" height="25px" src="../static/free-icon-mail-4542220.png" alt="email">
                    <p class="contacts-body-text" style="margin-top:4px;">zmohaxz82@gmail.com</p>
                </div>
                <div class="contacts-body" style="margin-top:5px">
                    <img class="contacts-body-img"
                    width="20px"
                    height="20px"
                    src="../static/free-icon-telegram-2111646.png"
                    alt="telegram"
                    >
                    <p class="contacts-body-text">@DPolevikov</p>
                </div>
                <div class="contacts-body" style="margin-top:5px">
                    <img class="contacts-body-img"
                    width="20px"
                    height="20px"
                    src="../static/free-icon-github-2111425.png"
                    alt="github"
                    >
                    <a href="https://github.com/Stranix89" class="contacts-body-text">https://github.com/Stranix89</a>
                </div>
                </div>
        </v-col>
    </v-row>
</template>

<style scoped>
.contacts {
    display: flex;
    justify-content: space-around;
}

.contacts-body {
    display: flex;
    padding-top: 15px;
    margin-left: 10px;
    margin-bottom: 5px;
}
.contacts-body-text {
    margin-left: 5px;
    font-size: 13px;
}
</style>
