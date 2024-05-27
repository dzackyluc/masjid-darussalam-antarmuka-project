<template>
    <v-app-bar app height="80">
        <template v-slot:prepend>
            <v-img
            src="../assets/logo-appbar.png"
            height="30rem"
            width="10rem"
            ></v-img>
        </template>
        <v-spacer></v-spacer>
        <v-container>
            <v-row class="d-flex justify-end" no-gutters>
                <v-col cols="1">
                    <a href="/profil" :class="[$route.path === '/' ? 'text-decoration-underline' : 'text-decoration-none', 'text-black d-flex justify-center text-button']">Beranda</a>
                </v-col>
                <v-col cols="1">
                    <a href="/profil" :class="[$route.path === '/profil' ? 'text-decoration-underline' : 'text-decoration-none', 'text-black d-flex justify-center text-button']">Profil</a>
                </v-col>
                <v-col cols="1">
                    <a href="/galeri" :class="[$route.path === '/galeri' ? 'text-decoration-underline' : 'text-decoration-none', 'text-black d-flex justify-center text-button']">Galeri</a>
                </v-col>
                <v-col cols="1">
                    <div class="text-center">
                        <v-menu open-on-hover>
                            <template v-slot:activator="{ props }">
                                <a href="#" v-bind="props" class="text-button text-black text-decoration-none">Layanan<v-icon>mdi-chevron-down</v-icon></a>
                            </template>
                            <v-list>
                                <v-list-item v-for="(item, index) in items" :key="index">
                                    <v-btn width="5rem" :to="item.path">{{ item.title }}</v-btn>
                                </v-list-item>
                            </v-list>
                        </v-menu>
                    </div>
                </v-col>
            </v-row>
        </v-container>
        <v-menu open-on-hover>
            <template v-slot:activator="{ props }">
                <v-btn
                    icon
                    v-bind="props"
                >
                    <v-icon size="x-large">mdi-account-circle-outline</v-icon>
                </v-btn>
            </template>
            <v-list>
                <v-list-item>
                    <v-btn width="5rem">Login</v-btn>
                </v-list-item>
            </v-list>
        </v-menu>
    </v-app-bar>
</template>

<script>
  export default {
    data: () => ({
      items: [
        { title: 'Infaq', path: '/infaq' },
        { title: 'Zakat', path: '/zakat' },
        { title: 'Reservasi', path: '/reservasi' },
      ],
    }),
  }
</script>