<template>
    <div class="raivofrontcomponent">


        <input>
        gyjyjugfyj

        <div id="nav">
            <router-link to="/">Home</router-link>
            |
            <router-link to="/about">About</router-link>
            |
            <router-link to="/raivofront">RaivoFront</router-link>
        </div>

        <div id="body">

            <div id="selection_account">
                <select name = "sma1" id = "account_selection">
                    <option value = "1">Account_1</option>
                    <option value = "2">Account_2</option>
                    <option value = "3">Account_3</option>
                    <option value = "4">Account_4</option>
                    <option value = "5">Account_5</option>
                </select>
            </div>



            <div id="information">
                MarketPrice |
                SMA 1 |
                SMA 2
            </div>

            <div id="selection_SMA1">
                <select name = "sma1" id = "sma1">
                    <option value = "1">SMA 5</option>
                    <option value = "2">SMA 9</option>
                    <option value = "3">SMA 13</option>
                    <option value = "4">SMA 15</option>
                    <option value = "5">SMA 20</option>
                    <option value = "6">SMA 26</option>

                </select>
            </div>


            <div id="selection_SMA2">
                <select name = "sma2" id = "sma2">
                    <option value = "1">SMA 5</option>
                    <option value = "1">SMA 9</option>
                    <option value = "1">SMA 13</option>
                    <option value = "1">SMA 15</option>
                    <option value = "1">SMA 20</option>
                    <option value = "1">SMA 26</option>

                </select>
            </div>

            <div id="ticker">
                <input>Ticker
                <br>
                <input>Trade
                <br>
                <input>Profit Taker
                <br>
                <input>Stop Loss
                <br>

                <br>

                <router-link to="/">Home</router-link>
                |
                <router-link to="/about">About</router-link>
                |
                <router-link to="/raivofront">RaivoFront</router-link>
            </div>
        </div>

    </div>
</template>

<script>


    // @ is an alias to /src
    import RaivoFrontComponent from '@/components/RaivoFrontComponent.vue'


    export default {
        name: 'RaivoFront',
        components: {
            RaivoFrontComponent
        }
    }
</script>