<template>
    <div class="divider">
        <v-row>
            <img width="285" :height="280" src="https://cdn.sanity.io/images/599r6htc/localized/d6bc9e7515c221ad2bf5e1a4f41ff0c5965963f7-902x888.jpg?w=440&q=75&fit=max&auto=format&dpr=2"/>
           
            <v-col>
                <div class="top-text">With Figma, everyone works towards a shared goal. 
                    This has enabled our product teams to ship new products faster and feel more confident 
                    in their decisions.</div>
                <div class="bottom-text"><b>Matt Gottschalk</b><br>
                    Head of Design Ops at British&nbsp;Telecom</div>
            </v-col>

        </v-row>
    </div>
</template>

<style scoped>
.divider{
    background: rgb(199, 185, 255);
    padding: 40px;
    margin: 50px 0;
}

img{
    margin-right: 50px;
}
.top-text{
    border: 1px solid black;
    padding: 15px;
}

.bottom-text{
    margin-top: 24px;
    margin-left: 24px;
}
</style>