
Skip to content

    Features
    Platform
    Business
    Explore
    Pricing

Sign in
Sign up

37
321

    196

iamshaunjp/vuejs-playlist
Code
Issues 2
Pull requests 3
Projects 0
Insights
Join GitHub today

GitHub is home to over 28 million developers working together to host and review code, manage projects, and build software together.
vuejs-playlist/src/components/formTwo.vue
89bedc6 on Apr 3, 2017
Shaun Pelling added lesson 28 code
46 lines (41 sloc) 961 Bytes
<template>
    <div>
        <form-helper>
            <div slot="form-header">
                <h3>Form Two - Log In</h3>
                <p>Enter your details to log-in</p>
            </div>
            <div slot="form-fields">
                <input type="text" placeholder="username" required />
                <input type="password" placeholder="password" required />
            </div>
            <div slot="form-controls">
                <button v-on:click="handleSubmit">Login</button>
            </div>
        </form-helper>
    </div>
</template>

<script>
// Imports
import formHelper from './formHelper.vue'
export default {
    components: {
        'form-helper': formHelper
    },
    data () {
        return {
        }
    },
    methods: {
        handleSubmit: function(){
            alert('thanks for logging in (form two)');
        }
    }
}
</script>

<style>
body{
    margin: 0;
    font-family: 'Nunito SemiBold';
}
</style>

    © 2018 GitHub, Inc.
    Terms
    Privacy
    Security
    Status
    Help

    Contact GitHub
    Pricing
    API
    Training
    Blog
    About

Press h to open a hovercard with more details.
