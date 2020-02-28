<template>
<div id="whole">
    <div id="main">
        <router-link id="change" to="/reg">
            Back
        </router-link>
        <div id="overlay"> </div>
        <div id="rectangle">
            <img id="holder" src="/assets/namecard.png"/> 
            <h1> MEMBER LOGIN </h1>
        </div> 
        <form id="login">
            <div class="form">
                 <input type='text' name="username" v-model="input.username" placeholder="User ID / Email" />
            </div>
            <div class="form">
                <input type='password' v-model='input.password' placeholder="Password" />
            </div>
            <div>
                <button id="start" type="button" v-on:click="login()"> LOGIN </button>
            </div>
        </form>
    </div>
</div>
</template>

<script>

export default {
    name: 'Login',
    data() {
        return {
            input: {
                username: "",
                password: ""
            }
        }
    },
    methods: {
        login() {
            return this.input.username + this.input.password;
        }
    }
}
</script>

<style scoped>

#whole {
    height: auto;
    width: auto;
}
    #main {
        height: 100%;
        width: 100%;
        background-image: url('/assets/login.jpeg');
        background-size: 100%;
        position: absolute;
    }

    #overlay{
        position: absolute;
        background: rgba(23, 23, 23, 0.49);
        height: 100%;
        width: 100%;
        margin-top: -55px;
        background-size: 100%
    }

    #rectangle {
        position: absolute;
        width: 977px;
        height: 560px;
        left: 231px;
        margin-top: 100px;
        background: rgba(196, 196, 196, 0.7);
    }

    #holder {
        height:97px;
        width:107px;
        margin-left: 440px;
        margin-top: 40px;
        text-align: center;
    }

    h1 {
        font-family: 'Futura Hv BT';
        font-size: 40px;
        margin-left: 336px;
        margin-top: 10px;
        color: #000000;
    }

    #login {
        position: absolute;
        height: 81px;
        left: 410px;
        top: 400px;
    }

    input {
        width: 607px;
        height: 60px;
    }

    .form {
        margin-bottom: 40px;
    }

    #start {
        background-color:#84CEEB; 
        width:385px; 
        height:43px;
        font-family:'Futura Hv BT'; 
        font-size:20px; 
        color:#FFFFFF;
        margin-left: 114px;
        top: 60px;
    }

    #change {
        font-family: Futura Hv BT;
        font-style: normal;
        font-weight: 800;
        font-size: 20px;
        line-height: 54px;
        display: flex;
        align-items: center;
        text-align: center;
        margin-left: 50px;
        color: #ffffff;
        z-index: 99999;
        position: relative;
    }

</style> 