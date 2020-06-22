<template>
    <div>
        <v-content>
            <section>
                <v-parallax
                    dark
                    height="600"
                    class="w-75"
                    src="../assets/4154C1E2-7E83-4E11-A915-84B24DBB8966-L0-001.jpg"
                >
                <v-row align="center" justify="center">
                    <v-img 
                        class=""
                        elevation="5"
                        src="../assets/CBLogo1.jpg" 
                        max-width="200"
                        ></v-img>
                    <v-col class="text-center" cols="12">
                        <h1 class="display-1 mb-4">Chick Basket Wheaton</h1>
                        <v-btn
                            tag="a"
                            href="https://www.toasttab.com/chickenbasketwheaton/v2/online-order#!/"
                            rounded
                            color="light-blue"
                            dark
                            elevation="12"
                            class="p-3 m-3"
                            x-large
                        ><h1 class="">ORDER ONLINE NOW!</h1></v-btn>
                    </v-col>
                </v-row>
                </v-parallax>
            </section>
            <section class="py-5">
                <v-container>
                    <v-row class="text-center">
                        <v-col cols="12">
                            <h1 class="mb-2">Chick Basket Wheaton</h1>
                            <p>Chicken Basket Wheaton has been around for more than 40 years! Dedicated to serving the absolute best-fried chicken, burgers, hotsub & fried seafood at A affordable prices. With many hour made sauces to choice from.</p>
                        </v-col>
                        <v-col cols="4">
                            <h3 class="mb-2">Delivery</h3>
                            <p>Ready to send your order anywhere</p>
                        </v-col>
                        <v-col cols="4">
                            <h3 class="mb-2">Catering</h3>
                            <p>Present a special menu at your event</p>
                        </v-col>
                        <v-col cols="4">
                            <h3 class="mb-2">Carry Out</h3>
                            <p>Order and enjoy your food anywhere</p>
                        </v-col>
                    </v-row>
                </v-container>
            </section>
            <section class="py-5 light-blue lighten-5">
                <v-container>
                    <v-row class="text-center">
                        <v-col>
                            <h1>Gallery</h1>
                        </v-col>
                    </v-row>
                    <v-row>
                        <v-col cols="6" sm="6" md="3"><v-img src="../assets/Steak and cheese_191023_0011.jpg"></v-img></v-col>
                        <v-col cols="6" sm="6" md="3"><v-img src="../assets/Buffalo_191023_0010.jpg"></v-img></v-col>
                        <v-col cols="6" sm="6" md="3"><v-img src="../assets/Buffalo_191023_0021.jpg"></v-img></v-col>
                        <v-col cols="6" sm="6" md="3"><v-img src="../assets/Steak and cheese_191023_0013.jpg"></v-img></v-col>
                    </v-row>
                </v-container>
            </section>

            <section id="map">
                <a target="_blank" href="https://www.google.co.th/maps/place/Chicken+Basket/@39.042951,-77.0568754,15.75z/data=!4m5!3m4!1s0x89b7cf03404d31ff:0x61bfaf6aef171187!8m2!3d39.0425426!4d-77.0515549?hl=th">
                    <img
                        style="width:100%;"
                        src="../assets/1584880713258.jpg"
                        alt=""
                    />
                </a>
            </section>
        </v-content>
        <v-footer
            color="light-blue white--text"
        >
            <v-row
                justify="center"
            >
                <v-col cols=12 md=4>
                    <h4 class="pb-3">Address</h4>
                    <p class="mb-1">11435 Georgia Ave, Wheaton, MD 20902</p>
                </v-col>
                <v-col cols=12 md=4>
                    <h4 class="pb-3">Phone</h4>
                    <p class="mb-1">+1 301-949-8818</p>
                    <p>+1 240-678-4991</p>
                </v-col>
                <v-col cols=12 md=4>
                    <h4 class="pb-3">Open hours</h4>
                    <p class="mb-1">Tuesday - Saturday 11:00am - 9:00pm</p>
                    <p class="mb-1">Sunday 12:00pm - 8:00pm</p>
                    <p class="mb-1">Monday closed</p>
                </v-col>
                <v-col
                    class="text-center light-blue darken-2 white--text"
                    cols=12
                >
                    <strong>COPYRIGHT © 2020 ALL RIGHTS RESERVED CHICKEN BASKET WHEATON</strong> | DEVELOPED BY NOTSLEEP TEAM
                </v-col>
            </v-row>
        </v-footer>
    </div>
</template>
