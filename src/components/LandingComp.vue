<template>
    <v-card flat>
        <v-img class="d-flex align-center" src="../assets/Profil Masjid.png">
            <v-card-title class="text-h1 text-white" style="text-shadow: 2px 2px 3px #000000;">MASJID DARUSSALAM</v-card-title>
            <v-card-title class="text-h1 text-white" style="text-shadow: 2px 2px 3px #000000;">SUKMAJAYA DEPOK</v-card-title>
        </v-img>
    </v-card>
    <v-container>
        <v-row>
            <v-col cols="6">
                <v-card flat>
                    <v-card-title class="text-h2" style="color: #4E6F52;">Waktu Sholat</v-card-title>
                    <v-img src="../assets/sholat.png"></v-img>
                </v-card>
            </v-col>
            <v-col cols="6">
                <v-card class="py-13" width="44rem" flat>
                    <v-row class="py-3" no-gutters>
                        <v-col cols="6"><h1 class="font-weight-medium">Depok</h1></v-col>
                        <v-col cols="6"><h1 class="d-flex justify-end text-decoration-underline font-weight-medium">Pilih Lokasi</h1></v-col>
                    </v-row>
                    <v-card class="rounded-xl" color="#F6EFE5" flat>
                        <v-row>
                            <v-col class="d-flex justify-center pt-7" cols="12">
                                <v-sheet class="d-flex align-center rounded-xl" width="40rem" height="5rem" color="#4E6F52">
                                    <v-row>
                                        <v-col class="d-flex px-10" cols="6"><v-icon size="x-large" class="pr-5">mdi-clock-time-three-outline</v-icon><h2 class="font-weight-medium">Matahari Terbit</h2></v-col>
                                        <v-col class="d-flex justify-end px-10" cols="6"><h2 class="font-weight-medium">05:30 AM</h2></v-col>
                                    </v-row>
                                </v-sheet>
                            </v-col>
                            <v-col class="d-flex justify-center" cols="12">
                                <v-sheet class="d-flex align-center rounded-xl" width="40rem" height="5rem" color="#4E6F52">
                                    <v-row>
                                        <v-col class="d-flex px-10" cols="6"><v-icon size="x-large" class="pr-5">mdi-clock-time-three-outline</v-icon><h2 class="font-weight-medium">Subuh</h2></v-col>
                                        <v-col class="d-flex justify-end px-10" cols="6"><h2>05:30 AM</h2></v-col>
                                    </v-row>
                                </v-sheet>
                            </v-col>
                            <v-col class="d-flex justify-center" cols="12">
                                <v-sheet class="d-flex align-center rounded-xl" width="40rem" height="5rem" color="#4E6F52">
                                    <v-row>
                                        <v-col class="d-flex px-10" cols="6"><v-icon size="x-large" class="pr-5">mdi-clock-time-three-outline</v-icon><h2 class="font-weight-medium">Dzuhur</h2></v-col>
                                        <v-col class="d-flex justify-end px-10" cols="6"><h2>05:30 AM</h2></v-col>
                                    </v-row>
                                </v-sheet>
                            </v-col>
                            <v-col class="d-flex justify-center" cols="12">
                                <v-sheet class="d-flex align-center rounded-xl" width="40rem" height="5rem" color="#4E6F52">
                                    <v-row>
                                        <v-col class="d-flex px-10" cols="6"><v-icon size="x-large" class="pr-5">mdi-clock-time-three-outline</v-icon><h2 class="font-weight-medium">Ashar</h2></v-col>
                                        <v-col class="d-flex justify-end px-10" cols="6"><h2>05:30 AM</h2></v-col>
                                    </v-row>
                                </v-sheet>
                            </v-col>
                            <v-col class="d-flex justify-center" cols="12">
                                <v-sheet class="d-flex align-center rounded-xl" width="40rem" height="5rem" color="#4E6F52">
                                    <v-row>
                                        <v-col class="d-flex px-10" cols="6"><v-icon size="x-large" class="pr-5">mdi-clock-time-three-outline</v-icon><h2 class="font-weight-medium">Maghrib</h2></v-col>
                                        <v-col class="d-flex justify-end px-10" cols="6"><h2>05:30 AM</h2></v-col>
                                    </v-row>
                                </v-sheet>
                            </v-col>
                            <v-col class="d-flex justify-center pb-7" cols="12">
                                <v-sheet class="d-flex align-center rounded-xl" width="40rem" height="5rem" color="#4E6F52">
                                    <v-row>
                                        <v-col class="d-flex px-10" cols="6">
                                            <v-icon size="x-large" class="pr-5">mdi-clock-time-three-outline</v-icon><h2 class="font-weight-medium">Isya</h2>
                                        </v-col>
                                        <v-col class="d-flex justify-end px-10" cols="6"><h2>05:30 AM</h2></v-col>
                                    </v-row>
                                </v-sheet>
                            </v-col>
                        </v-row>
                    </v-card>
                </v-card>
            </v-col>
        </v-row>
    </v-container>
</template>

<script>
export default {
    data() {
        return {
            dialog: false,
        }
    }
}
</script>