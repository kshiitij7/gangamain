<template>
    <v-app-bar  app color="#022a38" class="home-page-header" style="height: 8.2vh;" elevation="3">
        <v-row class="fill-height" align="center" justify="space-between">
            <v-img :src="isro" contain height="65px" max-width="120" class="ml-0" />
            <v-img :src="iirslogo" contain height="65px" max-width="80" class="ml-0" />
            <v-spacer></v-spacer>
            
                <div class="header-text">
                    <h3 class="mb-0">भारतीय अंतरिक्ष अनुसंधान संगठन, अंतरिक्ष विभाग</h3>
                    <h3 class="mb-0">Indian Space Research Organisation, Department of Space</h3>
                    <h3 class="mb-0">भारत सरकार / Government of India</h3>
                </div>
           
            <v-spacer></v-spacer>
           
            <v-img :src="india" style="margin-top: 2px;" contain height="60px" max-width="140" class="mr-0" />
        </v-row>
    </v-app-bar>
    </template>
    
    <script>
    export default {
        name: 'HeaderMain',
    
        data: () => ({
            isro: require('@/assets/img/isro.png'),
            iirslogo: require('@/assets/img/iirs.png'),
            india: require('@/assets/img/india.png'),
        }),
    }
    </script>
    
    <style scoped>
    .header-text {
        color: wheat;
        line-height: 1.1;
        margin-top: 5px;
        font-family: 'Poppins', sans-serif;
        font-weight: 300; 
        text-align: center; 
    }
  
    </style>
    
